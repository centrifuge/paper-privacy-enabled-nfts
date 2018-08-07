# Privacy-Enabled NFTs: Self-Mintable Non-Fungible Tokens With Private Off-Chain Data 
To read the latest version of the paper, check out the [releases on github](https://github.com/CentrifugeInc/paper-privacy-enabled-nfts/releases)

## Building 
The easiest way to generate a PDF out of the tex file is with docker:

```
docker run --rm -i --user="$(id -u):$(id -g)" --net=none -v "$PWD":/data "blang/latex:ctanfull" latexmk -pdf -outdir=./build
```


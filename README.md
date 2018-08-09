# Privacy-Enabled NFTs: Self-Mintable Non-Fungible Tokens With Private Off-Chain Data 
To read the latest version of the paper, check out the [releases on github](https://github.com/CentrifugeInc/paper-privacy-enabled-nfts/releases)

## Revisions
* [v1.01](https://github.com/centrifuge/paper-privacy-enabled-nfts/releases/tag/v1.01): minor udpate renaming the PDF to something more useful
* [v1](https://github.com/centrifuge/paper-privacy-enabled-nfts/releases/tag/v1): Published on 08-08-2018


## Building 
The easiest way to generate a PDF out of the tex file is with Docker. The generated file is put in `build/main.pdf`

```
docker run --rm -i --user="$(id -u):$(id -g)" --net=none -v "$PWD":/data "blang/latex:ctanfull" latexmk -pdf -outdir=./build
```


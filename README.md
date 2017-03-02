# tensorflow-python-mnist-codelab
Github tutorial: https://github.com/martin-gorner/tensorflow-mnist-tutorial

## Synopsis

This codelab is taken from the original codelab at Google Developer [https://codelabs.developers.google.com/codelabs/cloud-tensorflow-mnist] and modified for offline use by the GDG Kota Kinabalu community.

## Motivation

Due to poor Internet connection, most of the setup and installation instructions in Google codelabs are impractical, requiring a huge amount of download and/or updating power that the developing and emerging countries could not possibly cater. This codelab removes as much as possible the need to download via Internet, and instead package all required files, instructions, fonts, and sample codes into one single repo. This repo can then be run via a local web server or distributed using a removable storage. Instructions and links are also changed to reflect options for offline download (i.e. within the repo itself, instead to external locations like GitHub, CDNs and the likes).

What's NOT included in this codelab are the installers mentioned in docs/INSTALL.txt, for the purpose of ease of codelab distribution. Preferably, all the installers should also be downloaded prior to using this codelab, linked appropriately, and distributed as necessary. 

## Installation

This repo requires that you have node.js and npm's Bower installed in your machine, for the initial download. npm's Polymer is optional if you already have a web server in your machine. Otherwise, you can install Polymer via npm and use polymer serve to run the codelab in your local machine via HTTP. You can also use Python and run python -m http.server within the codelab's root folder.

This repo should be downloaded once, its Bower package updated once, and then the downloaded/cloned folder distributed to the rest of the members via a local web server or removable drive.

## Contributors

Please issue a pull request.

## License

This license follows its respective owners for Polymer and the tutorial.

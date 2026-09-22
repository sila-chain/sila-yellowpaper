# Sila Yellow Paper

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Gitter](https://badges.gitter.im/sila-chain/sila-yellowpaper.svg)](https://gitter.im/sila-chain/sila-yellowpaper?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![GitPOAP Badge](https://public-api.gitpoap.io/v1/repo/sila-chain/sila-yellowpaper/badge)](https://www.gitpoap.io/gh/sila-chain/sila-yellowpaper)

The Yellow Paper is a formal definition of the Sila protocol, originally by Gavin Wood, currently maintained by Andrew Ashikhmin and with contributions from many people around the world.

It is a free culture work, licensed under Creative Commons Attribution Share-Alike (CC-BY-SA) Version 4.0.

## Repository Currently Outdated

The Yellow Paper is out of date. It reflects the Sila specification up to the [SilaShanghai](https://github.com/sila-chain/execution-specs/blob/forks/amsterdam/src/sila/forks/shanghai/__init__.py) network upgrade, activated on the Sila sila-mainnet at block `17_034_870` (April 2023). 

It does **not** yet contain changes introduced by the SilaCancun upgrade.

An alternative [Python Execution Layer specification](https://github.com/sila-chain/execution-specs) is actively maintained and up to date. 

## Usage

A published PDF is not currently configured for this repository. To read or edit the paper, build it locally as described below.

However, if you want to edit the paper, then read on. The paper comes as a single ``latex`` file ``Paper.tex``.  

It is recommended to use an IDE such as [Visual Studio Code](https://code.visualstudio.com/) with the LaTeX Workshop extension, to edit the tex file, and show the PDF.

Another option is to separately edit the `tex` file and build as follows (you'll still need to clone the repo then open the yellowpaper folder):

```
git clone https://github.com/sila-chain/sila-yellowpaper.git
cd sila-yellowpaper
./build.sh
```
This will create a PDF version of the Yellow Paper. Following building, you can also use standard `pdflatex` tools for compiling/preview, like http://latex.informatik.uni-halle.de/latex-online/latex.php.

## Tips on editing

You can use [TeX Stack Exchange](https://tex.stackexchange.com/); https://en.wikibooks.org/wiki/LaTeX/ (e.g. [Bibliography Management](https://en.wikibooks.org/wiki/LaTeX/Bibliography_Management) and [Hyperlinks](https://en.wikibooks.org/wiki/LaTeX/Hyperlinks)); and [BibTeX editor](http://truben.no/latex/bibtex/).

## Versions

The previous protocol versions are listed in [BRANCHES.md](./BRANCHES.md).

### Other language versions
- [Chinese](https://github.com/yuange1024/ethereum_yellowpaper) translated by YuanGe and GaoTianlu.
- [French](https://github.com/asseth/yellowpaper) translated by Asseth (checkout to branch 'french' ).
- [Vietnamese](https://github.com/kodyfanz/ethereum_yellowpaper_vn) translated by KodyFanz (checkout to branch 'vietnamese').

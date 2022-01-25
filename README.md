__Latest release:__ [![DOI](https://www.fdr.uni-hamburg.de/badge/DOI/10.25592/uhhfdm.9643.svg)](https://doi.org/10.25592/uhhfdm.9643)

__This release:__ See [release description](https://github.com/DGS-Korpus/HamNoSys4TeX/releases/tag/v1.0.2).


# _hamnosys_ - Using HamNoSys in TeX
This is the TeX package _hamnosys_, which makes the HamNoSys font available in TeX documents.
The Hamburg Notation System, HamNoSys for short, is a system for the phonetic transcription of signed languages.

# Requirements
The _hamnosys_ package requires XeLaTeX or LuaLaTeX. It has been tested on TeX Live 2021.

# Installation
If your TeX distribution does not contain the package, you can install it manually by copying the files `hamnosys.sty` and `HamNoSysUnicode.ttf` from this repository. To install it locally for a single project, copy the files into the root directory of your TeX project. To install it globally, copy the files into a `hamnosys/` subdirectory in the appropriate location in your TeX installation. To generate the documentation, compile `hamnosys.dtx` using XeLaTeX or LuaLaTeX.

To use HamNoSys in other parts of your operating system and for a wider range of input methods, see the [HamNoSys Software Package](https://doi.org/10.25592/uhhfdm.9724).

# Usage
The package provides three methods of entering HamNoSys symbols:
1. Direct input of HamNoSys symbols as Unicode characters. As HamNoSys symbols can only be displayed by the HamNoSys font, you must either
   1. explicitly switch fonts using `\texthamnosys{}` or `\hamnosysfont`, or 
   2. use the `autofont` package option (XeTeX only).
2. Listing HamNoSys symbol names inside the command `\hamnosys{}`.
3. Using the commands that have been defined for each individual HamNoSys symbol.

For more details, read the [full documentation](hamnosys.pdf) (English) or [project note AP04-2021-02](https://doi.org/10.25592/uhhfdm.9637) of the DGS corpus project (English and German).

# Licence & Copyright
Copyright (C) 1986-2022 Universität Hamburg

Created by Marc Schulder, Thomas Hanke

This work may be distributed and/or modified under the conditions of the [LaTeX Project Public License](http://www.latex-project.org/lppl.txt), either version 1.3c of this license or (at your option) any later version.

This work has the LPPL maintenance status `maintained'.

The Current Maintainer of this work is Marc Schulder.

This work consists of the files hamnosys.dtx, hamnosys.ins,
HamNoSysUnicode.ttf, README.md and the derived files
hamnosys.sty, hamnosys.pdf and hamnosys.bib.
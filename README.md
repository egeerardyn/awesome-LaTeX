# Awesome LaTeX

This is a curated list of awesome stuff for the (La)TeX typesetting system.
[![Awesome][awesome]](https://github.com/sindresorhus/awesome) [![Issue Count](https://codeclimate.com/github/egeerardyn/awesome-LaTeX/badges/issue_count.svg)](https://codeclimate.com/github/egeerardyn/awesome-LaTeX) [![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg?style=flat)](LICENSE.md)

## Contents

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Awesome LaTeX](#awesome-latex)
	- [Contents](#contents)
	- [Distributions](#distributions)
	- [Engines](#engines)
		- [LaTeX formulas on the web](#latex-formulas-on-the-web)
	- [Editors](#editors)
		- [LaTeX-focussed](#latex-focussed)
		- [General purpose text editors](#general-purpose-text-editors)
		- [Online editors](#online-editors)
	- [Bibliography tools](#bibliography-tools)
	- [Misc. Tools](#misc-tools)
	- [LaTeX-compatible GUI tools](#latex-compatible-gui-tools)
	- [Packages](#packages)
		- [Tables](#tables)
		- [Graphics](#graphics)
			- [PSTricks](#pstricks)
			- [TikZ](#tikz)
	- [Templates](#templates)
	- [Symbols](#symbols)
	- [Resources](#resources)
	- [Tutorials](#tutorials)
	- [Books](#books)
	- [Blogs](#blogs)
	- [Social media](#social-media)
- [Meta Awesome-LaTeX](#meta-awesome-latex)
	- [Legend](#legend)

<!-- /TOC -->

## Distributions

- [MacTeX](https://tug.org/mactex/) - Most common LaTeX distribution for Mac OS X, basically TeXLive with some Mac-specific tools added. ![Mac][mac]
- [TeX Live](http://www.tug.org/texlive/) - Most common LaTeX distribution for Unices and Linux, but also works on Windows. ![Linux][linux] ![Windows][windows]
- [MikTeX](http://miktex.org) - Most common LaTeX distribution for Windows (only). ![Windows][windows]

## Engines

- [pdfTeX](http://www.tug.org/applications/pdftex/) - TeX compiler that produces PDF files immediately instead of DVI files (nowadays, this is the standard compiler for many users). ![foss][foss]
- [XeTeX](http://xetex.sourceforge.net) - TeX compiler that provides better unicode and font support than TeX/pdfTeX (i.e. you can use the  fonts of your operating system instead of only TeX fonts). ![foss][foss]
- [LuaTeX](http://www.luatex.org) - (La)TeX compiler that supports Lua code for scripting and has improved unicode and font support than standard TeX/pdfTeX. ![foss][foss]

### LaTeX formulas on the web

- [MathJaX](https://www.mathjax.org) - JavaScript engine to render mathematical formulas on the web. The outcome looks really slick. ![foss][foss]
- [mimeTeX](http://www.forkosh.com/mimetex.html) - mimeTeX is a rather old tool to render LaTeX formulas to PNG figures for your web site, without actually needing a LaTeX installation on your server. ![foss][foss]
- [mathTeX](http://www.forkosh.com/mathtex.html) - mathTeX is the successor of mimeTeX: it produces nicer-looking images but it requires LaTeX to be installed on your server. ![foss][foss]

## Editors

Because editing LaTeX code with notepad is not awesome.

### LaTeX-focussed

Some of the most awesome editor for LaTeX do just that: edit LaTeX

- [Kile](http://kile.sourceforge.net) - Just a great LaTeX editor originally from the Linux/KDE community, but runs just fine on Windows and OS X as well. ![foss][foss]
- [TeXMaker](http://www.xm1math.net/texmaker/) - Pretty good alternative to Kile.
- [TeXStudio](http://www.texstudio.org) - Cross-platform LaTeX editor that stems from TeXMaker.
- [WinEdt](http://www.winedt.com) - The LaTeX editor many people swear by. Only for ![Windows][windows].
- [TeXnicCenter](http://www.texniccenter.org) - A quite old but free and decent editor for LaTeX. ![Windows][windows]
- [LyX](https://www.lyx.org) - Cross-platform WYSIWYM editor that uses LaTeX behind the scenes to render documents. ![foss][foss]
- [TeXshop](http://pages.uoregon.edu/koch/texshop/) - No-nonsense editor for LaTeX documents which is included in MacTeX. ![Mac][mac]
- [TeXWorks](https://www.tug.org/texworks/) - No-nonsense editor for LaTeX code, modeled after TeXShop, but this one is cross-platform. ![foss][foss]
- [BakomaTex](http://www.bakoma-tex.com) - Commercial LaTeX editor that allows to edit your document both using its source code and WYSIWYG.
- [Inlage](http://www.inlage.com/home) - Commercial LaTeX editor with handwritten formula recognition, Excel importing and more nifty features. ![Windows][windows]
- [Texpad](https://www.texpadapp.com) - Commercial LaTeX editor for OS X and iOS, with excellent features (document overview, synchronised PDF display, autocompletion, sync across devices...) that never get in the way of writing. ![Mac][mac]

### General purpose text editors

These editors are no one-trick ponies: sure, they edit LaTeX, but they can do a lot more!

- [Atom](https://atom.io) [![Atom][awesome]](https://github.com/mehcode/awesome-atom) ![foss][foss]
	- [LaTeXTools](https://atom.io/packages/latextools) - An Atom port of the Sublime Text package of the same name. ![foss][foss]

- [Sublime Text](http://www.sublimetext.com) [![Sublime Text][awesome]](https://github.com/dreikanter/sublime-bookmarks)
	- [LaTeXing](http://www.latexing.com) - Commercial plug-in to edit LaTeX.
	- [LaTeXTools](https://github.com/SublimeText/LaTeXTools) - Free LaTeX plugin for Sublime Text. ![foss][foss]

- [Emacs](https://www.gnu.org/software/emacs/)  [![Emacs][awesome]](https://github.com/emacs-tw/awesome-emacs) ![foss][foss]
	- [AucTeX](https://www.gnu.org/software/auctex/) - Emacs plugin for LaTeX that also shows a preview of equations and figures. ![foss][foss]

- [Vim](http://www.vim.org) [![Vim][awesome]](https://github.com/mhinz/vim-galore) ![foss][foss]
	- [Vim-LaTeX](http://vim-latex.sourceforge.net) ![foss][foss]
	- [LaTeX Live Preview](https://github.com/xuhdev/vim-latex-live-preview) - Instantly previews your LaTeX document. ![foss][foss]

### Online editors

Online editors that allow you to edit documents collaboratively.

- [Authorea](https://www.authorea.com) - Online editor with built-in git support and bibliography tools.
- [ShareLaTeX](https://www.sharelatex.com) - Has pretty great LaTeX documentation and simple version control.
- [Overleaf](https://www.overleaf.com) - Online editor, also with a WYSIWYM editor and git support.
- [Papeeria](https://papeeria.com) - Online editor with built-in git support.
- [JaxEdit](http://jaxedit.com/page/jaxedit.html) - Online LaTeX editor with Live Preview and nice presentation mode.

## Bibliography tools

- [JabRef](http://jabref.sourceforge.net) - Very powerful cross-platform (Java) bibtex editor. The GUI looks quite dated, though. ![foss][foss]
- [Bibdesk](http://bibdesk.sourceforge.net) - Great bibliography editor for ![Mac][mac].
- [Zotero](https://www.zotero.org) - Reference manager for your browser that also exports to bibtex and integrates with many LaTeX editors.
- [Mendeley](https://www.mendeley.com) - Both an app and cloud client to manage your references and PDFs. Can sync out to a bibtex file for your LaTeX workflow.

## Build Tools

Compiling LaTeX documents can be tedious, build tools help you to manage the compilation process.

- [Arara](https://www.ctan.org/pkg/arara) ([GitHub repo](https://github.com/cereda/arara)) - Simple tool that allows you to specify which tools to call inside your document and it can be extended quite easily. ![foss][foss]
- [latexmk](https://www.ctan.org/pkg/latexmk) - Build tool that is the commonly used by many LaTeX editors (LaTeXing, TeXShop, ...) to build your LaTeX files. ![foss][foss]

## Misc. Tools

- [CaTeX](https://github.com/Alexis-benoist/CaTeX) - Concatenates LaTeX documents with attention for properly merging the preamble.
- [Pandoc](http://pandoc.org) - This program converts almost any document format (LaTeX, DOC, markdown, ...) to almost any other format. A great tool to aid workflows where multiple formats are used. ![foss][foss]
- [Codecogs Eqn Editor](https://www.codecogs.com/latex/eqneditor.php) - Online LaTeX equation editor that allows you to produce figures containing an equation.
- [LaTeXiT](http://www.chachatelier.fr/latexit/) - LaTeXit is an equation editor that makes it easy to drag-and-drop rendered equations (as PDF, PNG, ...) into your non-LaTeX documents on the Mac. ![Mac][mac]
- [KLaTeXFormula](http://klatexformula.sourceforge.net) - Cross-platform alternative for LaTeXit. ![foss][foss]
- [EqualX](http://equalx.sourceforge.net) - Graphical LaTeX formula editor. ![Windows][windows] ![Linux][linux] ![foss][foss]
- [ChkTeX](http://baruch.ev-en.org/proj/chktex/) - Linter / code checker for LaTeX documents. ![foss][foss]

## LaTeX-compatible GUI tools

- [TikzEdt](http://www.tikzedt.org) (also:  [GitHub repo](https://github.com/hchapman/tikzedt)) - WYSIWYG and text-based editor for TikZ pictures. ![foss][foss]
- [TikZ-Editor](https://github.com/fredokun/TikZ-Editor) - Live-previewing editor for TikZ figures. ![Mac][Mac] ![Linux][Linux] ![foss][foss]
- [IPE](http://ipe.otfried.org) - Drawing tool that integrates well with LaTeX commands and documents. ![foss][foss]
- [GeoGebra](http://www.geogebra.org/cms/) - Cross-platform geometry tool with output to TikZ. ![foss][foss]
- [Dia](https://wiki.gnome.org/Apps/Dia) - Cross-platform diagramming tool that can export to PSTricks and MetaPost code. ![foss][foss]

## Packages

- [CTAN](http://ctan.org) - The Comprehensive TeX Archive Network is the place to look for useful packages and documentation.

### Tables

- [Excel2LaTeX](https://www.ctan.org/pkg/excel2latex?lang=en) - Excel (2010 and older) macros to produce LaTeX `tabular` code. ![Windows][windows] ![Mac][mac]
- [csv2latex](http://www.freecode.com/projects/csv2latex) - Converts CSV files from your favorite programs to LaTeX `tabular`s. ![Linux][linux] ![Mac][mac]
- [Tables Generator](http://www.tablesgenerator.com) - This website provides a graphical interface to input your table and produces properly-formatted code for LaTeX, Markdown, HTML, ...
- [pgfplotstable](https://www.ctan.org/pkg/pgfplotstable?lang=en) - This package dis­plays nu­mer­i­cal ta­bles rounded to de­sired pre­ci­sion in var­i­ous dis­play for­mats. It can even read CSV files to include directly in your LaTeX document.

### Graphics

#### PSTricks

PSTricks is a great library to draw figures for inclusion in PostScript/DVI files.

#### TikZ

TikZ is an awesome package with many plugins that allow you to create figures from within your LaTeX documents.
Typically, it is easier to get to work with `pdflatex` than PSTricks is.

- [TeXample](http://www.texample.net) - Blog about LaTex, with a big collection of TikZ figures.
- [LaTeX en SI](http://sciences-indus-cpge.papanicola.info/-LaTeX-en-SI-) - Useful website with some custom packages to draw special plots (Bode, Nyquist, electrical schematics, block schematics, ...) using TikZ. Note that everything is in French.
- [tkz](http://altermundus.com/pages/tkz/index.html) - A collection of TikZ-based packages to make plots and graphs.
- [pgfplots](http://pgfplots.sourceforge.net) - A truely awesome plotting library on top of and in the style of TikZ/pgf. This library can load in CSV data files, perform some calculations and create beautiful plots.
- [A very minimal introduction to TikZ (PDF)](http://bit.ly/gNfVn9) - A short introductory document to the world of TikZ, written by Jacques Crémer.
- [PetarV-/TikZ](https://github.com/PetarV-/TikZ) - A collection of publication-ready PGF/TikZ figures by Petar Veličković.

## Templates

- [LaTeX templates](http://www.latextemplates.com) - Collection of templates for papers, posters, resumés, theses, books, presentations, … for LaTeX.
- [HowtoTeX: templates](http://www.howtotex.com/category/templates/) - Different templates for LaTeX under a CC-NC-SA license.

## Symbols

- [Comprehensive LaTeX symbol list](http://www.ctan.org/tex-archive/info/symbols/comprehensive/) - A very extensive list of symbols for LaTeX. Available in [A4](http://mirrors.ctan.org/info/symbols/comprehensive/symbols-a4.pdf) and [letter](http://mirrors.ctan.org/info/symbols/comprehensive/symbols-letter.pdf) sizes.
- [Detexify](http://detexify.kirelabs.org/classify.html) - You draw the symbol and this site/app will tell you the LaTeX command.

## Resources

- [TUG](https://www.tug.org) - The TeX User Group is a way to get in touch with other (La)TeX users.
- [TeXDoc](http://texdoc.net) - Online interface to the `texdoc` utility to browse LaTeX packages and documentation.
- [Dickimaw Books: LaTeX resources](http://www.dickimaw-books.com/latexresources.html) - Great overview of resources useful for LaTeX.
- [TUG: TeX showcase](http://www.tug.org/texshowcase/) - Website from the TUG that shows some examples of what LaTeX can do.
- [TeXample](http://www.texample.net) - Blog about LaTex, with a big collection of TikZ figures.
- [LaTeX cookbook](http://latex-cookbook.net) - Sibling of TeXample, contains quite a bit of example code.
- [12 Great resources for getting started with LaTeX](http://www.howtotex.com/general/12-great-resources-for-getting-started-with-latex/) - Nice overview of useful resources for beginners.
- [MartinThoma's LaTeX example](https://github.com/MartinThoma/LaTeX-examples/) - GitHub repository containing example LaTeX documents.
- [HowtoTeX LaTeX](http://latex.howtotex.com) - Start page with useful resources for LaTeX users.
- [MacTeX Wiki: TeX Extras](http://mactex-wiki.tug.org/wiki/index.php/TeX_Extras) - Overview of useful tools for LaTeX. Many of them are specific for Mac, but quite a bit are useful for other platforms as well.
- [LaTeX community](http://latex-community.org/index.php) - Forum and blog about LaTeX.

## Tutorials

- [The (Not So) Short Introduction to LaTeX2e](http://mirrors.ctan.org/info/lshort/english/lshort.pdf) - A very comprehensive introduction to LaTeX.

## Books

- [WikiBooks: LaTeX](https://en.wikibooks.org/wiki/LaTeX) - The LaTeX wikibook. Not really a paper book, but it is equally extensive.
- [The LaTeX Companion, F. Mittelbach (2004)](http://www.informit.com/store/latex-companion-9780201362992)
- [LaTeX Graphics Companion, M. Goossens (2007)](http://www.informit.com/store/latex-graphics-companion-9780321508928)

## Blogs

- [TeXblog](http://texblog.net) - Blog about LaTeX and everything related.

## Social media

- [LinkedIn: TeX/LaTeX User Group](https://www.linkedin.com/groups/1600297)
- [Twitter: @TeXtip](https://twitter.com/TeXtip) - Tips related to (La)TeX by [John D. Cook](http://www.johndcook.com/).
- [TeX.StackExchange](http://tex.stackexchange.com) - StackExchange TeX section.

---------------------------------------------------------------------------

<!-- Icons -->

# Meta Awesome-LaTeX

If you want to contribute, please do read our [CONTRIBUTING](CONTRIBUTING.md) guidelines.

## Legend

The icons indicating Mac, Linux and Windows compatibility show when a program is *only* available for those platforms. So absence of those icons means that the software is fully cross-platform.

|       Logo          | Description                                            |
|:-------------------:|:-------------------------------------------------------|
| ![Mac][mac]         | [Mac OS X](http://www.apple.com/osx/)                  |
| ![Linux][linux]     | [GNU/Linux](http://www.linux.org)                      |
| ![Windows][windows] | [Microsoft Windows](https://www.microsoft.com/windows) |
| ![FOSS][FOSS]      | [Free Open-Source Software](https://opensource.org)     |

---------------------------------------------------------------------------

All trademarks are property of their respective owners.

[mac]: https://cdn.rawgit.com/egeerardyn/awesome-LaTeX/700138fe725574e1741f148df6d1f77a8aa07eee/fig/apple.svg
[linux]: https://cdn.rawgit.com/egeerardyn/awesome-LaTeX/700138fe725574e1741f148df6d1f77a8aa07eee/fig/linux.svg
[windows]: https://cdn.rawgit.com/egeerardyn/awesome-LaTeX/700138fe725574e1741f148df6d1f77a8aa07eee/fig/windows.svg
[foss]: https://cdn.rawgit.com/egeerardyn/awesome-LaTeX/700138fe725574e1741f148df6d1f77a8aa07eee/fig/foss.svg
[awesome]:  https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg

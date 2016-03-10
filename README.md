
# Awesome LaTeX
This is a curated list of awesome stuff for the (La)TeX typesetting system. [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Contents
<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Awesome LaTeX](#awesome-latex)
  - [Contents](#contents)
- [Distributions](#distributions)
- [Engines](#engines)
  - [LaTeX formulas on the web](#latex-formulas-on-the-web)
- [Tools](#tools)
- [LaTeX-compatible tools](#latex-compatible-tools)
- [Editors](#editors)
  - [LaTeX-focussed](#latex-focussed)
  - [General purpose text editors](#general-purpose-text-editors)
  - [Online editors](#online-editors)
- [Bibliography tools](#bibliography-tools)
- [Packages](#packages)
  - [Tables](#tables)
  - [Graphics](#graphics)
    - [TikZ](#tikz)
    - [PSTricks](#pstricks)
- [Templates](#templates)
- [Resources](#resources)
- [Legend](#legend)

<!-- /TOC -->

# Distributions
- [MacTeX](https://tug.org/mactex/) - Most common LaTeX distribution for Mac OS X, basically TeXLive with some Mac-specific tools added.
- [MikTeX](http://miktex.org) - Most common LaTeX distribution for Windows (only).
- [TeX Live](http://www.tug.org/texlive/) - Most common LaTeX distribution for Unices and Linux, but also works on Windows. ![Linux][linux] ![Windows][windows]

# Engines
- [pdfTeX](http://www.tug.org/applications/pdftex/) - TeX compiler that produces PDF files immediately instead of DVI files (nowadays, this is the standard compiler for many users).
- [XeTeX](http://xetex.sourceforge.net) - TeX compiler that provides better unicode and font support than TeX/pdfTeX (i.e. you can use the  fonts of your operating system instead of only TeX fonts).
- [LuaTeX](http://www.luatex.org) - (La)TeX compiler that supports Lua code for scripting and has improved unicode and font support than standard TeX/pdfTeX.

## LaTeX formulas on the web
- [MathJaX](https://www.mathjax.org) - JavaScript engine to render mathematical formulas on the web. The outcome looks really slick.
- [mimeTeX](http://www.forkosh.com/mimetex.html) - mimeTeX is a rather old tool to render LaTeX formulas to PNG figures for your web site, without actually needing a LaTeX installation on your server.
- [mathTeX](http://www.forkosh.com/mathtex.html) - mathTeX is the successor of mimeTeX: it produces nicer-looking images but it requires LaTeX to be installed on your server.

# Tools
- Pandoc
- Online Math editors
- [LaTeXiT](http://www.chachatelier.fr/latexit/) - LaTeXit is an equation editor that makes it easy to drag-and-drop rendered equations into your documents on the Mac. ![Mac][mac]

# LaTeX-compatible tools
- [TikzEdt](http://www.tikzedt.org) - WYSIWYG and text-based editor for TikZ pictures. ![Windows][windows] ![Mac][mac] ![Linux][linux]: [GitHub repo](https://github.com/hchapman/tikzedt). Abandonded?
- KTikz
- [IPE](http://ipe.otfried.org)
- [TPx](http://tpx.sourceforge.net). ![Windows][windows] Abandoned?
- [http://www.geogebra.org/cms/](http://www.geogebra.org/cms/)
- [https://wiki.gnome.org/Apps/Dia](https://wiki.gnome.org/Apps/Dia)
- [https://github.com/fredokun/TikZ-Editor](https://github.com/fredokun/TikZ-Editor) - ![Mac][Mac] ![Linux][Linux]

# Editors
_Because editing LaTeX code with notepad is not awesome._

## LaTeX-focussed
- Kile
- TeXMaker
- WinEdt
- TeXniCenter
- LyX
- TeXshop
- BakomaTex

## General purpose text editors
- Atom
  - LaTeXTools

- Sublime Text
  - LaTeXing
  - LaTeXTools

- Emacs
  - AucTeX

- Vim

## Online editors
_Online editors that allow you to edit documents collaboratively._
- ShareLaTeX
- Overleaf
- Papeeria
- Authorea

# Bibliography tools
- JabRef
- Bibdesk
- 

# Packages
- [CTAN](http://ctan.org) - The Comprehensive TeX Archive Network is the place to look for useful packages and documentation.

## Tables
- Excel2LaTeX
- csv2latex
- [Tables Generator](http://www.tablesgenerator.com) - This website provides a graphical interface to input your table and produces properly-formatted code for LaTeX, Markdown, HTML, ...
- [pgfplotstable](https://www.ctan.org/pkg/pgfplotstable?lang=en) - This package dis­plays nu­mer­i­cal ta­bles rounded to de­sired pre­ci­sion in var­i­ous dis­play for­mats. It can even read CSV files to include directly in your LaTeX document.

## Graphics
### TikZ
- [TeXample](http://www.texample.net) - Blog about LaTex, with a big collection of TikZ figures.

### PSTricks
# Templates

- [LaTeX templates](http://www.latextemplates.com) - Collection of templates for papers, posters, resumés, theses, books, presentations, … for LaTeX.
- [HowtoTeX: templates](http://www.howtotex.com/category/templates/) - Different templates for LaTeX under a CC-NC-SA license.
-

# Symbols

- [Comprehensive LaTeX symbol list](http://www.ctan.org/tex-archive/info/symbols/comprehensive/) - A very extensive list of symbols for LaTeX. Available in [A4](http://mirrors.ctan.org/info/symbols/comprehensive/symbols-a4.pdf) and [letter](http://mirrors.ctan.org/info/symbols/comprehensive/symbols-letter.pdf) sizes.
- [Detexify](http://detexify.kirelabs.org/classify.html) - You draw the symbol and this site/app will tell you the LaTeX command.

# Resources

- [TUG](https://www.tug.org) - The TeX User Group is a way to get in touch with other (La)TeX users.
- [TeXDoc](http://texdoc.net) - Online interface to the `texdoc` utility to browse LaTeX packages and documentation.
- [http://www.dickimaw-books.com/latexresources.html](http://www.dickimaw-books.com/latexresources.html)
- [TUG: TeX showcase](http://www.tug.org/texshowcase/)
- [TeXample](http://www.texample.net) - Blog about LaTex, with a big collection of TikZ figures.

# Tutorials

- [The (Not So) Short Introduction to LaTeX2e](http://mirrors.ctan.org/info/lshort/english/lshort.pdf) - A very comprehensive introduction to LaTeX.

# Books

- [WikiBooks: LaTeX](https://en.wikibooks.org/wiki/LaTeX) - The LaTeX wikibook. Not really a paper book, but it is equally extensive.
- [The LaTeX Companion, F. Mittelbach (2004)](http://www.informit.com/store/latex-companion-9780201362992)
- [LaTeX Graphics Companion, M. Goossens (2007)](http://www.informit.com/store/latex-graphics-companion-9780321508928)

# Social media

- [Twitter: @TeXtip](https://twitter.com/TeXtip) - Tips related to (La)TeX by [John D. Cook](http://www.johndcook.com/).
<!-- Icons -->

# TODO
__Some random stuff that still needs to be categorized__

- http://www.howtotex.com/general/12-great-resources-for-getting-started-with-latex/
- http://latex.howtotex.com
- https://github.com/MartinThoma/LaTeX-examples/
- http://www.tug.org/texshowcase/
- http://mactex-wiki.tug.org/wiki/index.php/TeX_Extras
- chktex, diction, ...

# Legend

_What are all these weird icons all over the place?_

|        Logo         | Description                                            |
|:-------------------:|:-------------------------------------------------------|
|     ![Mac][mac]     | [Mac OS X](http://www.apple.com/osx/)                  |
|   ![Linux][linux]   | [GNU/Linux](http://www.linux.org)                      |
| ![Windows][windows] | [Microsoft Windows](https://www.microsoft.com/windows) |
|    ![FOSS][FOSS]    | [Free Open-Source Software](https://opensource.org)    |

All trademarks are property of their respective owners.

[mac]: https://rawgit.com/egeerardyn/awesome-LaTeX/master/fig/apple.svg
[linux]: https://rawgit.com/egeerardyn/awesome-LaTeX/master/fig/linux.svg
[windows]: https://rawgit.com/egeerardyn/awesome-LaTeX/master/fig/windows.svg
[foss]: https://rawgit.com/egeerardyn/awesome-LaTeX/awesome-LaTeX/master/fig/foss.svg

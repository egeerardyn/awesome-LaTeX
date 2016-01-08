# Awesome LaTeX
This is a curated list of awesome stuff for the (La)TeX typesetting system. [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Contents
<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:0 orderedList:0 -->

- [Awesome LaTeX](#awesome-latex)
  - [Contents](#contents)
  - [Legend](#legend)

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
- <!-- /TOC -->


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

## General purpose text editors
- Atom
  - LaTeX

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
# Packages
- [CTAN](http://ctan.org) - The Comprehensive TeX Archive Network is the place to look for useful packages and documentation.

## Tables
- Excel2LaTeX
- csv2latex
- [Tables Generator](http://www.tablesgenerator.com) - This website provides a graphical interface to input your table and produces properly-formatted code for LaTeX, Markdown, HTML, ...
- [pgfplotstable](https://www.ctan.org/pkg/pgfplotstable?lang=en) - This package dis­plays nu­mer­i­cal ta­bles rounded to de­sired pre­ci­sion in var­i­ous dis­play for­mats. It can even read CSV files to include directly in your LaTeX document.

## Graphics
### TikZ
### PSTricks
# Templates
# Resources
- [http://www.dickimaw-books.com/latexresources.html](http://www.dickimaw-books.com/latexresources.html)
- [http://www.tug.org/texshowcase/](http://www.tug.org/texshowcase/)
- [TeXample](http://www.texample.net) - Blog about LaTex, with a big collection of TikZ figures.
- <!-- Icons -->


# Legend

Logo                | Description
:-----------------: | :----------------
![Mac][mac]         | Mac OS X
![Linux][linux]     | GNU/Linux
![Windows][windows] | Microsoft Windows

All trademarks are property of their respective owners.

[mac]: https://cdn.rawgit.com/egeerardyn/awesome-LaTeX/master/fig/apple.svg
[linux]: https://cdn.rawgit.com/egeerardyn/awesome-LaTeX/master/fig/linux.svg
[windows]: https://cdn.rawgit.com/egeerardyn/awesome-LaTeX/master/fig/windows.svg
[foss]: https://cdn.rawgit.com/egeerardyn/awesome-LaTeX/master/fig/foss.svg

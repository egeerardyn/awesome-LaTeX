# Awesome LaTeX [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg?style=flat)](LICENSE.md)

![LaTeX Logo](fig/latex-logo.svg)

> This is a curated list of awesome stuff for the [(La)TeX typesetting system](https://www.latex-project.org/).

## Contents

- [Distributions](#distributions)
- [Docker Images](#docker-images)
- [Engines](#engines)
  - [LaTeX formulas on the web](#latex-formulas-on-the-web)
- [Editors](#editors)
  - [LaTeX-focused](#latex-focused)
  - [General purpose text editors](#general-purpose-text-editors)
  - [Online editors](#online-editors)
- [Language Servers](#language-servers)
- [Bibliography tools](#bibliography-tools)
- [Build Tools](#build-tools)
  - [GitHub Actions](#github-actions)
- [Misc. Tools](#misc-tools)
  - [Formatters](#formatters)
  - [Quality Check Tools](#quality-check-tools)
  - [Tools centered around equations](#tools-centered-around-equations)
- [LaTeX-compatible GUI tools](#latex-compatible-gui-tools)
- [Packages](#packages)
  - [References](#references)
  - [Tables](#tables)
  - [Graphics](#graphics)
  - [Source Code](#source-code)
  - [Typography](#typography)
  - [Presentations, Slides](#presentations-slides)
- [Templates](#templates)
- [Symbols](#symbols)
- [Resources](#resources)
- [Showcases](#showcases)
- [Tutorials](#tutorials)
- [Books](#books)
- [Blogs](#blogs)
- [Social media](#social-media)
- [Meta Awesome-LaTeX](#meta-awesome-latex)
- [Legend](#legend)

## Distributions

- [MacTeX](https://tug.org/mactex/) - Most common LaTeX distribution for macOS, basically TeXLive with some Mac-specific tools added. ![mac](fig/apple.svg)
- [TeX Live](https://www.tug.org/texlive/) - Most common LaTeX distribution for Unix-like operating systems, including GNU/Linux. Also works on Windows. ![linux](fig/linux.svg) ![windows](fig/windows.svg)
- [MikTeX](https://miktex.org) - Most common LaTeX distribution for Windows, but also available for Mac, Linux or as Docker image. ![linux](fig/linux.svg) ![windows](fig/windows.svg) ![mac](fig/apple.svg) ![foss](fig/foss.svg)

## Docker Images

When one aims for a ready-to-run LaTeX environment without installing, Docker images might be the choice.

- [reitzig/texlive-docker](https://github.com/reitzig/texlive-docker) - Minimal TeXLive system with package installation possibility.
- [Island of TeX/texlive](https://gitlab.com/islandoftex/images/texlive) - Debian-based full TeXLive system.
- [dante-ev/docker-texlive](https://github.com/dante-ev/docker-texlive) - Debian-based full TeXLive system with additions with Pandoc, Perl, and Python pre-installed.

## Engines

- [pdfTeX](https://www.tug.org/applications/pdftex/) - TeX compiler that produces PDF files immediately instead of DVI files (nowadays, this is the standard compiler for many users). ![foss](fig/foss.svg)
- [XeTeX](https://xetex.sourceforge.net) - TeX compiler that provides better unicode and font support than TeX/pdfTeX (i.e. you can use the fonts of your operating system instead of only TeX fonts). ![foss](fig/foss.svg)
- [LuaTeX](https://www.luatex.org) - (La)TeX compiler that supports Lua code for scripting and has improved unicode and font support than standard TeX/pdfTeX. ![foss](fig/foss.svg)
- [tectonic](https://tectonic-typesetting.GitHub.io/en-US/) - Modern, self contained (La)TeX compiler powered by XeTeX and TeXLive. ![foss](fig/foss.svg)

### LaTeX formulas on the web

- [Auto-LaTeX Equations with Google Docs](https://sites.google.com/site/autolatexequations) - Render high-quality math equations directly in Google Docs.
- [MathJaX](https://www.mathjax.org) - JavaScript engine to render mathematical formulas on the web. The outcome looks really slick. ![foss](fig/foss.svg)
- [mimeTeX](https://ctan.org/pkg/mimetex) - Rather old tool to render LaTeX formulas to PNG figures for your web site, without actually needing a LaTeX installation on your server. ![foss](fig/foss.svg)
- [mathTeX](https://ctan.org/pkg/mathtex) - Successor of mimeTeX: it produces nicer-looking images but it requires LaTeX to be installed on your server. ![foss](fig/foss.svg)
- [KaTeX](https://khan.GitHub.io/KaTeX/) - Math rendering library made by Khan Academy focusing on fast load times. All output is processed as plain HTML instead of fixed images. ![foss](fig/foss.svg)
- [Franklin.jl](https://franklinjl.org/) - Static site generator with KaTeX support, code evaluation, LaTeX-like commands and optional pre-rendering, in Julia. ![foss](fig/foss.svg)
- [xhub](https://github.com/nschloe/xhub) - Browser extension that lets you use LaTeX in GitHub pages. ![foss](fig/foss.svg)

## Editors

Because editing LaTeX code with notepad is not awesome.
There are many editors out there, below are the most awesome editors.
A complete list of LaTeX editors is collected at TeX.StackExchange as [big list of LaTeX Editors/IDEs](https://tex.stackexchange.com/q/339/9075).

- [List of popular LaTeX editors](https://tex.stackexchange.com/questions/339/latex-editors-ides) - Community-maintained list of popular LaTeX editors including a screenshot and a short description.

### LaTeX-focused

Some of the most awesome editor for LaTeX do just that: edit LaTeX.

- [Kile](https://kile.sourceforge.io) - Great LaTeX editor originally from the Linux/KDE community. It runs fine on Windows and macOS as well. ![foss](fig/foss.svg)
- [TeXMaker](https://www.xm1math.net/texmaker/) - Pretty good alternative to Kile.
- [TeXStudio](https://www.texstudio.org) - Cross-platform LaTeX editor that stems from TeXMaker.
- [WinEdt](https://www.winedt.com) - The LaTeX editor many people swear by. Only for ![windows](fig/windows.svg).
- [TeXnicCenter](https://www.texniccenter.org) - Quite old but free and decent editor for LaTeX. ![windows](fig/windows.svg)
- [LyX](https://www.lyx.org) - Cross-platform WYSIWYM editor that uses LaTeX behind the scenes to render documents. ![foss](fig/foss.svg)
- [TeXShop](https://pages.uoregon.edu/koch/texshop/) - No-nonsense editor for LaTeX documents which is included in MacTeX. ![mac](fig/apple.svg)
- [TeXWorks](https://www.tug.org/texworks/) - No-nonsense editor for LaTeX code, modeled after TeXShop, but this one is cross-platform. ![foss](fig/foss.svg)
- [BakomaTex](https://bakoma-tex.com) - Commercial LaTeX editor that allows to edit your document both using its source code and WYSIWYG.
- [Texifier](https://www.texifier.com/) - Commercial LaTeX editor for macOS and iOS, with excellent features (document overview, synchronised PDF display, autocompletion, sync across devices, etc.) that never get in the way of writing. ![mac](fig/apple.svg)
- [TeX64](https://tex64.com) - Native macOS LaTeX editor with AI-powered error fixing, equation OCR, live PDF preview, and structured math editing. ![mac](fig/apple.svg)
- [Oleafly](https://github.com/Oleafly/Oleafly) - Free, open-source desktop editor for LaTeX, Typst, and Markdown with live PDF preview, SyncTeX, bundled engines, and Git-native projects. ![foss](fig/foss.svg)
- [LaTeX Editor](https://github.com/s-balli/latex-editor) - Single-executable desktop editor with live PDF preview, two-way SyncTeX, LaTeX-aware spell checking, and one-key project snapshots written as a standard git repository. Needs a separate TeX distribution. ![windows](fig/windows.svg) ![linux](fig/linux.svg) ![foss](fig/foss.svg)
- [ModernTex](https://purplelink.llc/moderntex/) - Native macOS LaTeX editor for academic writing, with synced source and PDF, plain-language error messages, submission-readiness checks, a visual TikZ designer and a table editor. Free 7-day trial, then a one-time $19.99. ![mac](fig/apple.svg)

### General purpose text editors

These editors are no one-trick ponies: sure, they edit LaTeX, but they can do a lot more!

- [Atom](https://atom.io) - Hackable text editor by GitHub, discontinued in 2022. [![Atom][awesome]](https://github.com/mehcode/awesome-atom) ![foss](fig/foss.svg)
  - [LaTeXTools](https://atom.io/packages/latextools) - Atom port of the Sublime Text package of the same name. ![foss](fig/foss.svg)

- [Sublime Text](https://www.sublimetext.com) - Fast, cross-platform proprietary text editor. [![Sublime Text][awesome]](https://github.com/dreikanter/sublime-bookmarks)
  - [LaTeXing](https://github.com/LaTeXing/LaTeXing) - Free plug-in to edit LaTeX. ![foss](fig/foss.svg)
  - [LaTeXTools](https://github.com/SublimeText/LaTeXTools) - Free LaTeX plugin for Sublime Text. ![foss](fig/foss.svg)

- [Emacs](https://www.gnu.org/software/emacs/) - Extensible, customizable free text editor. [![Emacs][awesome]](https://github.com/emacs-tw/awesome-emacs) ![foss](fig/foss.svg)
  - [AucTeX](https://www.gnu.org/software/auctex/) - Emacs plugin for LaTeX that also shows a preview of equations and figures. ![foss](fig/foss.svg)
  - [RefTeX](https://www.gnu.org/software/auctex/reftex) - Emacs plugin for LaTeX that adds support for labels, references, and citations. ![foss](fig/foss.svg)

- [Vim](https://www.vim.org) - Highly configurable modal text editor. [![Vim][awesome]](https://github.com/mhinz/vim-galore) ![foss](fig/foss.svg)
  - [Vim-LaTeX](https://vim-latex.sourceforge.net) - Comprehensive set of tools to view, edit, and compile LaTeX documents within Vim. ![foss](fig/foss.svg)
  - [LaTeX Live Preview](https://github.com/xuhdev/vim-latex-live-preview) - Instantly previews your LaTeX document. ![foss](fig/foss.svg)
  - [vimtex](https://github.com/lervag/vimtex) - Modern Vim plugin for editing LaTeX files. Has a variety of features including live preview and forward search. ![foss](fig/foss.svg)

- [IntelliJ](https://www.jetbrains.com/idea/) - Java IDE by JetBrains that can be extended with plugins.
  - [TeXiFy-IDEA](https://github.com/Hannah-Sten/TeXiFy-IDEA) - Free LaTeX plugin for IntelliJ IDEA. ![foss](fig/foss.svg)

- [VS Code](https://code.visualstudio.com/) - Free, extensible code editor by Microsoft. [![VS Code][awesome]](https://github.com/viatsko/awesome-vscode) ![foss](fig/foss.svg)
  - [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop) - LaTeX extension for Visual Studio Code. ![foss](fig/foss.svg)
  - [a-nau/latex-devcontainer](https://github.com/a-nau/latex-devcontainer) - Devcontainer setup for easy LaTeX usage without local installation. ![foss](fig/foss.svg)

### Online editors

Online editors that allow you to edit documents collaboratively.

- [List of popular online LaTeX editors](https://tex.stackexchange.com/questions/3/compiling-documents-online/1654#1654) - Community-maintained list of popular online LaTeX editor including equation editors.
- [Authorea](https://www.authorea.com) - Online editor with built-in Git support and bibliography tools.
- [OpenAI Prism](https://prism.openai.com) - Online editor with realtime collaboration features.
- [Modern LaTeX Editor](https://github.com/InMDev/Modern-LaTeX-Editor) - Online editor, no-signup hybrid code editor + visual editor that mixes Notion/Google Docs/Microsoft Word-like editing with raw LaTeX code blocks.
- [Octree](https://www.useoctree.com) - Online editor with AI writing assistance.
- [Androma TeX Editor](https://androma.org) - Collaborative LaTeX editor integrated into a mathematics wiki, with issue tracking, pull requests, and WASM-based compilation.
- [Overleaf](https://www.overleaf.com) - Online editor, also with a WYSIWYM editor and Git support. Also available as [Overleaf Community Edition](https://github.com/overleaf/overleaf) (self-hosted, AGPL licensed). ![foss](fig/foss.svg)
  - [olcli](https://github.com/aloth/olcli) - Command-line interface for Overleaf to sync, manage, and compile projects from the terminal. ![foss](fig/foss.svg)
  - [overleaf-comments-export](https://github.com/Mangluu/overleaf-comments-export) - Exports comment threads, replies and tracked changes to Markdown and JSON, and annotates the compiled PDF with highlights on the commented text. ![foss](fig/foss.svg)
- [SciTeX Cloud](https://github.com/scitex-ai/scitex-hub) - Self-hostable online editor with AI assistant integration, figure/table/citation management, real-time collaboration, and an MCP server (29 tools). ![foss](fig/foss.svg)
- [WebLaTeX](https://github.com/sanjib-sen/weblatex) - Web-based VS Code with Git Integration + Copilot + Grammar & Spell Checker + Live Collaboration Support based on GitHub Codespace and Dev container.
- [Papeeria](https://papeeria.com) - Online editor with built-in Git support.
- [JaxEdit](https://zohooo.GitHub.io/jaxedit/) - Online LaTeX editor with Live Preview and nice presentation mode.
- [Vexlio](https://vexlio.com/) - Online diagram editor with built-in LaTeX equation support including live preview and easy exports.
- [TeXbrain](https://tex.swimmingbrain.dev) - Free, open-source browser-based LaTeX editor with in-browser compilation, live PDF preview and Git integration. No account or install required. ![foss](fig/foss.svg)
- [LetX](https://letx.app) - Online editor with real-time multi-author collaboration (CRDT), bidirectional SyncTeX, and 1000+ journal/thesis templates.
- [Sarmate.net](https://www.sarmate.net) - Online editor with 5 built-in WYSIWYG helpers (TikZ figures, probability trees, sign tables, color boxes, LaTeX tables) that auto-generate clean LaTeX code. Cloud compilation, real-time collaboration, free tier.
- [Aldine](https://aldine.dev) - Self-hosted online editor with real-time collaboration in which every project is a git repository, with branches in the editor and push/pull to GitHub, GitLab and Gitea. ![foss]

## Language Servers

Language servers bring IDE features (completion, diagnostics, navigation, and more) to any editor that speaks the [Language Server Protocol](https://microsoft.github.io/language-server-protocol/), such as Neovim, VS Code, Emacs, and Helix.

<!--lint ignore double-link-->
- [TexLab](https://github.com/latex-lsp/texlab) - Language server for LaTeX and BibTeX with completion, definitions, references, rename, formatting, and forward search. ![foss](fig/foss.svg)
- [Badness](https://github.com/jolars/badness) - Language server, formatter, and linter for LaTeX built on a lossless, error-tolerant syntax tree in the style of rust-analyzer. ![foss](fig/foss.svg)

## Bibliography tools

- [JabRef](https://www.jabref.org) - Very powerful cross-platform (Java) bibtex editor. ![mac](fig/apple.svg) ![windows](fig/windows.svg) ![linux](fig/linux.svg) ![foss](fig/foss.svg)
- [Papis](https://github.com/papis/papis) - Extremely customizable,
  powerful and simple cross-platform (Python) library manager. It has a very
  complete Command-Line-Interface, several GUIs and scripting capability.
  ![linux](fig/linux.svg) ![mac](fig/apple.svg) ![foss](fig/foss.svg)
- [Bibdesk](https://bibdesk.sourceforge.net) - Great bibliography editor for ![mac](fig/apple.svg).
- [Zotero](https://www.zotero.org) - Reference manager for your browser that also exports to bibtex and integrates with many LaTeX editors. ![mac](fig/apple.svg) ![windows](fig/windows.svg) ![linux](fig/linux.svg) ![foss](fig/foss.svg)
- [Mendeley](https://www.mendeley.com) - Both an app and cloud client to manage your references and PDFs. Can sync out to a bibtex file for your LaTeX workflow. ![mac](fig/apple.svg) ![windows](fig/windows.svg) ![linux](fig/linux.svg)
- [betterbib](https://github.com/texworld/betterbib) - Command-line utility for improving your BibTeX files. Fetches information from online sources. ![mac](fig/apple.svg) ![windows](fig/windows.svg) ![linux](fig/linux.svg) ![foss](fig/foss.svg)
- [OneCite](https://github.com/HzaCode/OneCite) - Universal citation management and academic reference toolkit that converts messy references into perfectly formatted citations. Supports DOI, arXiv ID, titles, and more, with output in BibTeX, APA, and MLA formats. ![mac](fig/apple.svg) ![windows](fig/windows.svg) ![linux](fig/linux.svg) ![foss](fig/foss.svg)
- [CrossRef Local](https://github.com/scitex-ai/crossref-local) - Local CrossRef database (167M papers) with full-text search, impact factor data, Python API for bibliography enrichment, and an MCP server (15 tools). ![foss](fig/foss.svg)
- [OpenAlex Local](https://github.com/scitex-ai/openalex-local) - Local OpenAlex database (284M scholarly works) with abstracts and semantic search for literature discovery, and an MCP server. ![foss](fig/foss.svg)
- [latexci BibTeX tools](https://latexci.com/tools/bibtex) - Browser-based .bib cleaner (removes duplicates, normalizes author names, escapes special characters) plus DOI, arXiv, PubMed and ISBN to BibTeX lookups, with no install and no account. ![foss](fig/foss.svg)

## Build Tools

Compiling LaTeX documents can be tedious, build tools help you to manage the compilation process.

- [Arara](https://www.ctan.org/pkg/arara) ([GitHub repo](https://github.com/islandoftex/arara)) - Simple tool that allows you to specify which tools to call inside your document and it can be extended quite easily. ![foss](fig/foss.svg)
- [latexmk](https://www.ctan.org/pkg/latexmk) - Build tool that is the commonly used by many LaTeX editors (LaTeXing, TeXShop, etc.) to build your LaTeX files. ![foss](fig/foss.svg)

### GitHub Actions

- [xu-cheng/latex-action](https://github.com/xu-cheng/latex-action) - GitHub Action to compile LaTeX documents.
- [dante-ev/latex-action](https://github.com/dante-ev/latex-action) - DANTE e.V.'s GitHub action to compile LaTeX documents. Offers a full TeXLive and pre-installed Perl and Python.

## Misc. Tools

- [CaTeX](https://github.com/Alexis-benoist/CaTeX) - Concatenates LaTeX documents with attention for properly merging the preamble.
- [Pandoc](https://pandoc.org) - This program converts almost any document format (LaTeX, DOC, markdown, etc.) to almost any other format. A great tool to aid workflows where multiple formats are used. ![foss](fig/foss.svg)
- [SciTeX Writer](https://github.com/scitex-ai/scitex-writer) - Manuscript compilation system with templates for manuscripts, revisions, and supplementary materials, plus figure, table, and citation handling, and an MCP server (38 tools). ![foss](fig/foss.svg)

### Formatters

Formatters keep the layout of your LaTeX source consistent, so that you can focus on the content.

<!--lint ignore double-link-->
- [latexindent](https://ctan.org/pkg/latexindent) - Perl script that indents and reformats LaTeX documents, highly configurable through YAML settings and shipped with the major TeX distributions. ![foss](fig/foss.svg)
- [tex-fmt](https://github.com/WGUNDERWOOD/tex-fmt) - Extremely fast LaTeX formatter written in Rust, with sensible defaults and minimal configuration. ![foss](fig/foss.svg)
- [Badness](https://github.com/jolars/badness) - Deterministic, rule-based, and idempotent LaTeX formatter written in Rust (also a linter and language server). ![foss](fig/foss.svg)

### Quality Check Tools

<!--lint ignore double-link-->
- [ChkTeX](https://www.nongnu.org/chktex/) - Linter / code checker for LaTeX documents. ![foss](fig/foss.svg)
- [blacktex](https://github.com/texworld/blacktex) - Command-line tool that replaces commonly occurring LaTeX anti-patterns and cleans up your files. ![windows](fig/windows.svg) ![linux](fig/linux.svg) ![mac](fig/apple.svg) ![foss](fig/foss.svg)
- [TeXtidote](https://github.com/sylvainhalle/textidote) - A cross-platform (Java) spelling, grammar and style checker for LaTeX documents. ![windows](fig/windows.svg) ![linux](fig/linux.svg) ![mac](fig/apple.svg) ![foss](fig/foss.svg)
- [Badness](https://github.com/jolars/badness) - Error-tolerant LaTeX linter with rich diagnostics and source snippets (also a formatter and language server). ![foss](fig/foss.svg)
- [latex2arxiv](https://github.com/YuZh98/latex2arxiv) - CLI tool that prepares a LaTeX project for arXiv submission: prunes unreachable files, strips draft markup, validates the bibliography, and catches desk-rejection errors before upload. Also available as a GitHub Action and MCP server for AI agents. ![windows](fig/windows.svg) ![linux](fig/linux.svg) ![mac](fig/apple.svg) ![foss](fig/foss.svg)

### Tools centered around equations

- [Codecogs Eqn Editor](https://editor.codecogs.com/) - Online LaTeX equation editor that allows you to produce figures containing an equation.
- [EqualX](https://equalx.sourceforge.io/) - Graphical LaTeX formula editor. ![windows](fig/windows.svg) ![linux](fig/linux.svg) ![foss](fig/foss.svg)
- [KLaTeXFormula](https://klatexformula.sourceforge.io) - Cross-platform alternative for LaTeXit. ![foss](fig/foss.svg)
- [Laeqed](https://www.thrysoee.dk/laeqed/) - Crossplatform LaTeX formula to PNG convertor. ![windows](fig/windows.svg) ![linux](fig/linux.svg) ![mac](fig/apple.svg) ![foss](fig/foss.svg)
- [LaTeXEqEdit](https://latexeqedit.sourceforge.net/) - LaTeX formula editor for Windows. ![windows](fig/windows.svg) ![foss](fig/foss.svg)
- [LaTeXiT](https://www.chachatelier.fr/latexit/) - Equation editor that makes it easy to drag-and-drop rendered equations (as PDF, PNG, etc.) into your non-LaTeX documents on the Mac. ![mac](fig/apple.svg)
- [LaTeX to Image](https://thomasahle.com/latex2png/) - Convert LaTeX to PNG, JPEG, or SVG images. Big symbols menu and easy drag-and-drop equations.
- [pix2tex](https://lukas-blecher.github.io/LaTeX-OCR/) - LaTeX OCR: converts images of equations into LaTeX code. ![windows](fig/windows.svg) ![linux](fig/linux.svg) ![mac](fig/apple.svg) ![foss](fig/foss.svg)
- [Image to LaTeX](https://www.underleaf.ai/tools/image-to-latex) - AI-powered converter that transforms images of handwritten notes, equations, or tables into clean LaTeX code.
- [IguanaTex](https://github.com/Jonathan-LeRoux/IguanaTex) - PowerPoint add-in that inserts LaTeX equations typeset by your local TeX distribution and keeps the source with each shape, so you can edit and re-typeset it later. ![windows] ![mac] ![foss]
- [MathPoint](https://tex64.com/mathpoint) - PowerPoint and Word add-in that inserts LaTeX equations, TikZ/pgfplots figures and tables typeset with LuaLaTeX on a server, so no local TeX installation is needed (also in PowerPoint for the web). Type LaTeX in its task pane or drive it from Claude or ChatGPT over MCP; the source stays with each shape for re-typesetting.

## LaTeX-compatible GUI tools

- [TikzEdt](http://www.tikzedt.org) (also: [GitHub repo](https://github.com/hchapman/tikzedt)) - WYSIWYG and text-based editor for TikZ pictures. ![foss](fig/foss.svg)
- [TikZ-Editor](https://github.com/fredokun/TikZ-Editor) - Live-previewing editor for TikZ figures. ![mac](fig/apple.svg) ![linux](fig/linux.svg) ![foss](fig/foss.svg)
- [IPE](https://ipe.otfried.org) - Drawing tool that integrates well with LaTeX commands and documents. ![foss](fig/foss.svg)
- [GeoGebra](https://www.geogebra.org/) - Cross-platform geometry tool with output to TikZ. ![foss](fig/foss.svg)
- [Dia](https://wiki.gnome.org/Apps/Dia) - Cross-platform diagramming tool that can export to PSTricks and MetaPost code. ![foss](fig/foss.svg)
- [TikZiT](https://tikzit.GitHub.io) - GUI tool for creating graphs and string diagrams using PGF/TikZ. ![windows](fig/windows.svg) ![linux](fig/linux.svg) ![mac](fig/apple.svg) ![foss](fig/foss.svg)
- [LaTeXDraw](https://latexdraw.sourceforge.net/) - Vector-based drawing tool having LaTeX as first-class citizen. ![windows](fig/windows.svg) ![linux](fig/linux.svg) ![mac](fig/apple.svg) ![foss](fig/foss.svg)
- [RustFig](https://fabianhassler.github.io/rustfig/) - xfig rebuilt for Windows, macOS, Linux and the browser (no X server): LaTeX text typeset on the canvas, and every fig2dev export built in (TikZ, PSTricks, pict2e, pstex/pdftex, PDF, EPS, SVG). Reads and writes xfig's .fig files. ![windows](fig/windows.svg) ![linux](fig/linux.svg) ![mac](fig/apple.svg) ![foss](fig/foss.svg)

## Packages

- [CTAN](https://www.ctan.org) - The Comprehensive TeX Archive Network is the place to look for useful packages and documentation.

### References

- [Cross-reference packages explained](https://tex.stackexchange.com/a/36312/9075) - Elaboration on cross-reference packages (cleveref, varioref, theoremref, nameref, etc.): Which to use, which conflict?

### Tables

- [Excel2LaTeX](https://www.ctan.org/pkg/excel2latex?lang=en) - Excel (2010 and older) macros to produce LaTeX `tabular` code. ![windows](fig/windows.svg) ![mac](fig/apple.svg)
- [csv2latex](https://freshmeat.sourceforge.net/projects/csv2latex) - Converts CSV files from your favorite programs to LaTeX `tabular`s. ![linux](fig/linux.svg) ![mac](fig/apple.svg)
- [Tables Generator](https://www.tablesgenerator.com) - This website provides a graphical interface to input your table and produces properly-formatted code for LaTeX, Markdown, HTML, etc.
- [pgfplotstable](https://www.ctan.org/pkg/pgfplotstable?lang=en) - This package displays numerical tables rounded to desired precision in various display formats. It can even read CSV files to include directly in your LaTeX document.

### Graphics

#### PSTricks

PSTricks is a great library to draw figures for inclusion in PostScript/DVI files.

#### TikZ

TikZ is an awesome package with many plugins that allow you to create figures from within your LaTeX documents.
Typically, it is easier to get to work with `pdflatex` than PSTricks is.

- [TeXample](https://texample.net) - Blog about LaTeX, with a big collection of TikZ figures.
- [pgfplots](https://pgfplots.sourceforge.net) - Truly awesome plotting library on top of and in the style of TikZ/pgf. This library can load in CSV data files, perform some calculations and create beautiful plots.
- [A very minimal introduction to TikZ (PDF)](https://cremeronline.com/LaTeX/minimaltikz.pdf) - Short introductory document to the world of TikZ, written by Jacques Crémer.
- [PetarV-/TikZ](https://github.com/PetarV-/TikZ) - Collection of publication-ready PGF/TikZ figures by Petar Veličković.
- [matlab2tikz](https://github.com/matlab2tikz/matlab2tikz) - Convert your MATLAB plots to PGFPlots/TikZ. ![windows](fig/windows.svg) ![linux](fig/linux.svg) ![mac](fig/apple.svg) ![foss](fig/foss.svg)
- [tikzplotlib](https://github.com/nschloe/tikzplotlib) - Convert your Matplotlib plots to PGFPlots/TikZ. ![windows](fig/windows.svg) ![linux](fig/linux.svg) ![mac](fig/apple.svg) ![foss](fig/foss.svg)
- [TikZBlog](https://latexdraw.com) - Step-by-Step Tutorials about How to Draw Illustrations in LaTeX.
- [OpenTikZ](https://github.com/opentikz/opentikz) - Community library of copyable TikZ icons and editable, parametric templates for academic conceptual diagrams (system/architecture, pipelines, flowcharts); CC0 content, with a Claude Code skill to edit figures on request. ![foss](fig/foss.svg)

### Source Code

- [minted](https://www.ctan.org/pkg/minted) - The minted package uses [pygments](https://pygments.org/) to generate the listings. In this way, LaTeX is able to format more than 300 programming and markup languages and other text formats.

### Typography

- [microtype](https://ctan.org/pkg/microtype) - This package improves the appearance of your documents by enabling margin kerning and font expansion.

### Presentations, Slides

- [nics](https://nics.nilcons.com/) - An opinionated alternative to Beamer, that we created with the hopes to make common tasks very easy and beautifully rendered by default. Has awesome documentation and a detailed cheatsheet to help you getting started.

## Templates

- [LaTeX templates](https://latextemplates.com) - Collection of templates for papers, posters, resumés, theses, books, presentations, … for LaTeX.
- [Ultimate Beamer Theme List](https://github.com/martinbjeldbak/ultimate-beamer-theme-list) - Links to various beamer themes along with PDF previews.
- [LaTeX Beamer Theme Overview](https://github.com/UweZiegenhagen/LaTeX-Beamer-Theme-Overview/blob/main/OVERVIEW.md) - Visual overview of beamer themes included in TeXLive.
- [TeXtured](https://github.com/jdujava/TeXtured) - A typographically elegant, clean, and structured LaTeX template (primarily intended for theses).

## Symbols

- [Comprehensive LaTeX symbol list](https://www.ctan.org/tex-archive/info/symbols/comprehensive/) - Very extensive list of symbols for LaTeX. Available in [A4](https://mirrors.ctan.org/info/symbols/comprehensive/symbols-a4.pdf) and [letter](https://mirrors.ctan.org/info/symbols/comprehensive/symbols-letter.pdf) sizes.
- [Detexify](https://detexify.kirelabs.org/classify.html) - You draw the symbol and this site/app will tell you the LaTeX command.

## Resources

- [TUG](https://www.tug.org) - The TeX User Group is a way to get in touch with other (La)TeX users.
- [Dickimaw Books: LaTeX resources](https://www.dickimaw-books.com/latexresources.html) - Great overview of resources useful for LaTeX.
- [LaTeX cookbook](https://latex-cookbook.net) - Sibling of TeXample, contains quite a bit of example code.
- [Visual FAQ](https://ctan.org/pkg/visualfaq) - Typesetting issues and a link to appropriate TeX FAQ answers.
- [MartinThoma's LaTeX example](https://github.com/MartinThoma/LaTeX-examples/) - GitHub repository containing example LaTeX documents.
- [LaTeX community](https://latex.org/forum) - Forum about LaTeX.
- German: [Neue TeX FAQ](https://texfragen.de) - Modern and updated LaTeX FAQ in German.
- [BibTeX Style Examples](https://kjt.stir.ac.uk/software/latex/showbst.html) - Example output of common BibTeX styles (BST files).
- [TeXnique](https://texnique.xyz) - A LaTeX Typesetting Game.

## Showcases

- [Showcase of beautiful typography done in TeX & friends](https://tex.stackexchange.com/questions/1319/showcase-of-beautiful-typography-done-in-tex-friends) - Set of examples demonstrating the power of LaTeX.
- [Showcase of beautiful invitations in TeX](https://tex.stackexchange.com/q/281415/9075) - Showcase of invitations typeset using LaTeX.
- [Showcase of "programming your document" paradigm](https://tex.stackexchange.com/q/219774/9075) - Collection of LaTeX documents demonstrating how LaTeX can be used like a programming language.
- [TUG: TeX showcase](https://www.tug.org/texshowcase/) - Website from the TUG that shows some examples of what LaTeX can do.
- [Awesome LaTeX drawing](https://github.com/xinychen/awesome-latex-drawing) - Curated list of academic drawing examples for using LaTeX.

## Tutorials

- [LearnLaTeX.org](https://www.learnlatex.org/) - Browser-based LaTeX tutorial.
- [The (Not So) Short Introduction to LaTeX2e](https://mirrors.ctan.org/info/lshort/english/lshort.pdf) - Very comprehensive introduction to LaTeX.
- [Begin LaTeX in minutes](https://github.com/luong-komorebi/Begin-Latex-in-minutes) - Brief intro to LaTeX for beginners that helps you use LaTeX with ease.
- [Getting to Grips with LaTeX](https://www.andy-roberts.net/writing/latex) - Complete guide going through the majority of things you need to know about LaTeX.
- [LaTeX introductions in languages other than English](https://tex.stackexchange.com/questions/84384/latex-introductions-in-languages-other-than-english/84385) - Collection of introductions in many languages.

## Books

- [Wikibooks: LaTeX](https://en.wikibooks.org/wiki/LaTeX) - The LaTeX wikibook. Not really a paper book, but it is equally extensive.
- [The LaTeX Companion, F. Mittelbach (2004)](https://www.informit.com/store/latex-companion-9780201362992)
- [LaTeX Graphics Companion, M. Goossens (2007)](https://www.informit.com/store/latex-graphics-companion-9780321508928)
- [TeX by Topic (2007)](https://ctan.org/pkg/texbytopic)
- [TeX for the Impatient (2020)](https://ctan.org/pkg/impatient)
- [Formatting Information (2020)](https://latex.silmaril.ie/formattinginformation/) - This is the HTML5-based online version of the book *Formatting Information - An introduction to typesetting with LATEX*. It has been continuously updated since the early 2000s.

## Blogs

- [TeXblog](https://texblog.net) - Blog about LaTeX and everything related.
- [texblog.org](https://texblog.org) - Blog on LaTeX and related topics (tutorials, packages, code snippets, etc.).
- [TeX Hour](https://texhour.github.io/) - A weekly video meeting.

## Social media

- [LinkedIn: TeX/LaTeX User Group](https://www.linkedin.com/groups/1600297)
- [Twitter: @TeXtip](https://twitter.com/TeXtip) - Tips related to (La)TeX by [John D. Cook](https://www.johndcook.com/).
- [TeX.StackExchange](https://tex.stackexchange.com) - StackExchange TeX section.
- [TopAnswers TeX](https://topanswers.xyz/tex) - Free and open-source Q&A site for TeX and friends.

---

<!-- Icons -->

## Meta Awesome-LaTeX

If you want to contribute, please do read our [CONTRIBUTING](CONTRIBUTING.md) guidelines.

## Legend

The icons indicating Mac, Linux and Windows compatibility show when a program is *only* available for those platforms. So absence of those icons means that the software is fully cross-platform.

|            Logo             | Description                                            |
| :-------------------------: | :----------------------------------------------------- |
|    ![mac](fig/apple.svg)    | [macOS](https://www.apple.com/macos)                   |
|   ![linux](fig/linux.svg)   | [GNU/Linux](https://www.gnu.org)                       |
| ![windows](fig/windows.svg) | [Microsoft Windows](https://www.microsoft.com/windows) |
|    ![foss](fig/foss.svg)    | [Free Open-Source Software](https://opensource.org)    |

---

All trademarks are property of their respective owners.

[awesome]: https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg

# Awesome LaTeX [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of LaTeX editors, distributions, tools, libraries, templates and resources for researchers, students and anyone who writes with TeX.

Star it if it saves you time. PRs welcome, see [Contributing](#contributing).

## Contents

- [Online Editors](#online-editors)
- [AI Writing Tools](#ai-writing-tools)
- [Offline Editors](#offline-editors)
- [Editor Plugins and Language Servers](#editor-plugins-and-language-servers)
- [Distributions](#distributions)
- [Engines](#engines)
- [Build Tools](#build-tools)
- [PDF Viewers with SyncTeX](#pdf-viewers-with-synctex)
- [Packages](#packages)
- [Bibliography and Citations](#bibliography-and-citations)
- [Figures and Diagrams](#figures-and-diagrams)
- [Tables](#tables)
- [Math, Symbols and OCR](#math-symbols-and-ocr)
- [Conversion](#conversion)
- [Linting, Formatting and Diffing](#linting-formatting-and-diffing)
- [Programmatic LaTeX](#programmatic-latex)
- [LaTeX in the Browser](#latex-in-the-browser)
- [CI, Docker and Self-Hosting](#ci-docker-and-self-hosting)
- [Templates](#templates)
- [Fonts](#fonts)
- [Learning Resources](#learning-resources)
- [Community](#community)
- [Alternatives to LaTeX](#alternatives-to-latex)
- [Contributing](#contributing)

## Online Editors

- [Overleaf](https://www.overleaf.com) - Collaborative cloud LaTeX editor, the de facto standard.
- [Bibby AI](https://trybibby.com) - LaTeX-native AI research writing platform.
- [Prism](https://prism.openai.com) - OpenAI's free cloud LaTeX workspace with built-in ChatGPT, based on Crixet.
- [Papeeria](https://papeeria.com) - Online LaTeX editor with Git integration.
- [CoCalc](https://cocalc.com) - Collaborative computing platform with a LaTeX editor, Jupyter and SageMath.
- [Authorea](https://www.authorea.com) - Collaborative research document platform with LaTeX support.
- [TeXlive.net](https://texlive.net) - Run small LaTeX snippets online with a full TeX Live.

## AI Writing Tools

- [Bibby AI](https://trybibby.com) - AI writing, editing and citation help inside a LaTeX editor.
- [Prism](https://prism.openai.com) - GPT-integrated LaTeX workspace with literature search and image-to-LaTeX.
- [Writefull](https://www.writefull.com) - Language feedback for academic writing, integrated with Overleaf.
- [Mathpix](https://mathpix.com) - Convert images and PDFs of math to LaTeX.

## Offline Editors

- [TeXstudio](https://www.texstudio.org) - Cross-platform IDE with autocompletion, preview and assistants.
- [Texmaker](https://www.xm1math.net/texmaker/) - Cross-platform editor with integrated PDF viewer.
- [TeXworks](https://www.tug.org/texworks/) - Simple editor shipped with TeX Live and MiKTeX.
- [LyX](https://www.lyx.org) - WYSIWYM document processor that outputs LaTeX.
- [Kile](https://kile.sourceforge.io) - KDE LaTeX editor.
- [TeXShop](https://pages.uoregon.edu/koch/texshop/) - Native macOS editor, ships with MacTeX.
- [Texifier](https://www.texifier.com) - macOS and iOS editor with live typesetting (formerly Texpad).
- [WinEdt](https://www.winedt.com) - Windows editor with deep MiKTeX integration.
- [TeXnicCenter](https://www.texniccenter.org) - Windows LaTeX IDE.
- [Gummi](https://github.com/alexandervdm/gummi) - Lightweight editor with live preview.

## Editor Plugins and Language Servers

- [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop) - VS Code extension: build, preview, SyncTeX, snippets.
- [Overleaf Workshop](https://github.com/iamhyc/Overleaf-Workshop) - Edit Overleaf projects from VS Code.
- [VimTeX](https://github.com/lervag/vimtex) - LaTeX plugin for Vim and Neovim.
- [AUCTeX](https://www.gnu.org/software/auctex/) - LaTeX environment for Emacs.
- [LaTeXTools](https://github.com/SublimeText/LaTeXTools) - LaTeX plugin for Sublime Text.
- [TexLab](https://github.com/latex-lsp/texlab) - LaTeX language server (works with any LSP editor).
- [LTeX+](https://github.com/ltex-plus/ltex-ls-plus) - LanguageTool-based grammar and spell checking language server.

## Distributions

- [TeX Live](https://tug.org/texlive/) - Full cross-platform TeX distribution.
- [MiKTeX](https://miktex.org) - Distribution with on-the-fly package installation.
- [MacTeX](https://tug.org/mactex/) - TeX Live packaged for macOS.
- [TinyTeX](https://yihui.org/tinytex/) - Small, portable TeX Live based distribution.
- [Tectonic](https://tectonic-typesetting.github.io) - Self-contained engine that fetches packages on demand and reruns automatically.
- [proTeXt](https://www.tug.org/protext/) - MiKTeX based Windows bundle.

## Engines

- [pdfTeX](https://www.tug.org/applications/pdftex/) - Default engine for `pdflatex`.
- [XeTeX](https://tug.org/xetex/) - Unicode and system font support.
- [LuaTeX](https://www.luatex.org) - TeX engine with embedded Lua scripting.
- [ConTeXt](https://wiki.contextgarden.net) - Alternative macro package on LuaMetaTeX.

## Build Tools

- [latexmk](https://ctan.org/pkg/latexmk) - Runs LaTeX, BibTeX/Biber and friends the right number of times.
- [arara](https://github.com/islandoftex/arara) - Rule-based build tool driven by directives in the source.
- [latexrun](https://github.com/aclements/latexrun) - Cleaner build output and error messages.
- [rubber](https://gitlab.com/latex-rubber/rubber) - Automated LaTeX build system.
- [ClutTeX](https://github.com/minoki/cluttex) - Builds without cluttering your directory.

## PDF Viewers with SyncTeX

- [Skim](https://skim-app.sourceforge.io) - macOS.
- [SumatraPDF](https://www.sumatrapdfreader.org) - Windows.
- [Zathura](https://pwmt.org/projects/zathura/) - Linux, keyboard driven.
- [Okular](https://okular.kde.org) - KDE, cross-platform.

## Packages

All links point to [CTAN](https://ctan.org).

**Math**
- [amsmath](https://ctan.org/pkg/amsmath) - Core math environments.
- [mathtools](https://ctan.org/pkg/mathtools) - Fixes and extensions for amsmath.
- [unicode-math](https://ctan.org/pkg/unicode-math) - OpenType math fonts for XeLaTeX/LuaLaTeX.
- [siunitx](https://ctan.org/pkg/siunitx) - Numbers and SI units.

**Layout and typography**
- [geometry](https://ctan.org/pkg/geometry) - Page margins.
- [microtype](https://ctan.org/pkg/microtype) - Microtypography, better line breaks.
- [fontspec](https://ctan.org/pkg/fontspec) - System font selection for XeLaTeX/LuaLaTeX.
- [enumitem](https://ctan.org/pkg/enumitem) - List customization.
- [babel](https://ctan.org/pkg/babel) / [polyglossia](https://ctan.org/pkg/polyglossia) - Multilingual support.
- [csquotes](https://ctan.org/pkg/csquotes) - Context-aware quotation marks.

**References and links**
- [hyperref](https://ctan.org/pkg/hyperref) - Hyperlinks and PDF metadata.
- [cleveref](https://ctan.org/pkg/cleveref) - Smart cross-references.
- [glossaries](https://ctan.org/pkg/glossaries) - Glossaries and acronyms.

**Floats and tables**
- [booktabs](https://ctan.org/pkg/booktabs) - Professional table rules.
- [tabularray](https://ctan.org/pkg/tabularray) - Modern table interface.
- [subcaption](https://ctan.org/pkg/subcaption) - Subfigures.

**Code and algorithms**
- [minted](https://ctan.org/pkg/minted) - Syntax highlighting via Pygments.
- [listings](https://ctan.org/pkg/listings) - Source code listings, no external deps.
- [algorithm2e](https://ctan.org/pkg/algorithm2e) - Algorithm typesetting.
- [algorithmicx](https://ctan.org/pkg/algorithmicx) - Pseudocode (`algpseudocode`).

**Boxes, notes, color**
- [xcolor](https://ctan.org/pkg/xcolor) - Colors.
- [tcolorbox](https://ctan.org/pkg/tcolorbox) - Colored and framed boxes.
- [todonotes](https://ctan.org/pkg/todonotes) - Margin TODOs.

**Science**
- [chemfig](https://ctan.org/pkg/chemfig) - Chemical structures.
- [mhchem](https://ctan.org/pkg/mhchem) - Chemical formulas and equations.
- [circuitikz](https://ctan.org/pkg/circuitikz) - Electrical circuits.

**Slides and posters**
- [beamer](https://ctan.org/pkg/beamer) - Presentations.
- [metropolis](https://github.com/matze/mtheme) - Clean Beamer theme.
- [tikzposter](https://ctan.org/pkg/tikzposter) - Scientific posters.
- [beamerposter](https://ctan.org/pkg/beamerposter) - Posters with Beamer.

## Bibliography and Citations

- [BibLaTeX](https://ctan.org/pkg/biblatex) + [Biber](https://ctan.org/pkg/biber) - Modern bibliography system.
- [natbib](https://ctan.org/pkg/natbib) - Classic author-year citations for BibTeX.
- [Zotero](https://www.zotero.org) - Reference manager.
- [Better BibTeX](https://retorque.re/zotero-better-bibtex/) - Zotero plugin for stable citekeys and auto-export.
- [JabRef](https://www.jabref.org) - BibTeX-native reference manager.
- [BibDesk](https://bibdesk.sourceforge.io) - macOS BibTeX manager.
- [Mendeley](https://www.mendeley.com) - Reference manager with BibTeX export.
- [doi2bib](https://www.doi2bib.org) - DOI to BibTeX.
- [bibtex-tidy](https://github.com/FlamingTempura/bibtex-tidy) - Clean, format and dedupe `.bib` files.
- [rebiber](https://github.com/yuchenlin/rebiber) - Replace arXiv entries with published versions.
- [bibtexparser](https://github.com/sciunto-org/python-bibtexparser) - Parse and write BibTeX in Python.

## Figures and Diagrams

- [PGF/TikZ](https://ctan.org/pkg/pgf) - Programmatic graphics in LaTeX.
- [PGFPlots](https://ctan.org/pkg/pgfplots) - Plots in TikZ.
- [tikz-cd](https://ctan.org/pkg/tikz-cd) - Commutative diagrams.
- [forest](https://ctan.org/pkg/forest) - Trees.
- [TikZiT](https://tikzit.github.io) - GUI for TikZ graphs.
- [quiver](https://q.uiver.app) - Commutative diagram editor with tikz-cd export.
- [Mathcha](https://www.mathcha.io) - Online math and diagram editor with TikZ export.
- [Ipe](https://ipe.otfried.org) - Drawing editor with LaTeX text.
- [Inkscape](https://inkscape.org) - Vector editor, exports PDF+LaTeX.
- [TexText](https://github.com/textext/textext) - LaTeX objects inside Inkscape.
- [draw.io](https://www.drawio.com) - Diagrams, exports PDF/SVG.
- [Asymptote](https://asymptote.sourceforge.io) - Vector graphics language with LaTeX labels.
- [SciencePlots](https://github.com/garrettj403/SciencePlots) - Matplotlib styles for papers.
- [TikZ.net](https://tikz.net) - Gallery of TikZ examples.
- [TeXample.net](https://texample.net) - TikZ examples.

## Tables

- [Tables Generator](https://www.tablesgenerator.com) - Visual table builder, LaTeX output.
- [Excel2LaTeX](https://ctan.org/pkg/excel2latex) - Excel add-in exporting tables.
- [pandas `to_latex`](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.to_latex.html) - DataFrame to LaTeX.

## Math, Symbols and OCR

- [Detexify](https://detexify.kirelabs.org) - Draw a symbol, get its command.
- [The Comprehensive LaTeX Symbol List](https://ctan.org/pkg/comprehensive) - Every symbol, with packages.
- [Mathpix](https://mathpix.com) - Image/PDF to LaTeX.
- [LaTeX-OCR (pix2tex)](https://github.com/lukas-blecher/LaTeX-OCR) - Open-source equation image to LaTeX.
- [Nougat](https://github.com/facebookresearch/nougat) - Academic PDF to markup with math.
- [latexify_py](https://github.com/google/latexify_py) - Python functions to LaTeX.
- [handcalcs](https://github.com/connorferster/handcalcs) - Render Python calculations as LaTeX.

## Conversion

- [Pandoc](https://pandoc.org) - Universal converter (Markdown, Word, LaTeX, HTML).
- [LaTeXML](https://math.nist.gov/~BMiller/LaTeXML/) - LaTeX to XML/HTML/MathML, used by arXiv HTML.
- [make4ht](https://ctan.org/pkg/make4ht) - Build system for TeX4ht, LaTeX to HTML/ODT.
- [KaTeX](https://katex.org) - Fast math rendering on the web.
- [MathJax](https://www.mathjax.org) - Math rendering on the web.

## Linting, Formatting and Diffing

- [ChkTeX](https://www.nongnu.org/chktex/) - LaTeX linter.
- [latexindent.pl](https://github.com/cmhughes/latexindent.pl) - Formatter and indenter.
- [tex-fmt](https://github.com/WGUNDERWOOD/tex-fmt) - Fast LaTeX formatter in Rust.
- [TeXtidote](https://github.com/sylvainhalle/textidote) - Spelling and grammar checker for LaTeX.
- [latexdiff](https://ctan.org/pkg/latexdiff) - Marked-up diff between two versions.
- [git-latexdiff](https://gitlab.com/git-latexdiff/git-latexdiff) - latexdiff across Git revisions.
- [TeXcount](https://app.uio.no/ifi/texcount/) - Word count for LaTeX.
- [arxiv-latex-cleaner](https://github.com/google-research/arxiv-latex-cleaner) - Strip comments and unused files before arXiv submission.

## Programmatic LaTeX

**Python**
- [PyLaTeX](https://github.com/JelteF/PyLaTeX) - Generate LaTeX documents from Python.
- [pylatexenc](https://github.com/phfaist/pylatexenc) - LaTeX to Unicode and back, parser.
- [TexSoup](https://github.com/alvinwan/TexSoup) - Navigate and edit LaTeX like BeautifulSoup.
- [plasTeX](https://github.com/plastex/plastex) - LaTeX processor in Python.

**R**
- [knitr](https://yihui.org/knitr/) - Dynamic reports with R and LaTeX.
- [Quarto](https://quarto.org) - Scientific publishing system with LaTeX/PDF output.

**Julia**
- [Latexify.jl](https://github.com/korsbo/Latexify.jl) - Julia objects to LaTeX.

## LaTeX in the Browser

- [SwiftLaTeX](https://github.com/SwiftLaTeX/SwiftLaTeX) - TeX engines compiled to WebAssembly.
- [BusyTeX](https://github.com/busytex/busytex) - TeX Live tools in WebAssembly.
- [LaTeX.js](https://github.com/michael-brade/LaTeX.js) - LaTeX to HTML in JavaScript.

## CI, Docker and Self-Hosting

- [latex-action](https://github.com/xu-cheng/latex-action) - GitHub Action to compile LaTeX.
- [Island of TeX Docker images](https://gitlab.com/islandoftex/images/texlive) - TeX Live container images.
- [Overleaf Community Edition](https://github.com/overleaf/overleaf) - Self-host Overleaf.

## Templates

**General**
- [Overleaf Templates](https://www.overleaf.com/latex/templates) - Thousands of templates.
- [LaTeXTemplates.com](https://www.latextemplates.com) - Curated templates by category.

**Publisher and conference classes**
- [IEEEtran](https://ctan.org/pkg/ieeetran) - IEEE.
- [acmart](https://ctan.org/pkg/acmart) - ACM.
- [llncs](https://ctan.org/pkg/llncs) - Springer LNCS.
- [elsarticle](https://ctan.org/pkg/elsarticle) - Elsevier.
- [revtex](https://ctan.org/pkg/revtex) - APS and AIP physics journals.
- [ACL style files](https://github.com/acl-org/acl-style-files) - ACL, EMNLP, NAACL.
- [ICLR template](https://github.com/ICLR/Master-Template) - ICLR.
- NeurIPS and ICML style files are released each year on [neurips.cc](https://neurips.cc) and [icml.cc](https://icml.cc).

**Theses, books, CVs**
- [classicthesis](https://ctan.org/pkg/classicthesis) - Thesis style.
- [tufte-latex](https://ctan.org/pkg/tufte-latex) - Tufte-style books and handouts.
- [Awesome-CV](https://github.com/posquit0/Awesome-CV) - CV and cover letter.
- [moderncv](https://ctan.org/pkg/moderncv) - CV class.
- [Jake's Resume](https://github.com/jakegut/resume) - Popular one-page resume.

## Fonts

- [The LaTeX Font Catalogue](https://tug.org/FontCatalogue/) - Fonts available in TeX, with samples.

## Learning Resources

- [Learn LaTeX](https://www.learnlatex.org) - Free interactive course by the LaTeX community.
- [Overleaf Learn](https://www.overleaf.com/learn) - Documentation and tutorials.
- [LaTeX Wikibook](https://en.wikibooks.org/wiki/LaTeX) - Comprehensive free book.
- [The Not So Short Introduction to LaTeX](https://ctan.org/pkg/lshort) - Classic intro.
- [texdoc.org](https://texdoc.org) - Online package documentation.

## Community

- [TeX Stack Exchange](https://tex.stackexchange.com) - Q&A.
- [CTAN](https://ctan.org) - Comprehensive TeX Archive Network.
- [TUG](https://tug.org) - TeX Users Group.
- [The LaTeX Project](https://www.latex-project.org) - LaTeX kernel team.

## Alternatives to LaTeX

- [Typst](https://typst.app) - Modern markup-based typesetting with fast compiles.
- [Quarto](https://quarto.org) - Markdown-based scientific publishing.
- [ConTeXt](https://wiki.contextgarden.net) - TeX-based alternative to LaTeX.

## Contributing

1. Fork the repo.
2. Add your entry in the right section, alphabetical order not required but keep similar items together.
3. Format: `- [Name](https://link) - Short description ending with a period.`
4. One entry per PR is preferred.
5. Tools must be actively maintained, real and relevant to LaTeX users. No affiliate links.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright to this work.

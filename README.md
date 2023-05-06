# lboro-beamer-template
An unofficial LaTeX Beamer presentation template for Loughborough University

This template uses the package [`svg`](https://ctan.org/pkg/svg?lang=en) where the command \includesvg will convert under the hood the university logo. This requires the help of either [Inkscape](http://www.inkscape.org/) (recommened) or [ImageMagick](http://www.imagemagick.org/). Please make sure you have one of these installed before compiling the source.

```
pdflatex --shell-escape example.tex
```

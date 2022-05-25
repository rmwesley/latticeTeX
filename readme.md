To compile to an image directly with `pdflatex`, add the convert instruction at the document definition: `\documentclass[tikz, convert={..., outext=.png}]{standalone}`. Then use the `-shell-escape` option on the call to the compiler, e.g.:

`pdflatex -shell-escape example.tex`

Example outputs:

![Honeycomb-Kagome lattice](images/example.png)

![Honeycomb-Kagome unit cell](images/unitcell.png)

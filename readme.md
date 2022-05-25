You can easily compile these standalone images with `pdflatex`, e.g.:

`pdflatex example.tex`

To produce a PNG image in linux, use ImageMagick's `convert` command, e.g.:

`convert -density 400 -quality 90 example.pdf images/example.png`

## Example outputs:

| ![lattice](images/example.png) |
|:--:|
| *Honeycomb-Kagome lattice* |

| ![unit-cell](images/unitcell.png) |
|:--:| 
| *Honeycomb-Kagome unit cell* |

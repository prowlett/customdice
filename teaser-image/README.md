# Teaser image

This folder contains the code and output for the teaser image used on CTAN. The output images `customdice.png` and `customdice-large.png` are distributed as CC-0.

## Note to self

Convert the pdflatex output using

```
convert -density 72 teaser-image.pdf customdice-large.png
convert -density 72 -resize 50% teaser-image.pdf customdice.png
```

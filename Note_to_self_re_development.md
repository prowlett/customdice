# Developer notes

Files uploaded to CTAN are:
- `customdice.ins`
- `customdice.dtx`
- `customdice.pdf`
- `README.md`

Put these in a subdirectory `customdice/` then zip this subdirectory for upload.

Don't edit `customdice.sty` directly. Its source, and the source for `customdice.pdf` are in `customdice.dtx`.

Make `customdice.sty` by running `latex customdice.ins`.

Then make `customdice.pdf` by running `pdflatex customdice.dtx`.

# customdice: LaTeX package for drawing customisable dice

`customdice` is a package for LaTeX, LuaLaTeX and XeTeX that provides functionality for drawing dice. The aim is to provide highly-customisable but simple-to-use commands, allowing:

- adding custom text to dice faces;
- control over colouring;
- control over sizing.

By [Peter Rowlett](https://github.com/prowlett/).

The package is licenced under [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).

## Changes

### [1.1] - 2022-08-10

- Added option to include 7, 8 or 9 dots on a standard dice face via `\dice{}`
- Added control over dice face border colour.
- Fixed bug meaning extra whitespace appeared after e.g. `\Largedice{5}` that did not appear with `\Large\dice{5}`.

### [1.0] - 2022-07-31

- First working version of package

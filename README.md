# (Discontinued Development)  Festival - Modal Text Editor

## Summary
I have gripes with every text editor I've used and, although many have great customization options, I wanted the flexibility that comes with making one from scratch. The main goals of the editor are to be smooth, with interpolated animations and nice graphic design, as well as easy on the fingers, with a modal system inspired by [Vim](https://www.vim.org/) and [Xah Fly Keys](http://xahlee.info/emacs/misc/xah-fly-keys.html).
Currently only for Linux, but it's built to be reasonably cross-platform and I plan to have Windows versions in the future.

## Libraries used
[Raylib](https://www.raylib.com/) For cross-platform graphics, input, and filesystem operations.
[libiconv](https://www.gnu.org/software/libiconv/) for text encoding conversion.
[libchardet](https://github.com/Joungkyun/libchardet/blob/master/README.md?plain=1) for text encoding detection.

## Current features
+ Buffer and View (tiled window) systems
+ Command and lister systems
+ Able to read from and write to any format using internal UTF-32 representation
+ Dynamic glyph loading based on unicode block ranges.

# Sketch-Linked-SVG
Sketch already supports drag and drop SVG files. However by importing SVG files via this plugin, you can update the imported SVG layer if the external source file changed.


# Installation

[Download Sketch-Linked-SVG](https://github.com/66eli77/Sketch-Linked-SVG/archive/master.zip) & unzip it.
Double click `Linked SVG.sketchplugin` to install the Plugin.


# Usage

- `Update Linked SVGs` -- reload all SVG layers marked with `@@`

- `Import Linked SVG` -- import external SVG file into a SVG layer and mark the layer with `@@` follow by the relative location of the external SVG file.

- `Export SVG` -- save the selected layers into a SVG file.

- `Open SVG` -- open external SVG file in a `page`.

- `Save SVG` -- save all layers in the current `page` into a SVG file.

This plugin eventually enables you to use SVG as the target file format for Sketch, and output consistent and concise SVG code. If you plan to manage a SVG based project on Github, this plugin will help you reduce merge conflict greatly or make it easy to resolve.


# References

Big thanks to <a href="https://github.com/frankko/Place-Linked-Bitmap" target="_blank">Place-Linked-Bitmap</a> for inspirations and <a href="https://github.com/BohemianCoding/svgo-compressor" target="_blank">SVGO Compressor</a> for providing the compression methods and <a href="https://github.com/abynim/Sketch-Headers" target="_blank">Sketch-Headers</a> for how to use undocumented Sketch functionality.

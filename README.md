# README

Tuirgin's Cartography Symbols provide SVG symbols for common ASCII symbols—alpha, numeric, punctuation—as well as cartographic symbols commonly used for dungeon mapping in old-school tabletop RPGs.

## Alpha-Numeric Symbols

The alpha, numeric, and punctuation symbols are available in a variety of colors. I primarily use them for monster tokens inspired by ASCII roguelikes such as Nethack and Angband, and use different colors to represent different sub-types of creatures.

## Cartography Symbols

There are a few black-only (or black and white) symbols in the `mono` folder. The remaining symbols are in color folders, currently `white` and `yellow`. The white symbols are provided for ease of recoloring or tinting within a VTT. The yellow symbols are what I use in maps as they retain high visibility even when map lighting is dim and the symbols are "hidden" and rendered with reduced opacity.

## FoundryVTT Installation

Use the following manifest URL:

<https://github.com/tuirgin/tuirgins-cartography-symbols/releases/latest/download/module.json>

## New Colors

The quickest way to create a new color is to copy a folder of white symbols and perform the following on the copies—but be sure to replace `#000000` with the hex color of your choice:

`sed -i 's/#ffffff/#000000/g' *.svg`

If you're using these symbols with a VTT such as FoundryVTT, you can use the white symbols and tint them within the VTT.

## Licensing

See LICENSE.md for licensing details: the glyphs are based on Adobe's SIL licensed Source Code Pro, while the cartography symbols are traditional.

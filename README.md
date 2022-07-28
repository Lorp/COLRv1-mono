# COLRv1-mono

Demo fonts that exploit the COLRv1 spec to show new possibilities in monochrome typefaces.

## Background

The [OpenType COLRv1 specification](https://docs.microsoft.com/en-us/typography/opentype/spec/colr) version 1.9, published in 2021, introduces a number of powerful new ways to handle color data in fonts. Compared with COLRv0, introduced in 2013, COLRv1 adds features including:
* gradients (linear/radial/sweep with multiple color stops)
* blending modes
* affine transformations

In an OpenType font a COLR table (both v0 and v1) coexists with a CPAL table, which stores color palette data. As well as referring to colors in the CPAL table, a COLR table can use a special identifier, 0xffff, to refer to the current foreground color as chosen by a system or user. All of the COLRv1 demo fonts in this repo make use of the 0xffff color reference, and thus provide solutions for monochrome fonts that are only color fonts a technical sense.

We provide full documentation on how to recreate each font.

We hope that these demo fonts:

* **inspire other type designers and icon designers to make such fonts;**
* **encourage authors of font editors (e.g. Glyphs and FontLab) to add UI to make such fonts;**
* **encourage system software engineers to support such fonts.**




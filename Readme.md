# NeoFuthark

Not happy with the lack of Sci-Fi Elder Futhark fonts available I
decided to make one.
![sample](image url "NeoFuthark.png")


## Glyphs
The unicode code points for the elder futhark runes are
supported. Currently no other codepoints.


## Process

I've been working with a single SVG file in inkscape to make the all
the runes, then I extracted each glyph into the `glyphs/` directory.

I then used fontforge to build the font files.

## Issues

The font wasa not made with the restrictions in font file formats in
mind. It was not made with integer points and the an EM size
of 1024. Subsequent rounding and scaling will inevitably caused some
less than perfect pixels.

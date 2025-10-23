# VNDS
VNDS with many new features.

List of changes:
Added back mp3/aac support
RGB text color support by putting "\x1b[r;g;bm" in a line. Values are from 0-31
Added changing the font with \font(fontname.ttf). Works mid-line as well. Fonts go in the root folder of the novel, and it needs a font called default.ttf in there or it'll probably break.
More stuff
This contains a fork of Edward Tufte's ET Book (free Bembo) font.

The originals may be found here:
https://edwardtufte.github.io/et-book/

The originals have ligatures but don't contain any liga gsub table, so
the ligatures don't get automatically inserted as they should. I used
Fontforge to add an appropriate liga gsub table.

You will notice there is no ff ligature (just fi, ffi, fl, and ffl). That's
the way the font came, and I didn't add one. It doesn't seem to need one
that badly; two adjacent f's dont run into each other like fi and fl did.

Tufte's original fonts are .ttf files; mine are .otf files. This should
not matter much; nearly every system supports OTF's.

The .sfd files are the Fontforge projects for each font. If you don't care
about editing fonts with Fontforge, you can just ignore them.
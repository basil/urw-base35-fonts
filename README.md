# URW Base 35 fonts

## Introduction

URW's Base 35 fonts are open-source recreations of the 35 core fonts required by Adobe's PostScript Language Level 2, developed by the German type foundry [URW++](https://www.urwtype.com/):

- Century Schoolbook (substituting for Adobe’s New Century Schoolbook)
- Dingbats (substituting for Adobe’s Zapf Dingbats)
- Nimbus Mono L (substituting for Adobe’s Courier)
- Nimbus Roman No9 L (substituting for Adobe’s Times)
- Nimbus Sans L (substituting for Adobe’s Helvetica)
- Standard Symbols L (substituting for Adobe’s Symbol)
- URW Bookman
- URW Chancery L Medium Italic (substituting for Adobe’s Zapf Chancery)
- URW Gothic L Book (substituting for Adobe’s Avant Garde)
- URW Palladio L (substituting for Adobe’s Palatino)

These original files are still available and can be freely downloaded, but they can be hard to find.
So I tracked them down and wrote a script to convert them into a new package of OTFs, TTFs, and webfonts.

## Prerequisites

- [FontForge](https://fontforge.org)

## Build

```bash
$ ./build.sh
$ ls dist/*.zip
dist/C059.zip
dist/D050000L.zip
dist/NimbusMonoPS.zip
dist/NimbusRoman.zip
dist/NimbusSans.zip
dist/NimbusSansNarrow.zip
dist/P052.zip
dist/StandardSymbolsPS.zip
dist/URWBookman.zip
dist/URWGothic.zip
dist/Z003.zip
```

## License

See [LICENSE](./LICENSE).

## Related

- [Utopia](https://github.com/basil/adobe-utopia-type1)
- [Luxi fonts](https://github.com/basil/bh-ttf)
- [Bitstream fonts](https://github.com/basil/bitstream-type1)
- [IBM Courier](https://github.com/basil/ibm-type1)
- [URW free fonts](https://github.com/basil/urw-free-fonts)

## Original

Repository for (URW)++ base 35 font set

`urw-base35-fonts/fonts`
 * Contains the URW++ font files themselves.
 * These are substitutes for the 35 fonts required by Adobe Postscript(c) Language Level 2.
 * They are included in Postscript Type1, OTF, and TTF formats.
 * AFM metrics files are also included.

`urw-base35-fonts/appstream`
 * Contains the metadata files for integration with AppStream.
 * See: https://www.freedesktop.org/wiki/Distributions/AppStream/

`urw-base35-fonts/fontconfig`
 * Contains the metadata files for fontconfig (attributes, name mapping, etc).
 * See: https://www.freedesktop.org/wiki/Software/fontconfig/

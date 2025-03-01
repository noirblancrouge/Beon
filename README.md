# Beon

[![][Fontbakery]](https://noirblancrouge.github.io/Beon/fontbakery/fontbakery-report.html)
[![][Universal]](https://noirblancrouge.github.io/Beon/fontbakery/fontbakery-report.html)
[![][Outline Checks]](https://noirblancrouge.github.io/Beon/fontbakery/fontbakery-report.html)
[![][Font File Checks]](https://noirblancrouge.github.io/Beon/fontbakery/fontbakery-report.html)
[![][OpenType Specification Checks]](https://noirblancrouge.github.io/Beon/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/Beon/badges/overall.json
[Outline Checks]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/Beon/badges/OutlineChecks.json
[Font File Checks]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/Beon/badges/FontFileChecks.json
[Universal]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/Beon/badges/UniversalProfileChecks.json
[OpenType Specification Checks]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/Beon/badges/OpenTypeSpecificationChecks.json

![Cover](https://raw.githubusercontent.com/noirblancrouge/Beon/master/documentation/images/beon.jpg)

Beon is a Neon stencil typeface, comes in a single weight, including multilingual support and openType features.
Beon can be used for a wide range of projects.

The Beon font as originally been designed for the movie BangBang by Raphael L. Lungo, the typeface has been develop for the appearance of the names of actors and the final drop.

![Specimen](https://raw.githubusercontent.com/noirblancrouge/Beon/master/documentation/images/beon-charset.jpg)

## ChangeLog

When you make modifications, be sure to add a description of your changes,
following the format of the other entries, to the start of this section.

14 Feb 2025 (Bastien Sozeau)
- Add glyphs according to the standards of the NBR glyphset

4 Sep 2023 (Bastien Sozeau)
- Update License, cleanup drawing, add glyphs

8 Oct 2014 (Christoph Haag) 
- created fontforge sources as base to work on GNU/Linux
- added FONTLOG to .sfdir
- Mastered Font from Fontforge SFDIR to 
  UFO,OTF,TTF,EOT,WOFF,SVG
  
17 Jan 2011 (Bastien Sozeau)
- Initital release.

## Bio

Bastien Sozeau is the founder of NoirBlancRouge, an independent type foundry based in Paris since 2019. Specializing in retail and custom typefaces, Bastien has crafted unique fonts for renowned brands such as Kipling, Christian Louboutin and The Olympic Museum. Beyond their commercial work, NoirBlancRouge has also been actively involved in designing free and open-source typefaces since 2013.

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at [noirblancrouge.github.io/Beon](https://noirblancrouge.github.io/Beon).

## License

Developed by [NoirBlancRouge Type Foundry](https://noirblancrouge.com) (Originally distributed by graphic design studio [Uplaod](https://uplaod.fr)), Beon is open source and licensed under OFL, the SIL Open Font License allows the licensed fonts to be used, studied, modified and redistributed freely as long as they are not sold by themselves.

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.

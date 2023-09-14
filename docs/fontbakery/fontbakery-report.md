## FontBakery report

fontbakery version: 0.9.0

<details><summary><b>[6] Beon-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1170 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1193, but got 1020 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 343, but got 150 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: numbersign	Contours detected: 8	Expected: 2

	- Glyph name: asterisk	Contours detected: 8	Expected: 1or4

	- Glyph name: plus	Contours detected: 3	Expected: 1

	- Glyph name: one	Contours detected: 2	Expected: 1

	- Glyph name: two	Contours detected: 2	Expected: 1

	- Glyph name: three	Contours detected: 2	Expected: 1

	- Glyph name: four	Contours detected: 3	Expected: 1or2

	- Glyph name: five	Contours detected: 3	Expected: 1

	- Glyph name: seven	Contours detected: 2	Expected: 1

	- Glyph name: eight	Contours detected: 1	Expected: 3

	- Glyph name: less	Contours detected: 2	Expected: 1

	- Glyph name: greater	Contours detected: 2	Expected: 1

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: E	Contours detected: 4	Expected: 1

	- Glyph name: F	Contours detected: 3	Expected: 1

	- Glyph name: G	Contours detected: 2	Expected: 1

	- Glyph name: H	Contours detected: 3	Expected: 1

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: K	Contours detected: 3	Expected: 1or2

	- Glyph name: L	Contours detected: 2	Expected: 1

	- Glyph name: M	Contours detected: 4	Expected: 1

	- Glyph name: N	Contours detected: 3	Expected: 1

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: S	Contours detected: 3	Expected: 1

	- Glyph name: T	Contours detected: 2	Expected: 1

	- Glyph name: U	Contours detected: 3	Expected: 1

	- Glyph name: V	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 4	Expected: 1or2

	- Glyph name: X	Contours detected: 3	Expected: 1

	- Glyph name: Y	Contours detected: 3	Expected: 1

	- Glyph name: Z	Contours detected: 3	Expected: 1

	- Glyph name: bracketleft	Contours detected: 3	Expected: 1

	- Glyph name: bracketright	Contours detected: 3	Expected: 1

	- Glyph name: asciicircum	Contours detected: 2	Expected: 1

	- Glyph name: f	Contours detected: 3	Expected: 1

	- Glyph name: h	Contours detected: 2	Expected: 1

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: k	Contours detected: 3	Expected: 1or2

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: t	Contours detected: 3	Expected: 1

	- Glyph name: u	Contours detected: 2	Expected: 1

	- Glyph name: v	Contours detected: 2	Expected: 1

	- Glyph name: w	Contours detected: 5	Expected: 1

	- Glyph name: x	Contours detected: 3	Expected: 1

	- Glyph name: y	Contours detected: 3	Expected: 1

	- Glyph name: z	Contours detected: 3	Expected: 1

	- Glyph name: braceleft	Contours detected: 2	Expected: 1

	- Glyph name: braceright	Contours detected: 2	Expected: 1

	- Glyph name: cent	Contours detected: 3	Expected: 1or2

	- Glyph name: sterling	Contours detected: 4	Expected: 1or2

	- Glyph name: currency	Contours detected: 6	Expected: 2

	- Glyph name: yen	Contours detected: 6	Expected: 1or2

	- Glyph name: section	Contours detected: 3	Expected: 2

	- Glyph name: guillemotleft	Contours detected: 4	Expected: 2

	- Glyph name: logicalnot	Contours detected: 2	Expected: 1

	- Glyph name: registered	Contours detected: 5	Expected: 3or4

	- Glyph name: plusminus	Contours detected: 4	Expected: 1or2

	- Glyph name: uni00B2	Contours detected: 2	Expected: 1

	- Glyph name: uni00B3	Contours detected: 2	Expected: 1

	- Glyph name: uni00B5	Contours detected: 3	Expected: 1

	- Glyph name: uni00B9	Contours detected: 2	Expected: 1

	- Glyph name: guillemotright	Contours detected: 4	Expected: 2

	- Glyph name: onequarter	Contours detected: 6	Expected: 3or4

	- Glyph name: onehalf	Contours detected: 5	Expected: 3

	- Glyph name: threequarters	Contours detected: 6	Expected: 3or4

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Aring	Contours detected: 5	Expected: 3or4

	- Glyph name: AE	Contours detected: 6	Expected: 2

	- Glyph name: Egrave	Contours detected: 5	Expected: 2

	- Glyph name: Eacute	Contours detected: 5	Expected: 2

	- Glyph name: Ecircumflex	Contours detected: 5	Expected: 2

	- Glyph name: Edieresis	Contours detected: 6	Expected: 3

	- Glyph name: Eth	Contours detected: 4	Expected: 2

	- Glyph name: Ntilde	Contours detected: 4	Expected: 2

	- Glyph name: multiply	Contours detected: 3	Expected: 1

	- Glyph name: Ugrave	Contours detected: 4	Expected: 2

	- Glyph name: Uacute	Contours detected: 4	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Udieresis	Contours detected: 5	Expected: 3

	- Glyph name: Yacute	Contours detected: 4	Expected: 2

	- Glyph name: germandbls	Contours detected: 4	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: eth	Contours detected: 4	Expected: 2

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: ugrave	Contours detected: 3	Expected: 2

	- Glyph name: uacute	Contours detected: 3	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: udieresis	Contours detected: 4	Expected: 3

	- Glyph name: yacute	Contours detected: 4	Expected: 2

	- Glyph name: ydieresis	Contours detected: 5	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2or3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 4	Expected: 2

	- Glyph name: dcroat	Contours detected: 4	Expected: 2

	- Glyph name: Emacron	Contours detected: 5	Expected: 2

	- Glyph name: Ebreve	Contours detected: 5	Expected: 2

	- Glyph name: Edotaccent	Contours detected: 5	Expected: 2

	- Glyph name: Eogonek	Contours detected: 5	Expected: 1or2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Ecaron	Contours detected: 5	Expected: 2

	- Glyph name: Gcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Gbreve	Contours detected: 3	Expected: 2

	- Glyph name: Gdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: uni0122	Contours detected: 3	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Hbar	Contours detected: 4	Expected: 2

	- Glyph name: hbar	Contours detected: 4	Expected: 1

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

	- Glyph name: ij	Contours detected: 5	Expected: 3or4

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: uni0136	Contours detected: 4	Expected: 2or3

	- Glyph name: uni0137	Contours detected: 4	Expected: 2or3

	- Glyph name: kgreenlandic	Contours detected: 3	Expected: 1or2

	- Glyph name: Lacute	Contours detected: 3	Expected: 2

	- Glyph name: uni013B	Contours detected: 3	Expected: 2

	- Glyph name: Lcaron	Contours detected: 3	Expected: 2

	- Glyph name: Ldot	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 4	Expected: 1

	- Glyph name: lslash	Contours detected: 3	Expected: 1

	- Glyph name: Nacute	Contours detected: 4	Expected: 2

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: uni0145	Contours detected: 4	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: Ncaron	Contours detected: 4	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 3	Expected: 1

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 5	Expected: 2

	- Glyph name: oe	Contours detected: 5	Expected: 3

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: Sacute	Contours detected: 4	Expected: 2

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Scedilla	Contours detected: 4	Expected: 1or2

	- Glyph name: scedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: Scaron	Contours detected: 4	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: uni0162	Contours detected: 3	Expected: 1or2

	- Glyph name: uni0163	Contours detected: 4	Expected: 1or2

	- Glyph name: Tcaron	Contours detected: 3	Expected: 2

	- Glyph name: tcaron	Contours detected: 4	Expected: 2

	- Glyph name: Tbar	Contours detected: 4	Expected: 1

	- Glyph name: tbar	Contours detected: 5	Expected: 1

	- Glyph name: Utilde	Contours detected: 4	Expected: 2

	- Glyph name: utilde	Contours detected: 3	Expected: 2

	- Glyph name: Umacron	Contours detected: 4	Expected: 2

	- Glyph name: umacron	Contours detected: 3	Expected: 2

	- Glyph name: Ubreve	Contours detected: 4	Expected: 2

	- Glyph name: ubreve	Contours detected: 3	Expected: 2

	- Glyph name: Uring	Contours detected: 5	Expected: 3

	- Glyph name: uring	Contours detected: 4	Expected: 3

	- Glyph name: Uhungarumlaut	Contours detected: 5	Expected: 3

	- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 4	Expected: 1

	- Glyph name: uogonek	Contours detected: 3	Expected: 1

	- Glyph name: Wcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 6	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 4	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 5	Expected: 3

	- Glyph name: Zacute	Contours detected: 4	Expected: 2

	- Glyph name: zacute	Contours detected: 4	Expected: 2

	- Glyph name: Zdotaccent	Contours detected: 4	Expected: 2

	- Glyph name: zdotaccent	Contours detected: 4	Expected: 2

	- Glyph name: Zcaron	Contours detected: 4	Expected: 2

	- Glyph name: zcaron	Contours detected: 4	Expected: 2

	- Glyph name: florin	Contours detected: 3	Expected: 1

	- Glyph name: uni019D	Contours detected: 3	Expected: 1

	- Glyph name: Gcaron	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4or5

	- Glyph name: AEacute	Contours detected: 7	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: uni0218	Contours detected: 4	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni021A	Contours detected: 3	Expected: 2

	- Glyph name: uni021B	Contours detected: 4	Expected: 2

	- Glyph name: uni0232	Contours detected: 4	Expected: 2

	- Glyph name: uni0233	Contours detected: 4	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni0394	Contours detected: 3	Expected: 2

	- Glyph name: uni03A9	Contours detected: 3	Expected: 1

	- Glyph name: uni03BC	Contours detected: 3	Expected: 1

	- Glyph name: pi	Contours detected: 3	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E14	Contours detected: 6	Expected: 3

	- Glyph name: uni1E16	Contours detected: 6	Expected: 3

	- Glyph name: uni1E1C	Contours detected: 6	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E20	Contours detected: 3	Expected: 2

	- Glyph name: uni1E24	Contours detected: 4	Expected: 2

	- Glyph name: uni1E25	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 4	Expected: 2

	- Glyph name: uni1E2B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E36	Contours detected: 3	Expected: 2

	- Glyph name: uni1E3A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E42	Contours detected: 5	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E44	Contours detected: 4	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E46	Contours detected: 4	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: uni1E48	Contours detected: 4	Expected: 2

	- Glyph name: uni1E49	Contours detected: 3	Expected: 2

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: uni1E5B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E5E	Contours detected: 4	Expected: 3

	- Glyph name: uni1E5F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E60	Contours detected: 4	Expected: 2

	- Glyph name: uni1E61	Contours detected: 3	Expected: 2

	- Glyph name: uni1E62	Contours detected: 4	Expected: 2

	- Glyph name: uni1E63	Contours detected: 3	Expected: 2

	- Glyph name: uni1E64	Contours detected: 5	Expected: 3

	- Glyph name: uni1E65	Contours detected: 4	Expected: 3

	- Glyph name: uni1E66	Contours detected: 5	Expected: 3

	- Glyph name: uni1E67	Contours detected: 4	Expected: 3

	- Glyph name: uni1E68	Contours detected: 5	Expected: 3

	- Glyph name: uni1E69	Contours detected: 4	Expected: 3

	- Glyph name: uni1E6C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E6D	Contours detected: 4	Expected: 2

	- Glyph name: uni1E6E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E6F	Contours detected: 4	Expected: 2

	- Glyph name: uni1E78	Contours detected: 5	Expected: 3

	- Glyph name: uni1E79	Contours detected: 4	Expected: 3

	- Glyph name: uni1E7A	Contours detected: 6	Expected: 4

	- Glyph name: uni1E7B	Contours detected: 5	Expected: 4

	- Glyph name: Wgrave	Contours detected: 5	Expected: 2

	- Glyph name: wgrave	Contours detected: 6	Expected: 2

	- Glyph name: Wacute	Contours detected: 5	Expected: 2

	- Glyph name: wacute	Contours detected: 6	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 6	Expected: 3

	- Glyph name: wdieresis	Contours detected: 7	Expected: 3

	- Glyph name: uni1E8E	Contours detected: 4	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 4	Expected: 2

	- Glyph name: uni1E92	Contours detected: 4	Expected: 2

	- Glyph name: uni1E93	Contours detected: 4	Expected: 2

	- Glyph name: uni1E97	Contours detected: 5	Expected: 3

	- Glyph name: uni1E9E	Contours detected: 4	Expected: 1

	- Glyph name: uni1EA0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EB8	Contours detected: 5	Expected: 2

	- Glyph name: uni1EBC	Contours detected: 5	Expected: 2

	- Glyph name: uni1EE4	Contours detected: 4	Expected: 2

	- Glyph name: uni1EE5	Contours detected: 3	Expected: 2

	- Glyph name: Ygrave	Contours detected: 4	Expected: 2

	- Glyph name: ygrave	Contours detected: 4	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 4	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 4	Expected: 2

	- Glyph name: dagger	Contours detected: 3	Expected: 1or2

	- Glyph name: daggerdbl	Contours detected: 5	Expected: 1or3

	- Glyph name: guilsinglleft	Contours detected: 2	Expected: 1

	- Glyph name: guilsinglright	Contours detected: 2	Expected: 1

	- Glyph name: uni2074	Contours detected: 3	Expected: 1or2

	- Glyph name: uni2075	Contours detected: 3	Expected: 1

	- Glyph name: uni2077	Contours detected: 2	Expected: 1

	- Glyph name: uni2078	Contours detected: 1	Expected: 3

	- Glyph name: uni2081	Contours detected: 2	Expected: 1

	- Glyph name: uni2082	Contours detected: 2	Expected: 1

	- Glyph name: uni2083	Contours detected: 2	Expected: 1

	- Glyph name: uni2084	Contours detected: 3	Expected: 1or2

	- Glyph name: uni2085	Contours detected: 3	Expected: 1

	- Glyph name: uni2087	Contours detected: 2	Expected: 1

	- Glyph name: uni2088	Contours detected: 1	Expected: 3

	- Glyph name: Euro	Contours detected: 5	Expected: 1or2

	- Glyph name: uni2116	Contours detected: 6	Expected: 3or4

	- Glyph name: trademark	Contours detected: 6	Expected: 2

	- Glyph name: uni2126	Contours detected: 3	Expected: 1

	- Glyph name: emptyset	Contours detected: 5	Expected: 3

	- Glyph name: uni2206	Contours detected: 3	Expected: 2

	- Glyph name: product	Contours detected: 3	Expected: 1

	- Glyph name: summation	Contours detected: 4	Expected: 1

	- Glyph name: radical	Contours detected: 3	Expected: 1

	- Glyph name: infinity	Contours detected: 1	Expected: 3

	- Glyph name: lessequal	Contours detected: 3	Expected: 2

	- Glyph name: greaterequal	Contours detected: 3	Expected: 2

	- Glyph name: lozenge	Contours detected: 4	Expected: 2

	- Glyph name: fi	Contours detected: 5	Expected: 1, 2or3

	- Glyph name: fl	Contours detected: 4	Expected: 1or2

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: AE	Contours detected: 6	Expected: 2

	- Glyph name: AEacute	Contours detected: 7	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2or3

	- Glyph name: Aring	Contours detected: 5	Expected: 3or4

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4or5

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 4	Expected: 2

	- Glyph name: E	Contours detected: 4	Expected: 1

	- Glyph name: Eacute	Contours detected: 5	Expected: 2

	- Glyph name: Ebreve	Contours detected: 5	Expected: 2

	- Glyph name: Ecaron	Contours detected: 5	Expected: 2

	- Glyph name: Ecircumflex	Contours detected: 5	Expected: 2

	- Glyph name: Edieresis	Contours detected: 6	Expected: 3

	- Glyph name: Edotaccent	Contours detected: 5	Expected: 2

	- Glyph name: Egrave	Contours detected: 5	Expected: 2

	- Glyph name: Emacron	Contours detected: 5	Expected: 2

	- Glyph name: Eng	Contours detected: 3	Expected: 1

	- Glyph name: Eogonek	Contours detected: 5	Expected: 1or2

	- Glyph name: Eth	Contours detected: 4	Expected: 2

	- Glyph name: Euro	Contours detected: 5	Expected: 1or2

	- Glyph name: F	Contours detected: 3	Expected: 1

	- Glyph name: G	Contours detected: 2	Expected: 1

	- Glyph name: Gbreve	Contours detected: 3	Expected: 2

	- Glyph name: Gcaron	Contours detected: 3	Expected: 2

	- Glyph name: Gcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Gdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 3	Expected: 1

	- Glyph name: Hbar	Contours detected: 4	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: K	Contours detected: 3	Expected: 1or2

	- Glyph name: L	Contours detected: 2	Expected: 1

	- Glyph name: Lacute	Contours detected: 3	Expected: 2

	- Glyph name: Lcaron	Contours detected: 3	Expected: 2

	- Glyph name: Ldot	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 4	Expected: 1

	- Glyph name: M	Contours detected: 4	Expected: 1

	- Glyph name: N	Contours detected: 3	Expected: 1

	- Glyph name: Nacute	Contours detected: 4	Expected: 2

	- Glyph name: Ncaron	Contours detected: 4	Expected: 2

	- Glyph name: Ntilde	Contours detected: 4	Expected: 2

	- Glyph name: OE	Contours detected: 5	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: S	Contours detected: 3	Expected: 1

	- Glyph name: Sacute	Contours detected: 4	Expected: 2

	- Glyph name: Scaron	Contours detected: 4	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: T	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 4	Expected: 1

	- Glyph name: Tcaron	Contours detected: 3	Expected: 2

	- Glyph name: U	Contours detected: 3	Expected: 1

	- Glyph name: Uacute	Contours detected: 4	Expected: 2

	- Glyph name: Ubreve	Contours detected: 4	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Udieresis	Contours detected: 5	Expected: 3

	- Glyph name: Ugrave	Contours detected: 4	Expected: 2

	- Glyph name: Uhungarumlaut	Contours detected: 5	Expected: 3

	- Glyph name: Umacron	Contours detected: 4	Expected: 2

	- Glyph name: Uogonek	Contours detected: 4	Expected: 1

	- Glyph name: Uring	Contours detected: 5	Expected: 3

	- Glyph name: Utilde	Contours detected: 4	Expected: 2

	- Glyph name: V	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 4	Expected: 1or2

	- Glyph name: Wacute	Contours detected: 5	Expected: 2

	- Glyph name: Wcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 6	Expected: 3

	- Glyph name: Wgrave	Contours detected: 5	Expected: 2

	- Glyph name: X	Contours detected: 3	Expected: 1

	- Glyph name: Y	Contours detected: 3	Expected: 1

	- Glyph name: Yacute	Contours detected: 4	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 5	Expected: 3

	- Glyph name: Ygrave	Contours detected: 4	Expected: 2

	- Glyph name: Z	Contours detected: 3	Expected: 1

	- Glyph name: Zacute	Contours detected: 4	Expected: 2

	- Glyph name: Zcaron	Contours detected: 4	Expected: 2

	- Glyph name: Zdotaccent	Contours detected: 4	Expected: 2

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: asciicircum	Contours detected: 2	Expected: 1

	- Glyph name: asterisk	Contours detected: 8	Expected: 1or4

	- Glyph name: braceleft	Contours detected: 2	Expected: 1

	- Glyph name: braceright	Contours detected: 2	Expected: 1

	- Glyph name: bracketleft	Contours detected: 3	Expected: 1

	- Glyph name: bracketright	Contours detected: 3	Expected: 1

	- Glyph name: cent	Contours detected: 3	Expected: 1or2

	- Glyph name: currency	Contours detected: 6	Expected: 2

	- Glyph name: dagger	Contours detected: 3	Expected: 1or2

	- Glyph name: daggerdbl	Contours detected: 5	Expected: 1or3

	- Glyph name: dcroat	Contours detected: 4	Expected: 2

	- Glyph name: eight	Contours detected: 1	Expected: 3

	- Glyph name: emptyset	Contours detected: 5	Expected: 3

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: eth	Contours detected: 4	Expected: 2

	- Glyph name: f	Contours detected: 3	Expected: 1

	- Glyph name: fi	Contours detected: 5	Expected: 3

	- Glyph name: five	Contours detected: 3	Expected: 1

	- Glyph name: fl	Contours detected: 4	Expected: 2

	- Glyph name: four	Contours detected: 3	Expected: 1or2

	- Glyph name: germandbls	Contours detected: 4	Expected: 1

	- Glyph name: greater	Contours detected: 2	Expected: 1

	- Glyph name: greaterequal	Contours detected: 3	Expected: 2

	- Glyph name: guillemotleft	Contours detected: 4	Expected: 2

	- Glyph name: guillemotright	Contours detected: 4	Expected: 2

	- Glyph name: guilsinglleft	Contours detected: 2	Expected: 1

	- Glyph name: guilsinglright	Contours detected: 2	Expected: 1

	- Glyph name: h	Contours detected: 2	Expected: 1

	- Glyph name: hbar	Contours detected: 4	Expected: 1

	- Glyph name: hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ij	Contours detected: 5	Expected: 3or4

	- Glyph name: infinity	Contours detected: 1	Expected: 3

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: k	Contours detected: 3	Expected: 1or2

	- Glyph name: kgreenlandic	Contours detected: 3	Expected: 1or2

	- Glyph name: less	Contours detected: 2	Expected: 1

	- Glyph name: lessequal	Contours detected: 3	Expected: 2

	- Glyph name: logicalnot	Contours detected: 2	Expected: 1

	- Glyph name: lozenge	Contours detected: 4	Expected: 2

	- Glyph name: lslash	Contours detected: 3	Expected: 1

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: multiply	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: numbersign	Contours detected: 8	Expected: 2

	- Glyph name: oe	Contours detected: 5	Expected: 3

	- Glyph name: one	Contours detected: 2	Expected: 1

	- Glyph name: onehalf	Contours detected: 5	Expected: 3

	- Glyph name: onequarter	Contours detected: 6	Expected: 3or4

	- Glyph name: pi	Contours detected: 3	Expected: 1

	- Glyph name: plus	Contours detected: 3	Expected: 1

	- Glyph name: plusminus	Contours detected: 4	Expected: 1or2

	- Glyph name: product	Contours detected: 3	Expected: 1

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: radical	Contours detected: 3	Expected: 1

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: registered	Contours detected: 5	Expected: 3or4

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: section	Contours detected: 3	Expected: 2

	- Glyph name: seven	Contours detected: 2	Expected: 1

	- Glyph name: sterling	Contours detected: 4	Expected: 1or2

	- Glyph name: summation	Contours detected: 4	Expected: 1

	- Glyph name: t	Contours detected: 3	Expected: 1

	- Glyph name: tbar	Contours detected: 5	Expected: 1

	- Glyph name: tcaron	Contours detected: 4	Expected: 2

	- Glyph name: three	Contours detected: 2	Expected: 1

	- Glyph name: threequarters	Contours detected: 6	Expected: 3or4

	- Glyph name: trademark	Contours detected: 6	Expected: 2

	- Glyph name: two	Contours detected: 2	Expected: 1

	- Glyph name: u	Contours detected: 2	Expected: 1

	- Glyph name: uacute	Contours detected: 3	Expected: 2

	- Glyph name: ubreve	Contours detected: 3	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: udieresis	Contours detected: 4	Expected: 3

	- Glyph name: ugrave	Contours detected: 3	Expected: 2

	- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: umacron	Contours detected: 3	Expected: 2

	- Glyph name: uni00B5	Contours detected: 3	Expected: 1

	- Glyph name: uni0122	Contours detected: 3	Expected: 2

	- Glyph name: uni0136	Contours detected: 4	Expected: 2or3

	- Glyph name: uni0137	Contours detected: 4	Expected: 2or3

	- Glyph name: uni013B	Contours detected: 3	Expected: 2

	- Glyph name: uni0145	Contours detected: 4	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: uni0162	Contours detected: 3	Expected: 1or2

	- Glyph name: uni0163	Contours detected: 4	Expected: 1or2

	- Glyph name: uni019D	Contours detected: 3	Expected: 1

	- Glyph name: uni0218	Contours detected: 4	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni021A	Contours detected: 3	Expected: 2

	- Glyph name: uni021B	Contours detected: 4	Expected: 2

	- Glyph name: uni0232	Contours detected: 4	Expected: 2

	- Glyph name: uni0233	Contours detected: 4	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni0394	Contours detected: 3	Expected: 2

	- Glyph name: uni03A9	Contours detected: 3	Expected: 1

	- Glyph name: uni03BC	Contours detected: 3	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E14	Contours detected: 6	Expected: 3

	- Glyph name: uni1E16	Contours detected: 6	Expected: 3

	- Glyph name: uni1E1C	Contours detected: 6	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E20	Contours detected: 3	Expected: 2

	- Glyph name: uni1E24	Contours detected: 4	Expected: 2

	- Glyph name: uni1E25	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 4	Expected: 2

	- Glyph name: uni1E2B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E36	Contours detected: 3	Expected: 2

	- Glyph name: uni1E3A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E42	Contours detected: 5	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E44	Contours detected: 4	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E46	Contours detected: 4	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: uni1E48	Contours detected: 4	Expected: 2

	- Glyph name: uni1E49	Contours detected: 3	Expected: 2

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: uni1E5B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E5E	Contours detected: 4	Expected: 3

	- Glyph name: uni1E5F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E60	Contours detected: 4	Expected: 2

	- Glyph name: uni1E61	Contours detected: 3	Expected: 2

	- Glyph name: uni1E62	Contours detected: 4	Expected: 2

	- Glyph name: uni1E63	Contours detected: 3	Expected: 2

	- Glyph name: uni1E64	Contours detected: 5	Expected: 3

	- Glyph name: uni1E65	Contours detected: 4	Expected: 3

	- Glyph name: uni1E66	Contours detected: 5	Expected: 3

	- Glyph name: uni1E67	Contours detected: 4	Expected: 3

	- Glyph name: uni1E68	Contours detected: 5	Expected: 3

	- Glyph name: uni1E69	Contours detected: 4	Expected: 3

	- Glyph name: uni1E6C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E6D	Contours detected: 4	Expected: 2

	- Glyph name: uni1E6E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E6F	Contours detected: 4	Expected: 2

	- Glyph name: uni1E78	Contours detected: 5	Expected: 3

	- Glyph name: uni1E79	Contours detected: 4	Expected: 3

	- Glyph name: uni1E7A	Contours detected: 6	Expected: 4

	- Glyph name: uni1E7B	Contours detected: 5	Expected: 4

	- Glyph name: uni1E8E	Contours detected: 4	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 4	Expected: 2

	- Glyph name: uni1E92	Contours detected: 4	Expected: 2

	- Glyph name: uni1E93	Contours detected: 4	Expected: 2

	- Glyph name: uni1E97	Contours detected: 5	Expected: 3

	- Glyph name: uni1E9E	Contours detected: 4	Expected: 1

	- Glyph name: uni1EA0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EB8	Contours detected: 5	Expected: 2

	- Glyph name: uni1EBC	Contours detected: 5	Expected: 2

	- Glyph name: uni1EE4	Contours detected: 4	Expected: 2

	- Glyph name: uni1EE5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 4	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 4	Expected: 2

	- Glyph name: uni2116	Contours detected: 6	Expected: 3or4

	- Glyph name: uni2126	Contours detected: 3	Expected: 1

	- Glyph name: uni2206	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 3	Expected: 1

	- Glyph name: uring	Contours detected: 4	Expected: 3

	- Glyph name: utilde	Contours detected: 3	Expected: 2

	- Glyph name: v	Contours detected: 2	Expected: 1

	- Glyph name: w	Contours detected: 5	Expected: 1

	- Glyph name: wacute	Contours detected: 6	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 6	Expected: 2

	- Glyph name: wdieresis	Contours detected: 7	Expected: 3

	- Glyph name: wgrave	Contours detected: 6	Expected: 2

	- Glyph name: x	Contours detected: 3	Expected: 1

	- Glyph name: y	Contours detected: 3	Expected: 1

	- Glyph name: yacute	Contours detected: 4	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 4	Expected: 2

	- Glyph name: ydieresis	Contours detected: 5	Expected: 3

	- Glyph name: yen	Contours detected: 6	Expected: 1or2

	- Glyph name: ygrave	Contours detected: 4	Expected: 2

	- Glyph name: z	Contours detected: 3	Expected: 1

	- Glyph name: zacute	Contours detected: 4	Expected: 2

	- Glyph name: zcaron	Contours detected: 4	Expected: 2

	- Glyph name: zdotaccent	Contours detected: 4	Expected: 2
 [code: contour-count]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 2 | 4 | 121 | 7 | 116 | 0 |
| 0% | 1% | 2% | 48% | 3% | 46% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**

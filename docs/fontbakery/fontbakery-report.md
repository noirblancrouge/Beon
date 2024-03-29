## FontBakery report

fontbakery version: 0.10.2

<details><summary><b>[6] Beon-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Familyname must be unique according to namecheck.fontdata.com (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontdata_namecheck">com.google.fonts/check/fontdata_namecheck</a>)</summary><div>


* 💔 **ERROR** Failed to access: http://namecheck.fontdata.com.
		This check relies on the external service http://namecheck.fontdata.com via the internet. While the service cannot be reached or does not respond this check is broken.

		You can exclude this check with the command line option:
		-x com.google.fonts/check/fontdata_namecheck

		Or you can wait until the service is available again.
		If the problem persists please report this issue at: https://github.com/fonttools/fontbakery/issues

		Original error message:
		<class 'requests.exceptions.ConnectionError'> [code: namecheck-service]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.2, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02CC MODIFIER LETTER LOW VERTICAL LINE: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, math, canadian-aboriginal, coptic, tifinagh, malayalam, tai-le, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032E COMBINING BREVE BELOW: try adding syriac
 * U+0330 COMBINING TILDE BELOW: try adding one of: syriac, cherokee, math
 * U+0331 COMBINING MACRON BELOW: try adding one of: caucasian-albanian, syriac, cherokee, tifinagh, gothic
 * U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: greek, elbasan, math
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: greek, elbasan, math
 * U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, yi, math
 * U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: sora-sompeng, yi, sundanese, kharoshthi, lisu, kaithi, cham, syloti-nagri, coptic, kayah-li
 * U+2012 FIGURE DASH: not included in any glyphset definition
 * U+2015 HORIZONTAL BAR: try adding adlam
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+2080 SUBSCRIPT ZERO: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CA LOZENGE: try adding one of: symbols, math
 * U+25CC DOTTED CIRCLE: try adding one of: ahom, pahawh-hmong, miao, lepcha, javanese, math, wancho, adlam, tibetan, soyombo, sharada, music, gurmukhi, hanifi-rohingya, meetei-mayek, grantha, tamil, malayalam, buhid, takri, tai-viet, thai, oriya, newa, mandaic, gunjala-gondi, hanunoo, kharoshthi, mende-kikakui, marchen, symbols, zanabazar-square, old-permic, brahmi, mongolian, osage, siddham, modi, nko, manichaean, sundanese, thaana, mahajani, syloti-nagri, tifinagh, batak, rejang, yi, buginese, balinese, limbu, kayah-li, gujarati, hebrew, duployan, khojki, bassa-vah, tirhuta, tagbanwa, psalter-pahlavi, bhaiksuki, coptic, devanagari, bengali, phags-pa, lao, telugu, masaram-gondi, cham, tai-le, elbasan, kaithi, sinhala, caucasian-albanian, myanmar, new-tai-lue, syriac, chakma, sogdian, tagalog, khmer, dogra, kannada, khudawadi
 * U+E133 : not included in any glyphset definition
 * U+E134 : not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: numbersign	Contours detected: 8	Expected: 2

	- Glyph name: asterisk	Contours detected: 8	Expected: 1 or 4

	- Glyph name: plus	Contours detected: 3	Expected: 1

	- Glyph name: one	Contours detected: 2	Expected: 1

	- Glyph name: two	Contours detected: 2	Expected: 1

	- Glyph name: three	Contours detected: 2	Expected: 1

	- Glyph name: four	Contours detected: 3	Expected: 1 or 2

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

	- Glyph name: K	Contours detected: 3	Expected: 1 or 2

	- Glyph name: L	Contours detected: 2	Expected: 1

	- Glyph name: M	Contours detected: 4	Expected: 1

	- Glyph name: N	Contours detected: 3	Expected: 1

	- Glyph name: R	Contours detected: 3	Expected: 1 or 2

	- Glyph name: S	Contours detected: 3	Expected: 1

	- Glyph name: T	Contours detected: 2	Expected: 1

	- Glyph name: U	Contours detected: 3	Expected: 1

	- Glyph name: V	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 4	Expected: 1 or 2

	- Glyph name: X	Contours detected: 3	Expected: 1

	- Glyph name: Y	Contours detected: 3	Expected: 1

	- Glyph name: Z	Contours detected: 3	Expected: 1

	- Glyph name: bracketleft	Contours detected: 3	Expected: 1

	- Glyph name: bracketright	Contours detected: 3	Expected: 1

	- Glyph name: asciicircum	Contours detected: 2	Expected: 1

	- Glyph name: f	Contours detected: 3	Expected: 1

	- Glyph name: h	Contours detected: 2	Expected: 1

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: k	Contours detected: 3	Expected: 1 or 2

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

	- Glyph name: cent	Contours detected: 3	Expected: 1 or 2

	- Glyph name: sterling	Contours detected: 4	Expected: 1 or 2

	- Glyph name: currency	Contours detected: 6	Expected: 2

	- Glyph name: yen	Contours detected: 6	Expected: 1 or 2

	- Glyph name: section	Contours detected: 3	Expected: 2

	- Glyph name: guillemotleft	Contours detected: 4	Expected: 2

	- Glyph name: logicalnot	Contours detected: 2	Expected: 1

	- Glyph name: registered	Contours detected: 5	Expected: 3 or 4

	- Glyph name: plusminus	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni00B2	Contours detected: 2	Expected: 1

	- Glyph name: uni00B3	Contours detected: 2	Expected: 1

	- Glyph name: uni00B5	Contours detected: 3	Expected: 1

	- Glyph name: uni00B9	Contours detected: 2	Expected: 1

	- Glyph name: guillemotright	Contours detected: 4	Expected: 2

	- Glyph name: onequarter	Contours detected: 6	Expected: 3 or 4

	- Glyph name: onehalf	Contours detected: 5	Expected: 3

	- Glyph name: threequarters	Contours detected: 6	Expected: 3 or 4

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Aring	Contours detected: 5	Expected: 3 or 4

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

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2 or 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 4	Expected: 2

	- Glyph name: dcroat	Contours detected: 4	Expected: 2

	- Glyph name: Emacron	Contours detected: 5	Expected: 2

	- Glyph name: Ebreve	Contours detected: 5	Expected: 2

	- Glyph name: Edotaccent	Contours detected: 5	Expected: 2

	- Glyph name: Eogonek	Contours detected: 5	Expected: 1 or 2

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

	- Glyph name: IJ	Contours detected: 3	Expected: 1 or 2

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: uni0136	Contours detected: 4	Expected: 2 or 3

	- Glyph name: uni0137	Contours detected: 4	Expected: 2 or 3

	- Glyph name: kgreenlandic	Contours detected: 3	Expected: 1 or 2

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

	- Glyph name: Scedilla	Contours detected: 4	Expected: 1 or 2

	- Glyph name: scedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Scaron	Contours detected: 4	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: uni0162	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0163	Contours detected: 4	Expected: 1 or 2

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

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4 or 5

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

	- Glyph name: dagger	Contours detected: 3	Expected: 1 or 2

	- Glyph name: daggerdbl	Contours detected: 5	Expected: 1 or 3

	- Glyph name: guilsinglleft	Contours detected: 2	Expected: 1

	- Glyph name: guilsinglright	Contours detected: 2	Expected: 1

	- Glyph name: uni2074	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni2075	Contours detected: 3	Expected: 1

	- Glyph name: uni2077	Contours detected: 2	Expected: 1

	- Glyph name: uni2078	Contours detected: 1	Expected: 3

	- Glyph name: uni2081	Contours detected: 2	Expected: 1

	- Glyph name: uni2082	Contours detected: 2	Expected: 1

	- Glyph name: uni2083	Contours detected: 2	Expected: 1

	- Glyph name: uni2084	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni2085	Contours detected: 3	Expected: 1

	- Glyph name: uni2087	Contours detected: 2	Expected: 1

	- Glyph name: uni2088	Contours detected: 1	Expected: 3

	- Glyph name: Euro	Contours detected: 5	Expected: 1 or 2

	- Glyph name: uni2116	Contours detected: 6	Expected: 3 or 4

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

	- Glyph name: fi	Contours detected: 5	Expected: 1, 2 or 3

	- Glyph name: fl	Contours detected: 4	Expected: 1 or 2

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: AE	Contours detected: 6	Expected: 2

	- Glyph name: AEacute	Contours detected: 7	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2 or 3

	- Glyph name: Aring	Contours detected: 5	Expected: 3 or 4

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4 or 5

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

	- Glyph name: Eogonek	Contours detected: 5	Expected: 1 or 2

	- Glyph name: Eth	Contours detected: 4	Expected: 2

	- Glyph name: Euro	Contours detected: 5	Expected: 1 or 2

	- Glyph name: F	Contours detected: 3	Expected: 1

	- Glyph name: G	Contours detected: 2	Expected: 1

	- Glyph name: Gbreve	Contours detected: 3	Expected: 2

	- Glyph name: Gcaron	Contours detected: 3	Expected: 2

	- Glyph name: Gcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Gdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 3	Expected: 1

	- Glyph name: Hbar	Contours detected: 4	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1 or 2

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: K	Contours detected: 3	Expected: 1 or 2

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

	- Glyph name: R	Contours detected: 3	Expected: 1 or 2

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

	- Glyph name: W	Contours detected: 4	Expected: 1 or 2

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

	- Glyph name: asterisk	Contours detected: 8	Expected: 1 or 4

	- Glyph name: braceleft	Contours detected: 2	Expected: 1

	- Glyph name: braceright	Contours detected: 2	Expected: 1

	- Glyph name: bracketleft	Contours detected: 3	Expected: 1

	- Glyph name: bracketright	Contours detected: 3	Expected: 1

	- Glyph name: cent	Contours detected: 3	Expected: 1 or 2

	- Glyph name: currency	Contours detected: 6	Expected: 2

	- Glyph name: dagger	Contours detected: 3	Expected: 1 or 2

	- Glyph name: daggerdbl	Contours detected: 5	Expected: 1 or 3

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

	- Glyph name: four	Contours detected: 3	Expected: 1 or 2

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

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: infinity	Contours detected: 1	Expected: 3

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: k	Contours detected: 3	Expected: 1 or 2

	- Glyph name: kgreenlandic	Contours detected: 3	Expected: 1 or 2

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

	- Glyph name: onequarter	Contours detected: 6	Expected: 3 or 4

	- Glyph name: pi	Contours detected: 3	Expected: 1

	- Glyph name: plus	Contours detected: 3	Expected: 1

	- Glyph name: plusminus	Contours detected: 4	Expected: 1 or 2

	- Glyph name: product	Contours detected: 3	Expected: 1

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: radical	Contours detected: 3	Expected: 1

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: registered	Contours detected: 5	Expected: 3 or 4

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: section	Contours detected: 3	Expected: 2

	- Glyph name: seven	Contours detected: 2	Expected: 1

	- Glyph name: sterling	Contours detected: 4	Expected: 1 or 2

	- Glyph name: summation	Contours detected: 4	Expected: 1

	- Glyph name: t	Contours detected: 3	Expected: 1

	- Glyph name: tbar	Contours detected: 5	Expected: 1

	- Glyph name: tcaron	Contours detected: 4	Expected: 2

	- Glyph name: three	Contours detected: 2	Expected: 1

	- Glyph name: threequarters	Contours detected: 6	Expected: 3 or 4

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

	- Glyph name: uni0136	Contours detected: 4	Expected: 2 or 3

	- Glyph name: uni0137	Contours detected: 4	Expected: 2 or 3

	- Glyph name: uni013B	Contours detected: 3	Expected: 2

	- Glyph name: uni0145	Contours detected: 4	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: uni0162	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0163	Contours detected: 4	Expected: 1 or 2

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

	- Glyph name: uni2116	Contours detected: 6	Expected: 3 or 4

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

	- Glyph name: yen	Contours detected: 6	Expected: 1 or 2

	- Glyph name: ygrave	Contours detected: 4	Expected: 2

	- Glyph name: z	Contours detected: 3	Expected: 1

	- Glyph name: zacute	Contours detected: 4	Expected: 2

	- Glyph name: zcaron	Contours detected: 4	Expected: 2

	- Glyph name: zdotaccent	Contours detected: 4	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* comma (U+002C): L<<136.0,24.0>--<136.0,23.0>> -> L<<136.0,23.0>--<136.0,22.0>>

	* semicolon (U+003B): L<<136.0,24.0>--<136.0,23.0>> -> L<<136.0,23.0>--<136.0,22.0>>

	* uni02BB (U+02BB): L<<54.0,906.0>--<54.0,907.0>> -> L<<54.0,907.0>--<54.0,908.0>> [code: found-colinear-vectors]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 1 | 1 | 4 | 121 | 8 | 119 | 0 |
| 0% | 0% | 2% | 48% | 3% | 47% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**

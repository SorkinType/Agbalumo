## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[13] Agbalumo-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)


	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_African is almost fulfilled. Missing codepoints:

	- 0xA7B3 (LATIN CAPITAL LETTER CHI)


	- 0x01EE (LATIN CAPITAL LETTER EZH WITH CARON)


	- 0x1E28 (LATIN CAPITAL LETTER H WITH CEDILLA)


	- 0xA726 (LATIN CAPITAL LETTER HENG)


	- 0xA740 (LATIN CAPITAL LETTER K WITH STROKE)


	- 0xA7AD (LATIN CAPITAL LETTER L WITH BELT)


	- 0x2C60 (LATIN CAPITAL LETTER L WITH DOUBLE BAR)


	- 0x2C62 (LATIN CAPITAL LETTER L WITH MIDDLE TILDE)


	- 0x0220 (LATIN CAPITAL LETTER N WITH LONG RIGHT LEG)


	- 0x0222 (LATIN CAPITAL LETTER OU)


	- 0x024A (LATIN CAPITAL LETTER SMALL Q WITH HOOK TAIL)


	- 0x1E64 (LATIN CAPITAL LETTER S WITH ACUTE AND DOT ABOVE)


	- 0x1E66 (LATIN CAPITAL LETTER S WITH CARON AND DOT ABOVE)


	- 0xA7A8 (LATIN CAPITAL LETTER S WITH OBLIQUE STROKE)


	- 0x023E (LATIN CAPITAL LETTER T WITH DIAGONAL STROKE)


	- 0x01EF (LATIN SMALL LETTER EZH WITH CARON)


	- 0x02C0 (MODIFIER LETTER GLOTTAL STOP)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Beyond is almost fulfilled. Missing codepoints:

	- 0x03BB (GREEK SMALL LETTER LAMDA)


	- 0x03C7 (GREEK SMALL LETTER CHI)


	- 0x01EE (LATIN CAPITAL LETTER EZH WITH CARON)


	- 0x2C62 (LATIN CAPITAL LETTER L WITH MIDDLE TILDE)


	- 0x023E (LATIN CAPITAL LETTER T WITH DIAGONAL STROKE)


	- 0x01EF (LATIN SMALL LETTER EZH WITH CARON)


	- 0x02C0 (MODIFIER LETTER GLOTTAL STOP)


	- 0x0166 (LATIN CAPITAL LETTER T WITH STROKE)


	- 0x01F0 (LATIN SMALL LETTER J WITH CARON)


	- 0x0138 (LATIN SMALL LETTER KRA)


	- 0x0167 (LATIN SMALL LETTER T WITH STROKE)


	- 0x02B8 (MODIFIER LETTER SMALL Y)


	- 0x1DBF (MODIFIER LETTER SMALL THETA)


	- 0x2144 (TURNED SANS-SERIF CAPITAL Y)


	- 0x0315 (COMBINING COMMA ABOVE RIGHT)


	- 0x0335 (COMBINING SHORT STROKE OVERLAY)


	- 0x02B9 (MODIFIER LETTER PRIME)


	- 0x02C8 (MODIFIER LETTER VERTICAL LINE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)


	- 0x1E97 (LATIN SMALL LETTER T WITH DIAERESIS)


	- 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition
 * U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition
 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, syriac, tifinagh, old-permic, tai-le, coptic, math, malayalam
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0324 COMBINING DIAERESIS BELOW: try adding one of: cherokee, syriac
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032E COMBINING BREVE BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: math, cherokee, syriac
 * U+0331 COMBINING MACRON BELOW: try adding one of: gothic, syriac, tifinagh, cherokee, caucasian-albanian
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai
 * U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition
 * U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition
 * U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition
 * U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition
 * U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition
 * U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition
 * U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition
 * U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition
 * U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition
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
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+215B VULGAR FRACTION ONE EIGHTH: not included in any glyphset definition
 * U+215C VULGAR FRACTION THREE EIGHTHS: not included in any glyphset definition
 * U+215D VULGAR FRACTION FIVE EIGHTHS: not included in any glyphset definition
 * U+215E VULGAR FRACTION SEVEN EIGHTHS: not included in any glyphset definition
 * U+2184 LATIN SMALL LETTER REVERSED C: not included in any glyphset definition
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CC DOTTED CIRCLE: try adding one of: buginese, tirhuta, tifinagh, sundanese, symbols, nko, manichaean, thaana, bhaiksuki, lao, kannada, gujarati, myanmar, adlam, lepcha, khudawadi, khojki, gurmukhi, soyombo, bassa-vah, buhid, pahawh-hmong, malayalam, kaithi, marchen, cham, phags-pa, caucasian-albanian, devanagari, zanabazar-square, kayah-li, mahajani, hanunoo, limbu, sharada, tibetan, coptic, brahmi, masaram-gondi, psalter-pahlavi, wancho, yi, hebrew, mende-kikakui, sinhala, mandaic, newa, syloti-nagri, bengali, gunjala-gondi, tai-viet, hanifi-rohingya, syriac, balinese, ahom, javanese, new-tai-lue, siddham, tai-le, miao, osage, oriya, tamil, telugu, kharoshthi, modi, mongolian, tagalog, thai, chakma, khmer, old-permic, duployan, takri, sogdian, batak, tagbanwa, rejang, math, dogra, grantha, elbasan, meetei-mayek, music
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- M_gravecomb

	- a.alt2

	- a.alt5

	- acutecomb.narrow

	- ampersand.001

	- ampersand.003

	- ampersand.004

	- ampersand.005

	- ampersand.006

	- ampersand.007

	- capslash_part.

	- dotbelowcomb.case.001

	- gravecomb.narrow

	- hookabovecomb.narrow

	- lcslash_part.

	- m_gravecomb

	- tildecomb.narrow

	- uni004D0304

	- uni004E0304

	- uni006D0304

	- uni006E0304

	- uni0302.narrow

	- uni0306.narrow

	- uni031B.narrow
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B4	Contours detected: 2	Expected: 1

	- Glyph name: uni01E2	Contours detected: 4	Expected: 3

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni01F5	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni023A	Contours detected: 2	Expected: 3

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni024E	Contours detected: 1	Expected: 2

	- Glyph name: uni024F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 20	Expected: 16 or 12

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni01B4	Contours detected: 2	Expected: 1

	- Glyph name: uni01E2	Contours detected: 4	Expected: 3

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni023A	Contours detected: 2	Expected: 3

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni024E	Contours detected: 1	Expected: 2

	- Glyph name: uni024F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 20	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: ygrave	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 556 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 554:
plus

Width = 515:
less

Width = 535:
greater

Width = 565:
logicalnot

Width = 579:
plusminus

Width = 541:
multiply

Width = 548:
minus, divide

Width = 546:
approxequal

Width = 502:
lessequal

Width = 506:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Eng (U+014A): B<<392.5,483.0>-<431.0,369.0>-<454.0,212.0>>/L<<454.0,212.0>--<458.0,292.0>> = 11.196769743469542

	* h (U+0068): B<<255.0,432.0>-<244.0,386.0>-<233.0,346.0>>/B<<233.0,346.0>-<252.0,383.0>-<283.5,419.5>> = 11.804859836651074

	* hbar (U+0127): B<<254.5,418.5>-<245.0,379.0>-<237.0,346.0>>/B<<237.0,346.0>-<256.0,383.0>-<287.5,419.5>> = 13.554116225585668

	* hcircumflex (U+0125): B<<255.0,432.0>-<244.0,386.0>-<233.0,346.0>>/B<<233.0,346.0>-<252.0,383.0>-<283.5,419.5>> = 11.804859836651074

	* ordfeminine (U+00AA): B<<226.0,293.5>-<226.0,297.0>-<227.0,301.0>>/B<<227.0,301.0>-<206.0,258.0>-<178.5,237.5>> = 11.993348723586983

	* uni021F (U+021F): B<<255.0,432.0>-<244.0,386.0>-<233.0,346.0>>/B<<233.0,346.0>-<252.0,383.0>-<283.5,419.5>> = 11.804859836651074

	* uni0265 (U+0265): B<<322.5,68.0>-<334.0,114.0>-<344.0,154.0>>/B<<344.0,154.0>-<325.0,117.0>-<293.5,80.5>> = 13.144867617550734

	* uni02B0 (U+02B0): B<<207.0,529.0>-<198.0,496.0>-<189.0,467.0>>/B<<189.0,467.0>-<205.0,494.0>-<232.5,520.5>> = 13.409208558112896

	* uni1E23 (U+1E23): B<<255.0,432.0>-<244.0,386.0>-<233.0,346.0>>/B<<233.0,346.0>-<252.0,383.0>-<283.5,419.5>> = 11.804859836651074

	* uni1E25 (U+1E25): B<<255.0,432.0>-<244.0,386.0>-<233.0,346.0>>/B<<233.0,346.0>-<252.0,383.0>-<283.5,419.5>> = 11.804859836651074

	* uni1E27 (U+1E27): B<<255.0,432.0>-<244.0,386.0>-<233.0,346.0>>/B<<233.0,346.0>-<252.0,383.0>-<283.5,419.5>> = 11.804859836651074

	* uni1E29 (U+1E29): B<<255.0,432.0>-<244.0,386.0>-<233.0,346.0>>/B<<233.0,346.0>-<252.0,383.0>-<283.5,419.5>> = 11.804859836651074

	* uni1E2B (U+1E2B): B<<255.0,432.0>-<244.0,386.0>-<233.0,346.0>>/B<<233.0,346.0>-<252.0,383.0>-<283.5,419.5>> = 11.804859836651074

	* uniA727 (U+A727): B<<255.0,432.0>-<244.0,386.0>-<233.0,346.0>>/B<<233.0,346.0>-<252.0,383.0>-<283.5,419.5>> = 11.804859836651074

	* uniA7B9 (U+A7B9): B<<255.5,327.5>-<244.0,280.0>-<236.0,236.0>>/B<<236.0,236.0>-<267.0,317.0>-<299.0,387.5>> = 10.63780408122225 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* summation (U+2211): L<<412.0,564.0>--<247.0,563.0>>

	* uni01A9 (U+01A9): L<<408.0,574.0>--<230.0,573.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 3 | 0 | 10 | 120 | 6 | 110 | 0 |
| 1% | 0% | 4% | 48% | 2% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**

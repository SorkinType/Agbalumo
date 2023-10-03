## Fontbakery report

Fontbakery version: 0.8.11

<details><summary><b>[17] Agbalumo-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Agbalumo Regular | Agbalumo |
| Subfamily Name | Italic | Regular |
| Full Name | Agbalumo Regular | Agbalumo Regular |
| Poscript Name | Agbalumo-Regular | Agbalumo-Regular |
| Typographic Family Name | Agbalumo | N/A |
| Typographic Subfamily Name | Regular | N/A | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1180 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1163, but got 1150 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030D

	- uni030F

	- uni0310

	- uni0311

	- uni0312

	- uni0313

	- uni031B

	- uni0324

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni0329

	- uni032D

	- uni032E

	- uni032F

	- uni0330

	- uni0331

	- uni0332

	- uni1DC4

	- uni1DC5

	- uni1DC6

	- uni1DC7 

	- uni1DCA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i᷆ i᷇ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i᷄ i᷅ i̛᷄ i̛᷅ i̛᷆ i̛᷇ i̤᷄ i̤᷅ i̤᷆ i̤᷇ i̥᷄ i̥᷅ i̥᷆ i̥᷇ i̦᷄ i̦᷅ i̦᷆ i̦᷇ i̧᷄ i̧᷅ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking head.macStyle value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/mac_style">com.google.fonts/check/mac_style</a>)</summary><div>


* 🔥 **FAIL** head macStyle ITALIC bit should be unset. [code: bad-ITALIC]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsSelection value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/fsselection">com.google.fonts/check/fsselection</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection REGULAR bit should be set. [code: bad-REGULAR]
* 🔥 **FAIL** OS/2 fsSelection ITALIC bit should be unset. [code: bad-ITALIC]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
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
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
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
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 9 | 8 | 118 | 7 | 100 | 0 |
| 0% | 4% | 3% | 49% | 3% | 41% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**

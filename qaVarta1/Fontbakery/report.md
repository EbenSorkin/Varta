## Fontbakery report

Fontbakery version: 0.7.10

<details>
<summary><b>[2] Family checks</b></summary>
<details>
<summary>🔥 <b>FAIL:</b> All tabular figures must have the same width across the RIBBI-family.</summary>

* [com.google.fonts/check/family/tnum_horizontal_metrics](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/family/tnum_horizontal_metrics)
* 🔥 **FAIL** The most common tabular glyph width is 1042. But there are other tabular glyphs with different widths such as the following ones:
	{1017: ['zero.tnum', 'one.tnum', 'two.tnum', 'three.tnum', 'four.tnum', 'five.tnum', 'six.tnum', 'seven.tnum', 'eight.tnum', 'nine.tnum']}. [code: inconsistent-widths]

</details>
<details>
<summary>⚠ <b>WARN:</b> Is the command `ftxvalidator` (Apple Font Tool Suite) available?</summary>

* [com.google.fonts/check/ftxvalidator_is_available](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/ftxvalidator_is_available)
* ⚠ **WARN** ftxvalidator is not available.

</details>
<br>
</details>
<details>
<summary><b>[10] Varta-Bold.ttf</b></summary>
<details>
<summary>🔥 <b>FAIL:</b> Check glyph coverage.</summary>

* [com.google.fonts/check/glyph_coverage](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage)
* 🔥 **FAIL** Missing required codepoints: 0x000D (CARRIAGE RETURN) [code: missing-codepoints]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Substitute copyright, registered and trademark symbols in name table entries.</summary>

* [com.google.fonts/check/name/unwanted_chars](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/unwanted_chars)
* 🔥 **FAIL** NAMEID #0 contains symbols that should be replaced by '(c)'. [code: unwanted-chars]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Are there non-ASCII characters in ASCII-only NAME table entries?</summary>

* [com.google.fonts/check/name/ascii_only_entries](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/ascii_only_entries)
* 🔥 **FAIL** There are 1 strings containing non-ASCII characters in the ASCII-only NAME table entries. [code: non-ascii-strings]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts</summary>

* [com.google.fonts/check/font_copyright](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright)
* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright © 2014 by Joana Correia, Viktoriya Grabowska, Eben Sorkin. All rights reserved." [code: bad-notice-format]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Does the font have a DSIG table?</summary>

* [com.google.fonts/check/dsig](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/dsig.html#com.google.fonts/check/dsig)
* 🔥 **FAIL** This font lacks a digital signature (DSIG table). Some applications may require one (even if only a dummy placeholder) in order to work properly. You can add a DSIG table by running the `gftools fix-dsig` script.

</details>
<details>
<summary>⚠ <b>WARN:</b> Font has old ttfautohint applied?</summary>

* [com.google.fonts/check/old_ttfautohint](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint)
* ⚠ **WARN** ttfautohint used in font = 1.3; installed = 1.8.2; Need to re-run with the newer version! [code: old-ttfa]

</details>
<details>
<summary>⚠ <b>WARN:</b> Stricter unitsPerEm criteria for Google Fonts. </summary>

* [com.google.fonts/check/unitsperem_strict](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict)
* ⚠ **WARN** Even though unitsPerEm (2048) in this font is reasonable. It is strongly advised to consider changing it to 2000, since it will likely improve the quality of Variable Fonts by avoiding excessive rounding of coordinates on interpolations. [code: legacy-value]

</details>
<details>
<summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary>

* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/contour_count)
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

Glyph name: uni20A8	Contours detected: 1	Expected: 3
Glyph name: uni0218	Contours detected: 1	Expected: 2
Glyph name: uni0904	Contours detected: 2	Expected: 1
Glyph name: uni090E	Contours detected: 2	Expected: 1
Glyph name: uni0910	Contours detected: 2	Expected: 1
Glyph name: uni0912	Contours detected: 2	Expected: 1
Glyph name: uni0913	Contours detected: 2	Expected: 1
Glyph name: uni0914	Contours detected: 2	Expected: 1
Glyph name: uni0916	Contours detected: 2	Expected: 1 or 3
Glyph name: uni1EAC	Contours detected: 3	Expected: 4
Glyph name: uni1EB6	Contours detected: 3	Expected: 4
Glyph name: uni094B	Contours detected: 2	Expected: 1
Glyph name: uni1ECB	Contours detected: 2	Expected: 3
Glyph name: uni0950	Contours detected: 4	Expected: 3
Glyph name: uni1ED8	Contours detected: 3	Expected: 4
Glyph name: uni0959	Contours detected: 3	Expected: 2 or 4
Glyph name: uni0967	Contours detected: 2	Expected: 1 [code: contour-count]

</details>
<details>
<summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature?</summary>

* [com.google.fonts/check/ligature_carets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets)
* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]

</details>
<details>
<summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences?</summary>

* [com.google.fonts/check/kerning_for_non_ligated_sequences](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences)
* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- uni0915 + uni0930094D.1
	- uni0930094D.1 + uni0930094D0902
	- uni0916 + uni0930094D.1
	- uni0917 + uni0930094D.1
	- uni0918 + uni0930094D.1
	- uni0919 + uni0930094D.1
	- uni091A + uni0930094D.1
	- uni091B + uni0930094D.1
	- uni091C + uni0930094D.1
	- uni091D + uni0930094D.1
	- uni091E + uni0930094D.1
	- uni091F + uni0930094D.1
	- uni0920 + uni0930094D.1
	- uni0921 + uni0930094D.1
	- uni0922 + uni0930094D.1
	- uni0923 + uni0930094D.1
	- uni0924 + uni0930094D.1
	- uni0925 + uni0930094D.1
	- uni0926 + uni0930094D.1
	- uni0927 + uni0930094D.1
	- uni0928 + uni0930094D.1
	- uni0929 + uni0930094D.1
	- uni092A + uni0930094D.1
	- uni092B + uni0930094D.1
	- uni092C + uni0930094D.1
	- uni092D + uni0930094D.1
	- uni092E + uni0930094D.1
	- uni092F + uni0930094D.1
	- uni0930 + uni0930094D.1
	- uni0931 + uni0930094D.1
	- uni0932 + uni0930094D.1
	- uni0933 + uni0930094D.1
	- uni0934 + uni0930094D.1
	- uni0935 + uni0930094D.1
	- uni0936 + uni0930094D.1
	- uni0937 + uni0930094D.1
	- uni0938 + uni0930094D.1
	- uni0939 + uni0930094D.1
	- uni0958 + uni0930094D.1
	- uni0959 + uni0930094D.1
	- uni095A + uni0930094D.1
	- uni095B + uni0930094D.1
	- uni095C + uni0930094D.1
	- uni095D + uni0930094D.1
	- uni095E + uni0930094D.1
	- uni095F + uni0930094D.1
	- uni0979 + uni0930094D.1
	- uni097A + uni0930094D.1
	- uni097B + uni0930094D.1
	- uni097C + uni0930094D.1
	- uni097E + uni0930094D.1
	- uni097F + uni0930094D.1
	- uni0932.loclMAR + uni0930094D.1
	- uni0936.loclMAR + uni0930094D.1
	- uni091D.np + uni0930094D.1
	- uni0979.np + uni0930094D.1
	- uni092F.post + uni0930094D.1
	- uni0935.post + uni0930094D.1
	- uni0928.post2 + uni0930094D.1
	- uni0936.ss02 + uni0930094D.1

   [code: lacks-kern-info]

</details>
<br>
</details>
<details>
<summary><b>[10] Varta-Light.ttf</b></summary>
<details>
<summary>🔥 <b>FAIL:</b> Check glyph coverage.</summary>

* [com.google.fonts/check/glyph_coverage](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage)
* 🔥 **FAIL** Missing required codepoints: 0x000D (CARRIAGE RETURN) [code: missing-codepoints]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts</summary>

* [com.google.fonts/check/font_copyright](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright)
* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright (c) 2014-2015, Sorkin Type Co (sorkintype.com | sorkintype@gmail.com)" [code: bad-notice-format]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Check name table: FONT_FAMILY_NAME entries. </summary>

* [com.google.fonts/check/name/familyname](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/familyname)
* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "Varta Light" but got "Varta". [code: mismatch]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Check name table: FONT_SUBFAMILY_NAME entries. </summary>

* [com.google.fonts/check/name/subfamilyname](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/subfamilyname)
* 🔥 **FAIL** SUBFAMILY_NAME for Win "Light" must be "Regular" [code: bad-familyname]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Does the font have a DSIG table?</summary>

* [com.google.fonts/check/dsig](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/dsig.html#com.google.fonts/check/dsig)
* 🔥 **FAIL** This font lacks a digital signature (DSIG table). Some applications may require one (even if only a dummy placeholder) in order to work properly. You can add a DSIG table by running the `gftools fix-dsig` script.

</details>
<details>
<summary>⚠ <b>WARN:</b> Font has old ttfautohint applied?</summary>

* [com.google.fonts/check/old_ttfautohint](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint)
* ⚠ **WARN** ttfautohint used in font = 1.3; installed = 1.8.2; Need to re-run with the newer version! [code: old-ttfa]

</details>
<details>
<summary>⚠ <b>WARN:</b> Stricter unitsPerEm criteria for Google Fonts. </summary>

* [com.google.fonts/check/unitsperem_strict](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict)
* ⚠ **WARN** Even though unitsPerEm (2048) in this font is reasonable. It is strongly advised to consider changing it to 2000, since it will likely improve the quality of Variable Fonts by avoiding excessive rounding of coordinates on interpolations. [code: legacy-value]

</details>
<details>
<summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary>

* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/contour_count)
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

Glyph name: uni20A8	Contours detected: 1	Expected: 3
Glyph name: uni0122	Contours detected: 1	Expected: 2
Glyph name: uni013B	Contours detected: 1	Expected: 2
Glyph name: uni0145	Contours detected: 1	Expected: 2
Glyph name: uni0156	Contours detected: 2	Expected: 3
Glyph name: uni1EE7	Contours detected: 1	Expected: 2
Glyph name: uni0904	Contours detected: 2	Expected: 1
Glyph name: uni090E	Contours detected: 2	Expected: 1
Glyph name: uni0910	Contours detected: 2	Expected: 1
Glyph name: uni0912	Contours detected: 2	Expected: 1
Glyph name: uni0913	Contours detected: 2	Expected: 1
Glyph name: uni0914	Contours detected: 2	Expected: 1
Glyph name: uni0916	Contours detected: 2	Expected: 1 or 3
Glyph name: uni1EA0	Contours detected: 2	Expected: 3
Glyph name: uni1EAC	Contours detected: 3	Expected: 4
Glyph name: uni1EB6	Contours detected: 3	Expected: 4
Glyph name: uni0950	Contours detected: 4	Expected: 3
Glyph name: uni1EDF	Contours detected: 2	Expected: 3
Glyph name: uni1EED	Contours detected: 1	Expected: 2
Glyph name: uni1EF7	Contours detected: 1	Expected: 2
Glyph name: uni0959	Contours detected: 3	Expected: 2 or 4
Glyph name: uni0967	Contours detected: 2	Expected: 1 [code: contour-count]

</details>
<details>
<summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature?</summary>

* [com.google.fonts/check/ligature_carets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets)
* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]

</details>
<details>
<summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences?</summary>

* [com.google.fonts/check/kerning_for_non_ligated_sequences](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences)
* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- uni0915 + uni0930094D.1
	- uni0930094D.1 + uni0930094D0902
	- uni0916 + uni0930094D.1
	- uni0917 + uni0930094D.1
	- uni0918 + uni0930094D.1
	- uni0919 + uni0930094D.1
	- uni091A + uni0930094D.1
	- uni091B + uni0930094D.1
	- uni091C + uni0930094D.1
	- uni091D + uni0930094D.1
	- uni091E + uni0930094D.1
	- uni091F + uni0930094D.1
	- uni0920 + uni0930094D.1
	- uni0921 + uni0930094D.1
	- uni0922 + uni0930094D.1
	- uni0923 + uni0930094D.1
	- uni0924 + uni0930094D.1
	- uni0925 + uni0930094D.1
	- uni0926 + uni0930094D.1
	- uni0927 + uni0930094D.1
	- uni0928 + uni0930094D.1
	- uni0929 + uni0930094D.1
	- uni092A + uni0930094D.1
	- uni092B + uni0930094D.1
	- uni092C + uni0930094D.1
	- uni092D + uni0930094D.1
	- uni092E + uni0930094D.1
	- uni092F + uni0930094D.1
	- uni0930 + uni0930094D.1
	- uni0931 + uni0930094D.1
	- uni0932 + uni0930094D.1
	- uni0933 + uni0930094D.1
	- uni0934 + uni0930094D.1
	- uni0935 + uni0930094D.1
	- uni0936 + uni0930094D.1
	- uni0937 + uni0930094D.1
	- uni0938 + uni0930094D.1
	- uni0939 + uni0930094D.1
	- uni0958 + uni0930094D.1
	- uni0959 + uni0930094D.1
	- uni095A + uni0930094D.1
	- uni095B + uni0930094D.1
	- uni095C + uni0930094D.1
	- uni095D + uni0930094D.1
	- uni095E + uni0930094D.1
	- uni095F + uni0930094D.1
	- uni0979 + uni0930094D.1
	- uni097A + uni0930094D.1
	- uni097B + uni0930094D.1
	- uni097C + uni0930094D.1
	- uni097E + uni0930094D.1
	- uni097F + uni0930094D.1
	- uni0932.loclMAR + uni0930094D.1
	- uni0936.loclMAR + uni0930094D.1
	- uni091D.np + uni0930094D.1
	- uni0979.np + uni0930094D.1
	- uni092F.post + uni0930094D.1
	- uni0935.post + uni0930094D.1
	- uni0928.post2 + uni0930094D.1
	- uni0936.ss02 + uni0930094D.1

   [code: lacks-kern-info]

</details>
<br>
</details>
<details>
<summary><b>[9] Varta-Regular.ttf</b></summary>
<details>
<summary>🔥 <b>FAIL:</b> Check glyph coverage.</summary>

* [com.google.fonts/check/glyph_coverage](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage)
* 🔥 **FAIL** Missing required codepoints: 0x000D (CARRIAGE RETURN) [code: missing-codepoints]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts</summary>

* [com.google.fonts/check/font_copyright](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright)
* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright (c) 2014-2015, Sorkin Type Co (sorkintype.com | sorkintype@gmail.com)" [code: bad-notice-format]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Does the font have a DSIG table?</summary>

* [com.google.fonts/check/dsig](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/dsig.html#com.google.fonts/check/dsig)
* 🔥 **FAIL** This font lacks a digital signature (DSIG table). Some applications may require one (even if only a dummy placeholder) in order to work properly. You can add a DSIG table by running the `gftools fix-dsig` script.

</details>
<details>
<summary>⚠ <b>WARN:</b> Font has old ttfautohint applied?</summary>

* [com.google.fonts/check/old_ttfautohint](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint)
* ⚠ **WARN** ttfautohint used in font = 1.3; installed = 1.8.2; Need to re-run with the newer version! [code: old-ttfa]

</details>
<details>
<summary>⚠ <b>WARN:</b> Stricter unitsPerEm criteria for Google Fonts. </summary>

* [com.google.fonts/check/unitsperem_strict](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict)
* ⚠ **WARN** Even though unitsPerEm (2048) in this font is reasonable. It is strongly advised to consider changing it to 2000, since it will likely improve the quality of Variable Fonts by avoiding excessive rounding of coordinates on interpolations. [code: legacy-value]

</details>
<details>
<summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary>

* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/contour_count)
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

Glyph name: uni20A8	Contours detected: 1	Expected: 3
Glyph name: uni0122	Contours detected: 1	Expected: 2
Glyph name: uni0136	Contours detected: 1	Expected: 2 or 3
Glyph name: uni0137	Contours detected: 1	Expected: 2 or 3
Glyph name: uni013B	Contours detected: 1	Expected: 2
Glyph name: uni013C	Contours detected: 1	Expected: 2
Glyph name: uni0145	Contours detected: 1	Expected: 2
Glyph name: uni0156	Contours detected: 2	Expected: 3
Glyph name: uni0904	Contours detected: 2	Expected: 1
Glyph name: uni090E	Contours detected: 2	Expected: 1
Glyph name: uni0910	Contours detected: 2	Expected: 1
Glyph name: uni0912	Contours detected: 2	Expected: 1
Glyph name: uni0913	Contours detected: 2	Expected: 1
Glyph name: uni0914	Contours detected: 2	Expected: 1
Glyph name: uni0916	Contours detected: 2	Expected: 1 or 3
Glyph name: uni1ECB	Contours detected: 2	Expected: 3
Glyph name: uni0950	Contours detected: 4	Expected: 3
Glyph name: uni0959	Contours detected: 3	Expected: 2 or 4
Glyph name: uni0967	Contours detected: 2	Expected: 1 [code: contour-count]

</details>
<details>
<summary>⚠ <b>WARN:</b> Check name table: FULL_FONT_NAME entries. </summary>

* [com.google.fonts/check/name/fullfontname](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/fullfontname)
* ⚠ **WARN** Entry [FULL_FONT_NAME(4):WINDOWS(3)] on the "name" table: Got "Varta" which lacks "Regular", but it is probably OK in this case. [code: lacks-regular]

</details>
<details>
<summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature?</summary>

* [com.google.fonts/check/ligature_carets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets)
* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]

</details>
<details>
<summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences?</summary>

* [com.google.fonts/check/kerning_for_non_ligated_sequences](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences)
* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- uni0915 + uni0930094D.1
	- uni0930094D.1 + uni0930094D0902
	- uni0916 + uni0930094D.1
	- uni0917 + uni0930094D.1
	- uni0918 + uni0930094D.1
	- uni0919 + uni0930094D.1
	- uni091A + uni0930094D.1
	- uni091B + uni0930094D.1
	- uni091C + uni0930094D.1
	- uni091D + uni0930094D.1
	- uni091E + uni0930094D.1
	- uni091F + uni0930094D.1
	- uni0920 + uni0930094D.1
	- uni0921 + uni0930094D.1
	- uni0922 + uni0930094D.1
	- uni0923 + uni0930094D.1
	- uni0924 + uni0930094D.1
	- uni0925 + uni0930094D.1
	- uni0926 + uni0930094D.1
	- uni0927 + uni0930094D.1
	- uni0928 + uni0930094D.1
	- uni0929 + uni0930094D.1
	- uni092A + uni0930094D.1
	- uni092B + uni0930094D.1
	- uni092C + uni0930094D.1
	- uni092D + uni0930094D.1
	- uni092E + uni0930094D.1
	- uni092F + uni0930094D.1
	- uni0930 + uni0930094D.1
	- uni0931 + uni0930094D.1
	- uni0932 + uni0930094D.1
	- uni0933 + uni0930094D.1
	- uni0934 + uni0930094D.1
	- uni0935 + uni0930094D.1
	- uni0936 + uni0930094D.1
	- uni0937 + uni0930094D.1
	- uni0938 + uni0930094D.1
	- uni0939 + uni0930094D.1
	- uni0958 + uni0930094D.1
	- uni0959 + uni0930094D.1
	- uni095A + uni0930094D.1
	- uni095B + uni0930094D.1
	- uni095C + uni0930094D.1
	- uni095D + uni0930094D.1
	- uni095E + uni0930094D.1
	- uni095F + uni0930094D.1
	- uni0979 + uni0930094D.1
	- uni097A + uni0930094D.1
	- uni097B + uni0930094D.1
	- uni097C + uni0930094D.1
	- uni097E + uni0930094D.1
	- uni097F + uni0930094D.1
	- uni0932.loclMAR + uni0930094D.1
	- uni0936.loclMAR + uni0930094D.1
	- uni091D.np + uni0930094D.1
	- uni0979.np + uni0930094D.1
	- uni092F.post + uni0930094D.1
	- uni0935.post + uni0930094D.1
	- uni0928.post2 + uni0930094D.1
	- uni0936.ss02 + uni0930094D.1

   [code: lacks-kern-info]

</details>
<br>
</details>
<details>
<summary><b>[8] Varta-SemiBold.ttf</b></summary>
<details>
<summary>🔥 <b>FAIL:</b> Check glyph coverage.</summary>

* [com.google.fonts/check/glyph_coverage](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage)
* 🔥 **FAIL** Missing required codepoints: 0x000D (CARRIAGE RETURN) [code: missing-codepoints]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts</summary>

* [com.google.fonts/check/font_copyright](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright)
* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright (c) 2014-2015, Sorkin Type Co (sorkintype.com | sorkintype@gmail.com)" [code: bad-notice-format]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Does the font have a DSIG table?</summary>

* [com.google.fonts/check/dsig](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/dsig.html#com.google.fonts/check/dsig)
* 🔥 **FAIL** This font lacks a digital signature (DSIG table). Some applications may require one (even if only a dummy placeholder) in order to work properly. You can add a DSIG table by running the `gftools fix-dsig` script.

</details>
<details>
<summary>⚠ <b>WARN:</b> Font has old ttfautohint applied?</summary>

* [com.google.fonts/check/old_ttfautohint](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint)
* ⚠ **WARN** ttfautohint used in font = 1.3; installed = 1.8.2; Need to re-run with the newer version! [code: old-ttfa]

</details>
<details>
<summary>⚠ <b>WARN:</b> Stricter unitsPerEm criteria for Google Fonts. </summary>

* [com.google.fonts/check/unitsperem_strict](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict)
* ⚠ **WARN** Even though unitsPerEm (2048) in this font is reasonable. It is strongly advised to consider changing it to 2000, since it will likely improve the quality of Variable Fonts by avoiding excessive rounding of coordinates on interpolations. [code: legacy-value]

</details>
<details>
<summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary>

* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/contour_count)
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

Glyph name: uni20A8	Contours detected: 1	Expected: 3
Glyph name: uni0122	Contours detected: 1	Expected: 2
Glyph name: uni0136	Contours detected: 1	Expected: 2 or 3
Glyph name: uni0137	Contours detected: 1	Expected: 2 or 3
Glyph name: uni013B	Contours detected: 1	Expected: 2
Glyph name: uni013C	Contours detected: 1	Expected: 2
Glyph name: uni0145	Contours detected: 1	Expected: 2
Glyph name: uni0156	Contours detected: 2	Expected: 3
Glyph name: uni0218	Contours detected: 1	Expected: 2
Glyph name: uni0904	Contours detected: 2	Expected: 1
Glyph name: uni090E	Contours detected: 2	Expected: 1
Glyph name: uni0910	Contours detected: 2	Expected: 1
Glyph name: uni0912	Contours detected: 2	Expected: 1
Glyph name: uni0913	Contours detected: 2	Expected: 1
Glyph name: uni0914	Contours detected: 2	Expected: 1
Glyph name: uni0916	Contours detected: 2	Expected: 1 or 3
Glyph name: uni1E92	Contours detected: 1	Expected: 2
Glyph name: uni1EA0	Contours detected: 2	Expected: 3
Glyph name: uni1EB6	Contours detected: 3	Expected: 4
Glyph name: uni094B	Contours detected: 2	Expected: 1
Glyph name: uni0950	Contours detected: 4	Expected: 3
Glyph name: uni1ED8	Contours detected: 3	Expected: 4
Glyph name: uni1EDE	Contours detected: 2	Expected: 3 or 4
Glyph name: uni1EDF	Contours detected: 2	Expected: 3
Glyph name: uni0959	Contours detected: 3	Expected: 2 or 4
Glyph name: uni0967	Contours detected: 2	Expected: 1 [code: contour-count]

</details>
<details>
<summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature?</summary>

* [com.google.fonts/check/ligature_carets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets)
* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]

</details>
<details>
<summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences?</summary>

* [com.google.fonts/check/kerning_for_non_ligated_sequences](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences)
* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- uni0915 + uni0930094D.1
	- uni0930094D.1 + uni0930094D0902
	- uni0916 + uni0930094D.1
	- uni0917 + uni0930094D.1
	- uni0918 + uni0930094D.1
	- uni0919 + uni0930094D.1
	- uni091A + uni0930094D.1
	- uni091B + uni0930094D.1
	- uni091C + uni0930094D.1
	- uni091D + uni0930094D.1
	- uni091E + uni0930094D.1
	- uni091F + uni0930094D.1
	- uni0920 + uni0930094D.1
	- uni0921 + uni0930094D.1
	- uni0922 + uni0930094D.1
	- uni0923 + uni0930094D.1
	- uni0924 + uni0930094D.1
	- uni0925 + uni0930094D.1
	- uni0926 + uni0930094D.1
	- uni0927 + uni0930094D.1
	- uni0928 + uni0930094D.1
	- uni0929 + uni0930094D.1
	- uni092A + uni0930094D.1
	- uni092B + uni0930094D.1
	- uni092C + uni0930094D.1
	- uni092D + uni0930094D.1
	- uni092E + uni0930094D.1
	- uni092F + uni0930094D.1
	- uni0930 + uni0930094D.1
	- uni0931 + uni0930094D.1
	- uni0932 + uni0930094D.1
	- uni0933 + uni0930094D.1
	- uni0934 + uni0930094D.1
	- uni0935 + uni0930094D.1
	- uni0936 + uni0930094D.1
	- uni0937 + uni0930094D.1
	- uni0938 + uni0930094D.1
	- uni0939 + uni0930094D.1
	- uni0958 + uni0930094D.1
	- uni0959 + uni0930094D.1
	- uni095A + uni0930094D.1
	- uni095B + uni0930094D.1
	- uni095C + uni0930094D.1
	- uni095D + uni0930094D.1
	- uni095E + uni0930094D.1
	- uni095F + uni0930094D.1
	- uni0979 + uni0930094D.1
	- uni097A + uni0930094D.1
	- uni097B + uni0930094D.1
	- uni097C + uni0930094D.1
	- uni097E + uni0930094D.1
	- uni097F + uni0930094D.1
	- uni0932.loclMAR + uni0930094D.1
	- uni0936.loclMAR + uni0930094D.1
	- uni091D.np + uni0930094D.1
	- uni0979.np + uni0930094D.1
	- uni092F.post + uni0930094D.1
	- uni0935.post + uni0930094D.1
	- uni0928.post2 + uni0930094D.1
	- uni0936.ss02 + uni0930094D.1

   [code: lacks-kern-info]

</details>
<br>
</details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS |
|:-----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 17 | 22 | 234 | 24 | 254 |
| 0% | 3% | 4% | 42% | 4% | 46% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**

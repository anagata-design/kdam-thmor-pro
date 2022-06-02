## Fontbakery report

Fontbakery version: 0.8.8

<details><summary><b>[8] KdamThmorPro-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Version number has increased since previous release on Google Fonts? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump">com.google.fonts/check/version_bump</a>)</summary><div>


* 🔥 **FAIL** Version number 1.0030059814453125 is equal to version on Google Fonts.
* 🔥 **FAIL** Version number 1.0030059814453125 is equal to version on Google Fonts GitHub repo.
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ANGT' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: asterisk	Contours detected: 5	Expected: 1 or 4
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: Eth	Contours detected: 3	Expected: 2
	- Glyph name: dagger	Contours detected: 4	Expected: 1 or 2
	- Glyph name: daggerdbl	Contours detected: 7	Expected: 1 or 3
	- Glyph name: uni25CC	Contours detected: 10	Expected: 16 or 12
	- Glyph name: Eth	Contours detected: 3	Expected: 2
	- Glyph name: asterisk	Contours detected: 5	Expected: 1 or 4
	- Glyph name: dagger	Contours detected: 4	Expected: 1 or 2
	- Glyph name: daggerdbl	Contours detected: 7	Expected: 1 or 3
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 
	- And Glyph name: uni25CC	Contours detected: 10	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure no GSUB5/GPOS7 lookups are present. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/gsub5_gpos7">com.google.fonts/check/gsub5_gpos7</a>)</summary><div>


* ⚠ **WARN** Font contains a GSUB5 lookup which is not processed by macOS [code: has-gsub5]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* comma (U+002C): X=92.0,Y=2.0 (should be at baseline 0?)
	* comma (U+002C): X=51.0,Y=2.0 (should be at baseline 0?)
	* seven (U+0037): X=21.0,Y=794.0 (should be at cap-height 793?)
	* seven (U+0037): X=392.0,Y=794.0 (should be at cap-height 793?)
	* semicolon (U+003B): X=114.0,Y=2.0 (should be at baseline 0?)
	* semicolon (U+003B): X=74.0,Y=2.0 (should be at baseline 0?)
	* Z (U+005A): X=558.0,Y=-1.0 (should be at baseline 0?)
	* Z (U+005A): X=134.0,Y=-1.0 (should be at baseline 0?)
	* Z (U+005A): X=63.0,Y=794.0 (should be at cap-height 793?)
	* Z (U+005A): X=463.0,Y=794.0 (should be at cap-height 793?) and 17 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* dagger (U+2020): L<<227.0,0.0>--<213.0,305.0>> -> L<<213.0,305.0>--<213.0,448.0>>
	* dagger (U+2020): L<<292.0,448.0>--<292.0,306.0>> -> L<<292.0,306.0>--<277.0,0.0>>
	* exclam (U+0021): L<<120.0,247.0>--<92.0,612.0>> -> L<<92.0,612.0>--<92.0,805.0>>
	* exclam (U+0021): L<<220.0,805.0>--<220.0,612.0>> -> L<<220.0,612.0>--<191.0,247.0>>
	* exclamdown (U+00A1): L<<185.0,365.0>--<213.0,0.0>> -> L<<213.0,0.0>--<213.0,-193.0>>
	* exclamdown (U+00A1): L<<85.0,-193.0>--<85.0,0.0>> -> L<<85.0,0.0>--<114.0,365.0>>
	* lozenge (U+25CA): L<<308.0,113.0>--<387.0,237.0>> -> L<<387.0,237.0>--<490.0,390.0>>
	* lozenge (U+25CA): L<<317.0,677.0>--<238.0,548.0>> -> L<<238.0,548.0>--<140.0,402.0>>
	* lozenge (U+25CA): L<<490.0,390.0>--<408.0,515.0>> -> L<<408.0,515.0>--<317.0,677.0>> and uni1799 (U+1799): L<<450.0,98.0>--<451.0,430.0>> -> L<<451.0,430.0>--<451.0,514.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * AE (U+00C6): L<<443.0,794.0>--<934.0,793.0>>
 * Aacute (U+00C1): L<<377.0,1035.0>--<502.0,1034.0>>
 * Agrave (U+00C0): L<<194.0,1034.0>--<319.0,1035.0>>
 * Eacute (U+00C9): L<<344.0,1035.0>--<469.0,1034.0>>
 * Egrave (U+00C8): L<<161.0,1034.0>--<286.0,1035.0>>
 * Iacute (U+00CD): L<<189.0,1035.0>--<314.0,1034.0>>
 * Igrave (U+00CC): L<<11.0,1034.0>--<136.0,1035.0>>
 * OE (U+0152): L<<247.0,797.0>--<945.0,793.0>>
 * OE (U+0152): L<<951.0,0.0>--<247.0,-4.0>>
 * Oacute (U+00D3): L<<387.0,1035.0>--<512.0,1034.0>> and 74 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 1 | 7 | 106 | 7 | 104 | 0 |
| 0% | 0% | 3% | 47% | 3% | 46% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**

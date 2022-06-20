## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[20] NotoSansOldHungarian-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 20** the noto project authors (https://github.com/notofonts/noto-project-template)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* 🔥 **FAIL** Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at https://pypi.org/project/gftools/ [code: lacks-gasp]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/familyname">com.google.fonts/check/name/familyname</a>)</summary><div>


* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "Noto Sans Old Hungarian" but got "Noto Sans OldHung". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicfamilyname">com.google.fonts/check/name/typographicfamilyname</a>)</summary><div>


* 🔥 **FAIL** Font style is "Regular" and, for that reason, it is not expected to have a [TYPOGRAPHIC_FAMILY_NAME(16):WINDOWS(3)] entry! [code: ribbi]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansOldHungarian/googlefonts/ttf/NotoSansOldHungarian-Regular.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 859 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 241, but got 177 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Does full font name begin with the font family name? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/name/match_familyname_fullfont">com.google.fonts/check/name/match_familyname_fullfont</a>)</summary><div>


* 🔥 **FAIL** On the 'name' table, the full font name 'Noto Sans Old Hungarian Regular' does not begin with the font family name 'Noto Sans OldHung' in platformID 3, encodingID 1, languageID 1033(0409), and nameID 1. [code: mismatch-font-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/old-hungarian.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansOldHungarian/googlefonts/ttf/NotoSansOldHungarian-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/old-hungarian.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳀 ‍ 𐳂  = 𐳀‍𐳂</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CC0.ltr=0+444|space=1+260|space=1+0|space=3+260|uni10CC2.ltr=4+538|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CC2_10CC0.ltr=9+646</pre>



<pre>Got     : uni10CC0.ltr=0+444|space=1+260|space=1+0|space=3+260|uni10CC2.ltr=4+538|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CC2_10CC0.ltr=9+646</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3500 2036" transform="matrix(1 0 0 -1 0 0)">
<path d="M95.0,0.0L95.0,600.0L214.0,600.0L412.0,409.0L412.0,300.0L182.0,289.0L182.0,0.0L95.0,0.0ZM182.0,366.0L336.0,373.0L182.0,523.0L182.0,366.0Z"  transform="translate(0, 677)"/>
<path d=""  transform="translate(444, 677)"/>
<path d=""  transform="translate(704, 677)"/>
<path d=""  transform="translate(704, 677)"/>
<path d="M10.0,0.0L217.0,313.0L25.0,600.0L119.0,600.0L268.0,371.0L417.0,600.0L516.0,600.0L321.0,311.0L528.0,0.0L434.0,0.0L271.0,253.0L111.0,0.0L10.0,0.0Z"  transform="translate(964, 677)"/>
<path d=""  transform="translate(1502, 677)"/>
<path d=""  transform="translate(1762, 677)"/>
<path d="M56.0,416.0L56.0,487.0L514.0,487.0L514.0,416.0L56.0,416.0ZM56.0,217.0L56.0,288.0L514.0,288.0L514.0,217.0L56.0,217.0Z"  transform="translate(2022, 677)"/>
<path d=""  transform="translate(2594, 677)"/>
<path d="M10.0,0.0L217.0,313.0L25.0,600.0L119.0,600.0L268.0,371.0L417.0,600.0L537.0,600.0L616.0,302.0L548.0,246.0L346.0,348.0L321.0,311.0L528.0,0.0L434.0,0.0L271.0,253.0L111.0,0.0L10.0,0.0ZM525.0,342.0L473.0,536.0L387.0,408.0L525.0,342.0Z"  transform="translate(2854, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3528 2036" transform="matrix(1 0 0 -1 0 0)">
<path d="M95.0,0.0L95.0,600.0L214.0,600.0L412.0,409.0L412.0,300.0L182.0,289.0L182.0,0.0L95.0,0.0ZM182.0,366.0L336.0,373.0L182.0,523.0L182.0,366.0Z"  transform="translate(0, 677)"/>
<path d=""  transform="translate(444, 677)"/>
<path d=""  transform="translate(704, 677)"/>
<path d=""  transform="translate(704, 677)"/>
<path d="M10.0,0.0L217.0,313.0L25.0,600.0L119.0,600.0L268.0,371.0L417.0,600.0L516.0,600.0L321.0,311.0L528.0,0.0L434.0,0.0L271.0,253.0L111.0,0.0L10.0,0.0Z"  transform="translate(964, 677)"/>
<path d=""  transform="translate(1502, 677)"/>
<path d=""  transform="translate(1762, 677)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(2022, 677)"/>
<path d=""  transform="translate(2622, 677)"/>
<path d="M10.0,0.0L217.0,313.0L25.0,600.0L119.0,600.0L268.0,371.0L417.0,600.0L537.0,600.0L616.0,302.0L548.0,246.0L346.0,348.0L321.0,311.0L528.0,0.0L434.0,0.0L271.0,253.0L111.0,0.0L10.0,0.0ZM525.0,342.0L473.0,536.0L387.0,408.0L525.0,342.0Z"  transform="translate(2882, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳀 ‍ 𐳇  = 𐳀‍𐳇</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CC0.ltr=0+444|space=1+260|space=1+0|space=3+260|uni10CC7.ltr=4+437|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CC0.ltr=9+444|space=9+0|uni10CC7.ltr=11+437</pre>



<pre>Got     : uni10CC0.ltr=0+444|space=1+260|space=1+0|space=3+260|uni10CC7.ltr=4+437|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CC0.ltr=9+444|space=9+0|uni10CC7.ltr=11+437</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3634 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(444, 677)"/>
<path d=""  transform="translate(704, 677)"/>
<path d=""  transform="translate(704, 677)"/>
<path d=""  transform="translate(964, 677)"/>
<path d=""  transform="translate(1401, 677)"/>
<path d=""  transform="translate(1661, 677)"/>
<path d=""  transform="translate(1921, 677)"/>
<path d=""  transform="translate(2493, 677)"/>
<path d=""  transform="translate(2753, 677)"/>
<path d=""  transform="translate(3197, 677)"/>
<path d=""  transform="translate(3197, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3662 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(444, 677)"/>
<path d=""  transform="translate(704, 677)"/>
<path d=""  transform="translate(704, 677)"/>
<path d=""  transform="translate(964, 677)"/>
<path d=""  transform="translate(1401, 677)"/>
<path d=""  transform="translate(1661, 677)"/>
<path d=""  transform="translate(1921, 677)"/>
<path d=""  transform="translate(2521, 677)"/>
<path d=""  transform="translate(2781, 677)"/>
<path d=""  transform="translate(3225, 677)"/>
<path d=""  transform="translate(3225, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳀 ‍ 𐳖  = 𐳀‍𐳖</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CC0.ltr=0+444|space=1+260|space=1+0|space=3+260|uni10CD6.ltr=4+612|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CD6_10CC0.ltr=9+700</pre>



<pre>Got     : uni10CC0.ltr=0+444|space=1+260|space=1+0|space=3+260|uni10CD6.ltr=4+612|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CD6_10CC0.ltr=9+700</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3628 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(444, 677)"/>
<path d=""  transform="translate(704, 677)"/>
<path d=""  transform="translate(704, 677)"/>
<path d=""  transform="translate(964, 677)"/>
<path d=""  transform="translate(1576, 677)"/>
<path d=""  transform="translate(1836, 677)"/>
<path d=""  transform="translate(2096, 677)"/>
<path d=""  transform="translate(2668, 677)"/>
<path d=""  transform="translate(2928, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3656 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(444, 677)"/>
<path d=""  transform="translate(704, 677)"/>
<path d=""  transform="translate(704, 677)"/>
<path d=""  transform="translate(964, 677)"/>
<path d=""  transform="translate(1576, 677)"/>
<path d=""  transform="translate(1836, 677)"/>
<path d=""  transform="translate(2096, 677)"/>
<path d=""  transform="translate(2696, 677)"/>
<path d=""  transform="translate(2956, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳀 ‍ 𐳢  = 𐳀‍𐳢</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CC0.ltr=0+444|space=1+260|space=1+0|space=3+260|uni10CE2.ltr=4+627|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CE2_10CC0.ltr=9+794</pre>



<pre>Got     : uni10CC0.ltr=0+444|space=1+260|space=1+0|space=3+260|uni10CE2.ltr=4+627|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CE2_10CC0.ltr=9+794</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3737 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(444, 677)"/>
<path d=""  transform="translate(704, 677)"/>
<path d=""  transform="translate(704, 677)"/>
<path d=""  transform="translate(964, 677)"/>
<path d=""  transform="translate(1591, 677)"/>
<path d=""  transform="translate(1851, 677)"/>
<path d=""  transform="translate(2111, 677)"/>
<path d=""  transform="translate(2683, 677)"/>
<path d=""  transform="translate(2943, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3765 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(444, 677)"/>
<path d=""  transform="translate(704, 677)"/>
<path d=""  transform="translate(704, 677)"/>
<path d=""  transform="translate(964, 677)"/>
<path d=""  transform="translate(1591, 677)"/>
<path d=""  transform="translate(1851, 677)"/>
<path d=""  transform="translate(2111, 677)"/>
<path d=""  transform="translate(2711, 677)"/>
<path d=""  transform="translate(2971, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳀 ‍ 𐳦 ‍ 𐳦  = 𐳀‍𐳦‍𐳦</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CC0.ltr=0+444|space=1+260|space=1+0|space=3+260|uni10CE6.ltr=4+467|space=5+260|space=5+0|space=7+260|uni10CE6.ltr=8+467|space=9+260|space=10+260|.notdef=11+600|space=12+260|uni10CC0.ltr=13+444|space=13+0|uni10CE6.ltr=15+467|space=15+0|uni10CE6.ltr=17+467</pre>



<pre>Got     : uni10CC0.ltr=0+444|space=1+260|space=1+0|space=3+260|uni10CE6.ltr=4+467|space=5+260|space=5+0|space=7+260|uni10CE6.ltr=8+467|space=9+260|space=10+260|equal=11+572|space=12+260|uni10CC0.ltr=13+444|space=13+0|uni10CE6.ltr=15+467|space=15+0|uni10CE6.ltr=17+467</pre>



<pre>                                                                                                                                                                ^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5148 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(444, 677)"/>
<path d=""  transform="translate(704, 677)"/>
<path d=""  transform="translate(704, 677)"/>
<path d=""  transform="translate(964, 677)"/>
<path d=""  transform="translate(1431, 677)"/>
<path d=""  transform="translate(1691, 677)"/>
<path d=""  transform="translate(1691, 677)"/>
<path d=""  transform="translate(1951, 677)"/>
<path d=""  transform="translate(2418, 677)"/>
<path d=""  transform="translate(2678, 677)"/>
<path d=""  transform="translate(2938, 677)"/>
<path d=""  transform="translate(3510, 677)"/>
<path d=""  transform="translate(3770, 677)"/>
<path d=""  transform="translate(4214, 677)"/>
<path d=""  transform="translate(4214, 677)"/>
<path d=""  transform="translate(4681, 677)"/>
<path d=""  transform="translate(4681, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5176 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(444, 677)"/>
<path d=""  transform="translate(704, 677)"/>
<path d=""  transform="translate(704, 677)"/>
<path d=""  transform="translate(964, 677)"/>
<path d=""  transform="translate(1431, 677)"/>
<path d=""  transform="translate(1691, 677)"/>
<path d=""  transform="translate(1691, 677)"/>
<path d=""  transform="translate(1951, 677)"/>
<path d=""  transform="translate(2418, 677)"/>
<path d=""  transform="translate(2678, 677)"/>
<path d=""  transform="translate(2938, 677)"/>
<path d=""  transform="translate(3538, 677)"/>
<path d=""  transform="translate(3798, 677)"/>
<path d=""  transform="translate(4242, 677)"/>
<path d=""  transform="translate(4242, 677)"/>
<path d=""  transform="translate(4709, 677)"/>
<path d=""  transform="translate(4709, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳁 ‍ 𐳢  = 𐳁‍𐳢</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CC1.ltr=0+433|space=1+260|space=1+0|space=3+260|uni10CE2.ltr=4+627|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CC1.ltr=9+433|space=9+0|uni10CE2.ltr=11+627</pre>



<pre>Got     : uni10CC1.ltr=0+433|space=1+260|space=1+0|space=3+260|uni10CE2.ltr=4+627|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CC1.ltr=9+433|space=9+0|uni10CE2.ltr=11+627</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3992 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(433, 677)"/>
<path d=""  transform="translate(693, 677)"/>
<path d=""  transform="translate(693, 677)"/>
<path d=""  transform="translate(953, 677)"/>
<path d=""  transform="translate(1580, 677)"/>
<path d=""  transform="translate(1840, 677)"/>
<path d=""  transform="translate(2100, 677)"/>
<path d=""  transform="translate(2672, 677)"/>
<path d=""  transform="translate(2932, 677)"/>
<path d=""  transform="translate(3365, 677)"/>
<path d=""  transform="translate(3365, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4020 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(433, 677)"/>
<path d=""  transform="translate(693, 677)"/>
<path d=""  transform="translate(693, 677)"/>
<path d=""  transform="translate(953, 677)"/>
<path d=""  transform="translate(1580, 677)"/>
<path d=""  transform="translate(1840, 677)"/>
<path d=""  transform="translate(2100, 677)"/>
<path d=""  transform="translate(2700, 677)"/>
<path d=""  transform="translate(2960, 677)"/>
<path d=""  transform="translate(3393, 677)"/>
<path d=""  transform="translate(3393, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳂 ‍ 𐳀  = 𐳂‍𐳀</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CC2.ltr=0+538|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CC0_10CC2.ltr=9+646</pre>



<pre>Got     : uni10CC2.ltr=0+538|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CC0_10CC2.ltr=9+646</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3500 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(538, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(1058, 677)"/>
<path d=""  transform="translate(1502, 677)"/>
<path d=""  transform="translate(1762, 677)"/>
<path d=""  transform="translate(2022, 677)"/>
<path d=""  transform="translate(2594, 677)"/>
<path d=""  transform="translate(2854, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3528 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(538, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(1058, 677)"/>
<path d=""  transform="translate(1502, 677)"/>
<path d=""  transform="translate(1762, 677)"/>
<path d=""  transform="translate(2022, 677)"/>
<path d=""  transform="translate(2622, 677)"/>
<path d=""  transform="translate(2882, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳂 ‍ 𐳉  = 𐳂‍𐳉</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CC2.ltr=0+538|space=1+260|space=1+0|space=3+260|uni10CC9.ltr=4+411|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CC2.ltr=9+538|space=9+0|uni10CC9.ltr=11+411</pre>



<pre>Got     : uni10CC2.ltr=0+538|space=1+260|space=1+0|space=3+260|uni10CC9.ltr=4+411|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CC2.ltr=9+538|space=9+0|uni10CC9.ltr=11+411</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3770 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(538, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(1058, 677)"/>
<path d=""  transform="translate(1469, 677)"/>
<path d=""  transform="translate(1729, 677)"/>
<path d=""  transform="translate(1989, 677)"/>
<path d=""  transform="translate(2561, 677)"/>
<path d=""  transform="translate(2821, 677)"/>
<path d=""  transform="translate(3359, 677)"/>
<path d=""  transform="translate(3359, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3798 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(538, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(1058, 677)"/>
<path d=""  transform="translate(1469, 677)"/>
<path d=""  transform="translate(1729, 677)"/>
<path d=""  transform="translate(1989, 677)"/>
<path d=""  transform="translate(2589, 677)"/>
<path d=""  transform="translate(2849, 677)"/>
<path d=""  transform="translate(3387, 677)"/>
<path d=""  transform="translate(3387, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳂 ‍ 𐳐  = 𐳂‍𐳐</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CC2.ltr=0+538|space=1+260|space=1+0|space=3+260|uni10CD0.ltr=4+452|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CC2.ltr=9+538|space=9+0|uni10CD0.ltr=11+452</pre>



<pre>Got     : uni10CC2.ltr=0+538|space=1+260|space=1+0|space=3+260|uni10CD0.ltr=4+452|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CC2.ltr=9+538|space=9+0|uni10CD0.ltr=11+452</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3852 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(538, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(1058, 677)"/>
<path d=""  transform="translate(1510, 677)"/>
<path d=""  transform="translate(1770, 677)"/>
<path d=""  transform="translate(2030, 677)"/>
<path d=""  transform="translate(2602, 677)"/>
<path d=""  transform="translate(2862, 677)"/>
<path d=""  transform="translate(3400, 677)"/>
<path d=""  transform="translate(3400, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3880 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(538, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(1058, 677)"/>
<path d=""  transform="translate(1510, 677)"/>
<path d=""  transform="translate(1770, 677)"/>
<path d=""  transform="translate(2030, 677)"/>
<path d=""  transform="translate(2630, 677)"/>
<path d=""  transform="translate(2890, 677)"/>
<path d=""  transform="translate(3428, 677)"/>
<path d=""  transform="translate(3428, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳂 ‍ 𐳛  = 𐳂‍𐳛</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CC2.ltr=0+538|space=1+260|space=1+0|space=3+260|uni10CDB.ltr=4+473|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CC2.ltr=9+538|space=9+0|uni10CDB.ltr=11+473</pre>



<pre>Got     : uni10CC2.ltr=0+538|space=1+260|space=1+0|space=3+260|uni10CDB.ltr=4+473|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CC2.ltr=9+538|space=9+0|uni10CDB.ltr=11+473</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3894 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(538, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(1058, 677)"/>
<path d=""  transform="translate(1531, 677)"/>
<path d=""  transform="translate(1791, 677)"/>
<path d=""  transform="translate(2051, 677)"/>
<path d=""  transform="translate(2623, 677)"/>
<path d=""  transform="translate(2883, 677)"/>
<path d=""  transform="translate(3421, 677)"/>
<path d=""  transform="translate(3421, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3922 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(538, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(1058, 677)"/>
<path d=""  transform="translate(1531, 677)"/>
<path d=""  transform="translate(1791, 677)"/>
<path d=""  transform="translate(2051, 677)"/>
<path d=""  transform="translate(2651, 677)"/>
<path d=""  transform="translate(2911, 677)"/>
<path d=""  transform="translate(3449, 677)"/>
<path d=""  transform="translate(3449, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳂 ‍ 𐳦  = 𐳂‍𐳦</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CC2.ltr=0+538|space=1+260|space=1+0|space=3+260|uni10CE6.ltr=4+467|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CC2.ltr=9+538|space=9+0|uni10CE6.ltr=11+467</pre>



<pre>Got     : uni10CC2.ltr=0+538|space=1+260|space=1+0|space=3+260|uni10CE6.ltr=4+467|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CC2.ltr=9+538|space=9+0|uni10CE6.ltr=11+467</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3882 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(538, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(1058, 677)"/>
<path d=""  transform="translate(1525, 677)"/>
<path d=""  transform="translate(1785, 677)"/>
<path d=""  transform="translate(2045, 677)"/>
<path d=""  transform="translate(2617, 677)"/>
<path d=""  transform="translate(2877, 677)"/>
<path d=""  transform="translate(3415, 677)"/>
<path d=""  transform="translate(3415, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3910 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(538, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(1058, 677)"/>
<path d=""  transform="translate(1525, 677)"/>
<path d=""  transform="translate(1785, 677)"/>
<path d=""  transform="translate(2045, 677)"/>
<path d=""  transform="translate(2645, 677)"/>
<path d=""  transform="translate(2905, 677)"/>
<path d=""  transform="translate(3443, 677)"/>
<path d=""  transform="translate(3443, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳄 ‍ 𐳓  = 𐳄‍𐳓</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CC4.ltr=0+447|space=1+260|space=1+0|space=3+260|uni10CD3.ltr=4+493|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CC4.ltr=9+447|space=9+0|uni10CD3.ltr=11+493</pre>



<pre>Got     : uni10CC4.ltr=0+447|space=1+260|space=1+0|space=3+260|uni10CD3.ltr=4+493|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CC4.ltr=9+447|space=9+0|uni10CD3.ltr=11+493</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3752 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(447, 677)"/>
<path d=""  transform="translate(707, 677)"/>
<path d=""  transform="translate(707, 677)"/>
<path d=""  transform="translate(967, 677)"/>
<path d=""  transform="translate(1460, 677)"/>
<path d=""  transform="translate(1720, 677)"/>
<path d=""  transform="translate(1980, 677)"/>
<path d=""  transform="translate(2552, 677)"/>
<path d=""  transform="translate(2812, 677)"/>
<path d=""  transform="translate(3259, 677)"/>
<path d=""  transform="translate(3259, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3780 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(447, 677)"/>
<path d=""  transform="translate(707, 677)"/>
<path d=""  transform="translate(707, 677)"/>
<path d=""  transform="translate(967, 677)"/>
<path d=""  transform="translate(1460, 677)"/>
<path d=""  transform="translate(1720, 677)"/>
<path d=""  transform="translate(1980, 677)"/>
<path d=""  transform="translate(2580, 677)"/>
<path d=""  transform="translate(2840, 677)"/>
<path d=""  transform="translate(3287, 677)"/>
<path d=""  transform="translate(3287, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳄 ‍ 𐳔  = 𐳄‍𐳔</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CC4.ltr=0+447|space=1+260|space=1+0|space=3+260|uni10CD4.ltr=4+469|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CC4.ltr=9+447|space=9+0|uni10CD4.ltr=11+469</pre>



<pre>Got     : uni10CC4.ltr=0+447|space=1+260|space=1+0|space=3+260|uni10CD4.ltr=4+469|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CC4.ltr=9+447|space=9+0|uni10CD4.ltr=11+469</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3704 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(447, 677)"/>
<path d=""  transform="translate(707, 677)"/>
<path d=""  transform="translate(707, 677)"/>
<path d=""  transform="translate(967, 677)"/>
<path d=""  transform="translate(1436, 677)"/>
<path d=""  transform="translate(1696, 677)"/>
<path d=""  transform="translate(1956, 677)"/>
<path d=""  transform="translate(2528, 677)"/>
<path d=""  transform="translate(2788, 677)"/>
<path d=""  transform="translate(3235, 677)"/>
<path d=""  transform="translate(3235, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3732 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(447, 677)"/>
<path d=""  transform="translate(707, 677)"/>
<path d=""  transform="translate(707, 677)"/>
<path d=""  transform="translate(967, 677)"/>
<path d=""  transform="translate(1436, 677)"/>
<path d=""  transform="translate(1696, 677)"/>
<path d=""  transform="translate(1956, 677)"/>
<path d=""  transform="translate(2556, 677)"/>
<path d=""  transform="translate(2816, 677)"/>
<path d=""  transform="translate(3263, 677)"/>
<path d=""  transform="translate(3263, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳆 ‍ 𐳀  = 𐳆‍𐳀</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CC6.ltr=0+615|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CC6.ltr=9+615|space=9+0|uni10CC0.ltr=11+444</pre>



<pre>Got     : uni10CC6.ltr=0+615|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CC6.ltr=9+615|space=9+0|uni10CC0.ltr=11+444</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3990 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(615, 677)"/>
<path d=""  transform="translate(875, 677)"/>
<path d=""  transform="translate(875, 677)"/>
<path d=""  transform="translate(1135, 677)"/>
<path d=""  transform="translate(1579, 677)"/>
<path d=""  transform="translate(1839, 677)"/>
<path d=""  transform="translate(2099, 677)"/>
<path d=""  transform="translate(2671, 677)"/>
<path d=""  transform="translate(2931, 677)"/>
<path d=""  transform="translate(3546, 677)"/>
<path d=""  transform="translate(3546, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4018 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(615, 677)"/>
<path d=""  transform="translate(875, 677)"/>
<path d=""  transform="translate(875, 677)"/>
<path d=""  transform="translate(1135, 677)"/>
<path d=""  transform="translate(1579, 677)"/>
<path d=""  transform="translate(1839, 677)"/>
<path d=""  transform="translate(2099, 677)"/>
<path d=""  transform="translate(2699, 677)"/>
<path d=""  transform="translate(2959, 677)"/>
<path d=""  transform="translate(3574, 677)"/>
<path d=""  transform="translate(3574, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳆 ‍ 𐳐 ‍ 𐳙  = 𐳆‍𐳐‍𐳙</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CC6.ltr=0+615|space=1+260|space=1+0|space=3+260|uni10CD0.ltr=4+452|space=5+260|space=5+0|space=7+260|uni10CD9.ltr=8+420|space=9+260|space=10+260|.notdef=11+600|space=12+260|uni10CC6.ltr=13+615|space=13+0|uni10CD9_10CD0.ltr=15+448</pre>



<pre>Got     : uni10CC6.ltr=0+615|space=1+260|space=1+0|space=3+260|uni10CD0.ltr=4+452|space=5+260|space=5+0|space=7+260|uni10CD9.ltr=8+420|space=9+260|space=10+260|equal=11+572|space=12+260|uni10CC6.ltr=13+615|space=13+0|uni10CD9_10CD0.ltr=15+448</pre>



<pre>                                                                                                                                                                ^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4942 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(615, 677)"/>
<path d=""  transform="translate(875, 677)"/>
<path d=""  transform="translate(875, 677)"/>
<path d=""  transform="translate(1135, 677)"/>
<path d=""  transform="translate(1587, 677)"/>
<path d=""  transform="translate(1847, 677)"/>
<path d=""  transform="translate(1847, 677)"/>
<path d=""  transform="translate(2107, 677)"/>
<path d=""  transform="translate(2527, 677)"/>
<path d=""  transform="translate(2787, 677)"/>
<path d=""  transform="translate(3047, 677)"/>
<path d=""  transform="translate(3619, 677)"/>
<path d=""  transform="translate(3879, 677)"/>
<path d=""  transform="translate(4494, 677)"/>
<path d=""  transform="translate(4494, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4970 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(615, 677)"/>
<path d=""  transform="translate(875, 677)"/>
<path d=""  transform="translate(875, 677)"/>
<path d=""  transform="translate(1135, 677)"/>
<path d=""  transform="translate(1587, 677)"/>
<path d=""  transform="translate(1847, 677)"/>
<path d=""  transform="translate(1847, 677)"/>
<path d=""  transform="translate(2107, 677)"/>
<path d=""  transform="translate(2527, 677)"/>
<path d=""  transform="translate(2787, 677)"/>
<path d=""  transform="translate(3047, 677)"/>
<path d=""  transform="translate(3647, 677)"/>
<path d=""  transform="translate(3907, 677)"/>
<path d=""  transform="translate(4522, 677)"/>
<path d=""  transform="translate(4522, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳇 ‍ 𐳪  = 𐳇‍𐳪</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CC7.ltr=0+437|space=1+260|space=1+0|space=3+260|uni10CEA.ltr=4+662|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CC7.ltr=9+437|space=9+0|uni10CEA.ltr=11+662</pre>



<pre>Got     : uni10CC7.ltr=0+437|space=1+260|space=1+0|space=3+260|uni10CEA.ltr=4+662|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CC7.ltr=9+437|space=9+0|uni10CEA.ltr=11+662</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4070 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(437, 677)"/>
<path d=""  transform="translate(697, 677)"/>
<path d=""  transform="translate(697, 677)"/>
<path d=""  transform="translate(957, 677)"/>
<path d=""  transform="translate(1619, 677)"/>
<path d=""  transform="translate(1879, 677)"/>
<path d=""  transform="translate(2139, 677)"/>
<path d=""  transform="translate(2711, 677)"/>
<path d=""  transform="translate(2971, 677)"/>
<path d=""  transform="translate(3408, 677)"/>
<path d=""  transform="translate(3408, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4098 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(437, 677)"/>
<path d=""  transform="translate(697, 677)"/>
<path d=""  transform="translate(697, 677)"/>
<path d=""  transform="translate(957, 677)"/>
<path d=""  transform="translate(1619, 677)"/>
<path d=""  transform="translate(1879, 677)"/>
<path d=""  transform="translate(2139, 677)"/>
<path d=""  transform="translate(2739, 677)"/>
<path d=""  transform="translate(2999, 677)"/>
<path d=""  transform="translate(3436, 677)"/>
<path d=""  transform="translate(3436, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳍 ‍ 𐳀  = 𐳍‍𐳀</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CCD.ltr=0+565|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CCD.ltr=9@-40,0+525|space=9+0|uni10CC0.ltr=11+444</pre>



<pre>Got     : uni10CCD.ltr=0+565|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CCD.ltr=9@-40,0+525|space=9+0|uni10CC0.ltr=11+444</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3850 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(565, 677)"/>
<path d=""  transform="translate(825, 677)"/>
<path d=""  transform="translate(825, 677)"/>
<path d=""  transform="translate(1085, 677)"/>
<path d=""  transform="translate(1529, 677)"/>
<path d=""  transform="translate(1789, 677)"/>
<path d=""  transform="translate(2049, 677)"/>
<path d=""  transform="translate(2621, 677)"/>
<path d=""  transform="translate(2841, 677)"/>
<path d=""  transform="translate(3406, 677)"/>
<path d=""  transform="translate(3406, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3878 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(565, 677)"/>
<path d=""  transform="translate(825, 677)"/>
<path d=""  transform="translate(825, 677)"/>
<path d=""  transform="translate(1085, 677)"/>
<path d=""  transform="translate(1529, 677)"/>
<path d=""  transform="translate(1789, 677)"/>
<path d=""  transform="translate(2049, 677)"/>
<path d=""  transform="translate(2649, 677)"/>
<path d=""  transform="translate(2869, 677)"/>
<path d=""  transform="translate(3434, 677)"/>
<path d=""  transform="translate(3434, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳍 ‍ 𐳉  = 𐳍‍𐳉</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CCD.ltr=0+565|space=1+260|space=1+0|space=3+260|uni10CC9.ltr=4+411|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CCD.ltr=9+565|space=9+0|uni10CC9.ltr=11+411</pre>



<pre>Got     : uni10CCD.ltr=0+565|space=1+260|space=1+0|space=3+260|uni10CC9.ltr=4+411|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CCD.ltr=9+565|space=9+0|uni10CC9.ltr=11+411</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3824 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(565, 677)"/>
<path d=""  transform="translate(825, 677)"/>
<path d=""  transform="translate(825, 677)"/>
<path d=""  transform="translate(1085, 677)"/>
<path d=""  transform="translate(1496, 677)"/>
<path d=""  transform="translate(1756, 677)"/>
<path d=""  transform="translate(2016, 677)"/>
<path d=""  transform="translate(2588, 677)"/>
<path d=""  transform="translate(2848, 677)"/>
<path d=""  transform="translate(3413, 677)"/>
<path d=""  transform="translate(3413, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3852 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(565, 677)"/>
<path d=""  transform="translate(825, 677)"/>
<path d=""  transform="translate(825, 677)"/>
<path d=""  transform="translate(1085, 677)"/>
<path d=""  transform="translate(1496, 677)"/>
<path d=""  transform="translate(1756, 677)"/>
<path d=""  transform="translate(2016, 677)"/>
<path d=""  transform="translate(2616, 677)"/>
<path d=""  transform="translate(2876, 677)"/>
<path d=""  transform="translate(3441, 677)"/>
<path d=""  transform="translate(3441, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳍 ‍ 𐳐  = 𐳍‍𐳐</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CCD.ltr=0+565|space=1+260|space=1+0|space=3+260|uni10CD0.ltr=4+452|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CCD.ltr=9+565|space=9+0|uni10CD0.ltr=11+452</pre>



<pre>Got     : uni10CCD.ltr=0+565|space=1+260|space=1+0|space=3+260|uni10CD0.ltr=4+452|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CCD.ltr=9+565|space=9+0|uni10CD0.ltr=11+452</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3906 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(565, 677)"/>
<path d=""  transform="translate(825, 677)"/>
<path d=""  transform="translate(825, 677)"/>
<path d=""  transform="translate(1085, 677)"/>
<path d=""  transform="translate(1537, 677)"/>
<path d=""  transform="translate(1797, 677)"/>
<path d=""  transform="translate(2057, 677)"/>
<path d=""  transform="translate(2629, 677)"/>
<path d=""  transform="translate(2889, 677)"/>
<path d=""  transform="translate(3454, 677)"/>
<path d=""  transform="translate(3454, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3934 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(565, 677)"/>
<path d=""  transform="translate(825, 677)"/>
<path d=""  transform="translate(825, 677)"/>
<path d=""  transform="translate(1085, 677)"/>
<path d=""  transform="translate(1537, 677)"/>
<path d=""  transform="translate(1797, 677)"/>
<path d=""  transform="translate(2057, 677)"/>
<path d=""  transform="translate(2657, 677)"/>
<path d=""  transform="translate(2917, 677)"/>
<path d=""  transform="translate(3482, 677)"/>
<path d=""  transform="translate(3482, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳍 ‍ 𐳛  = 𐳍‍𐳛</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CCD.ltr=0+565|space=1+260|space=1+0|space=3+260|uni10CDB.ltr=4+473|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CCD.ltr=9+565|space=9+0|uni10CDB.ltr=11+473</pre>



<pre>Got     : uni10CCD.ltr=0+565|space=1+260|space=1+0|space=3+260|uni10CDB.ltr=4+473|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CCD.ltr=9+565|space=9+0|uni10CDB.ltr=11+473</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3948 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(565, 677)"/>
<path d=""  transform="translate(825, 677)"/>
<path d=""  transform="translate(825, 677)"/>
<path d=""  transform="translate(1085, 677)"/>
<path d=""  transform="translate(1558, 677)"/>
<path d=""  transform="translate(1818, 677)"/>
<path d=""  transform="translate(2078, 677)"/>
<path d=""  transform="translate(2650, 677)"/>
<path d=""  transform="translate(2910, 677)"/>
<path d=""  transform="translate(3475, 677)"/>
<path d=""  transform="translate(3475, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3976 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(565, 677)"/>
<path d=""  transform="translate(825, 677)"/>
<path d=""  transform="translate(825, 677)"/>
<path d=""  transform="translate(1085, 677)"/>
<path d=""  transform="translate(1558, 677)"/>
<path d=""  transform="translate(1818, 677)"/>
<path d=""  transform="translate(2078, 677)"/>
<path d=""  transform="translate(2678, 677)"/>
<path d=""  transform="translate(2938, 677)"/>
<path d=""  transform="translate(3503, 677)"/>
<path d=""  transform="translate(3503, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳏 ‍ 𐳀  = 𐳏‍𐳀</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CCF.ltr=0+536|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CCF.ltr=9+536|space=9+0|uni10CC0.ltr=11+444</pre>



<pre>Got     : uni10CCF.ltr=0+536|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CCF.ltr=9+536|space=9+0|uni10CC0.ltr=11+444</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3832 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(536, 677)"/>
<path d=""  transform="translate(796, 677)"/>
<path d=""  transform="translate(796, 677)"/>
<path d=""  transform="translate(1056, 677)"/>
<path d=""  transform="translate(1500, 677)"/>
<path d=""  transform="translate(1760, 677)"/>
<path d=""  transform="translate(2020, 677)"/>
<path d=""  transform="translate(2592, 677)"/>
<path d=""  transform="translate(2852, 677)"/>
<path d=""  transform="translate(3388, 677)"/>
<path d=""  transform="translate(3388, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3860 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(536, 677)"/>
<path d=""  transform="translate(796, 677)"/>
<path d=""  transform="translate(796, 677)"/>
<path d=""  transform="translate(1056, 677)"/>
<path d=""  transform="translate(1500, 677)"/>
<path d=""  transform="translate(1760, 677)"/>
<path d=""  transform="translate(2020, 677)"/>
<path d=""  transform="translate(2620, 677)"/>
<path d=""  transform="translate(2880, 677)"/>
<path d=""  transform="translate(3416, 677)"/>
<path d=""  transform="translate(3416, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳏 ‍ 𐳉  = 𐳏‍𐳉</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CCF.ltr=0+536|space=1+260|space=1+0|space=3+260|uni10CC9.ltr=4+411|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CCF.ltr=9+536|space=9+0|uni10CC9.ltr=11+411</pre>



<pre>Got     : uni10CCF.ltr=0+536|space=1+260|space=1+0|space=3+260|uni10CC9.ltr=4+411|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CCF.ltr=9+536|space=9+0|uni10CC9.ltr=11+411</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3766 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(536, 677)"/>
<path d=""  transform="translate(796, 677)"/>
<path d=""  transform="translate(796, 677)"/>
<path d=""  transform="translate(1056, 677)"/>
<path d=""  transform="translate(1467, 677)"/>
<path d=""  transform="translate(1727, 677)"/>
<path d=""  transform="translate(1987, 677)"/>
<path d=""  transform="translate(2559, 677)"/>
<path d=""  transform="translate(2819, 677)"/>
<path d=""  transform="translate(3355, 677)"/>
<path d=""  transform="translate(3355, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3794 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(536, 677)"/>
<path d=""  transform="translate(796, 677)"/>
<path d=""  transform="translate(796, 677)"/>
<path d=""  transform="translate(1056, 677)"/>
<path d=""  transform="translate(1467, 677)"/>
<path d=""  transform="translate(1727, 677)"/>
<path d=""  transform="translate(1987, 677)"/>
<path d=""  transform="translate(2587, 677)"/>
<path d=""  transform="translate(2847, 677)"/>
<path d=""  transform="translate(3383, 677)"/>
<path d=""  transform="translate(3383, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳏 ‍ 𐳐  = 𐳏‍𐳐</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CCF.ltr=0+536|space=1+260|space=1+0|space=3+260|uni10CD0.ltr=4+452|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CCF.ltr=9+536|space=9+0|uni10CD0.ltr=11+452</pre>



<pre>Got     : uni10CCF.ltr=0+536|space=1+260|space=1+0|space=3+260|uni10CD0.ltr=4+452|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CCF.ltr=9+536|space=9+0|uni10CD0.ltr=11+452</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3848 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(536, 677)"/>
<path d=""  transform="translate(796, 677)"/>
<path d=""  transform="translate(796, 677)"/>
<path d=""  transform="translate(1056, 677)"/>
<path d=""  transform="translate(1508, 677)"/>
<path d=""  transform="translate(1768, 677)"/>
<path d=""  transform="translate(2028, 677)"/>
<path d=""  transform="translate(2600, 677)"/>
<path d=""  transform="translate(2860, 677)"/>
<path d=""  transform="translate(3396, 677)"/>
<path d=""  transform="translate(3396, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3876 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(536, 677)"/>
<path d=""  transform="translate(796, 677)"/>
<path d=""  transform="translate(796, 677)"/>
<path d=""  transform="translate(1056, 677)"/>
<path d=""  transform="translate(1508, 677)"/>
<path d=""  transform="translate(1768, 677)"/>
<path d=""  transform="translate(2028, 677)"/>
<path d=""  transform="translate(2628, 677)"/>
<path d=""  transform="translate(2888, 677)"/>
<path d=""  transform="translate(3424, 677)"/>
<path d=""  transform="translate(3424, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳏 ‍ 𐳛  = 𐳏‍𐳛</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CCF.ltr=0+536|space=1+260|space=1+0|space=3+260|uni10CDB.ltr=4+473|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CCF.ltr=9+536|space=9+0|uni10CDB.ltr=11+473</pre>



<pre>Got     : uni10CCF.ltr=0+536|space=1+260|space=1+0|space=3+260|uni10CDB.ltr=4+473|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CCF.ltr=9+536|space=9+0|uni10CDB.ltr=11+473</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3890 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(536, 677)"/>
<path d=""  transform="translate(796, 677)"/>
<path d=""  transform="translate(796, 677)"/>
<path d=""  transform="translate(1056, 677)"/>
<path d=""  transform="translate(1529, 677)"/>
<path d=""  transform="translate(1789, 677)"/>
<path d=""  transform="translate(2049, 677)"/>
<path d=""  transform="translate(2621, 677)"/>
<path d=""  transform="translate(2881, 677)"/>
<path d=""  transform="translate(3417, 677)"/>
<path d=""  transform="translate(3417, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3918 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(536, 677)"/>
<path d=""  transform="translate(796, 677)"/>
<path d=""  transform="translate(796, 677)"/>
<path d=""  transform="translate(1056, 677)"/>
<path d=""  transform="translate(1529, 677)"/>
<path d=""  transform="translate(1789, 677)"/>
<path d=""  transform="translate(2049, 677)"/>
<path d=""  transform="translate(2649, 677)"/>
<path d=""  transform="translate(2909, 677)"/>
<path d=""  transform="translate(3445, 677)"/>
<path d=""  transform="translate(3445, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳐 ‍ 𐳒  = 𐳐‍𐳒</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CD0.ltr=0+452|space=1+260|space=1+0|space=3+260|uni10CD2.ltr=4+407|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CD0.ltr=9+452|space=9+0|uni10CD2.ltr=11+407</pre>



<pre>Got     : uni10CD0.ltr=0+452|space=1+260|space=1+0|space=3+260|uni10CD2.ltr=4+407|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CD0.ltr=9+452|space=9+0|uni10CD2.ltr=11+407</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3590 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(452, 677)"/>
<path d=""  transform="translate(712, 677)"/>
<path d=""  transform="translate(712, 677)"/>
<path d=""  transform="translate(972, 677)"/>
<path d=""  transform="translate(1379, 677)"/>
<path d=""  transform="translate(1639, 677)"/>
<path d=""  transform="translate(1899, 677)"/>
<path d=""  transform="translate(2471, 677)"/>
<path d=""  transform="translate(2731, 677)"/>
<path d=""  transform="translate(3183, 677)"/>
<path d=""  transform="translate(3183, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3618 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(452, 677)"/>
<path d=""  transform="translate(712, 677)"/>
<path d=""  transform="translate(712, 677)"/>
<path d=""  transform="translate(972, 677)"/>
<path d=""  transform="translate(1379, 677)"/>
<path d=""  transform="translate(1639, 677)"/>
<path d=""  transform="translate(1899, 677)"/>
<path d=""  transform="translate(2499, 677)"/>
<path d=""  transform="translate(2759, 677)"/>
<path d=""  transform="translate(3211, 677)"/>
<path d=""  transform="translate(3211, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳐 ‍ 𐳦  = 𐳐‍𐳦</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CD0.ltr=0+452|space=1+260|space=1+0|space=3+260|uni10CE6.ltr=4+467|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CE6_10CD0.ltr=9+600</pre>



<pre>Got     : uni10CD0.ltr=0+452|space=1+260|space=1+0|space=3+260|uni10CE6.ltr=4+467|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CE6_10CD0.ltr=9+600</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3391 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(452, 677)"/>
<path d=""  transform="translate(712, 677)"/>
<path d=""  transform="translate(712, 677)"/>
<path d=""  transform="translate(972, 677)"/>
<path d=""  transform="translate(1439, 677)"/>
<path d=""  transform="translate(1699, 677)"/>
<path d=""  transform="translate(1959, 677)"/>
<path d=""  transform="translate(2531, 677)"/>
<path d=""  transform="translate(2791, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3419 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(452, 677)"/>
<path d=""  transform="translate(712, 677)"/>
<path d=""  transform="translate(712, 677)"/>
<path d=""  transform="translate(972, 677)"/>
<path d=""  transform="translate(1439, 677)"/>
<path d=""  transform="translate(1699, 677)"/>
<path d=""  transform="translate(1959, 677)"/>
<path d=""  transform="translate(2559, 677)"/>
<path d=""  transform="translate(2819, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳑 ‍ 𐳢 ‍ 𐳦  = 𐳑‍𐳢‍𐳦</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CD1.ltr=0+421|space=1+260|space=1+0|space=3+260|uni10CE2.ltr=4+627|space=5+260|space=5+0|space=7+260|uni10CE6.ltr=8+467|space=9+260|space=10+260|.notdef=11+600|space=12+260|uni10CD1.ltr=13+421|space=13+0|uni10CE2.ltr=15+627|space=15+0|uni10CE6.ltr=17+467</pre>



<pre>Got     : uni10CD1.ltr=0+421|space=1+260|space=1+0|space=3+260|uni10CE2.ltr=4+627|space=5+260|space=5+0|space=7+260|uni10CE6.ltr=8+467|space=9+260|space=10+260|equal=11+572|space=12+260|uni10CD1.ltr=13+421|space=13+0|uni10CE2.ltr=15+627|space=15+0|uni10CE6.ltr=17+467</pre>



<pre>                                                                                                                                                                ^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5422 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(421, 677)"/>
<path d=""  transform="translate(681, 677)"/>
<path d=""  transform="translate(681, 677)"/>
<path d=""  transform="translate(941, 677)"/>
<path d=""  transform="translate(1568, 677)"/>
<path d=""  transform="translate(1828, 677)"/>
<path d=""  transform="translate(1828, 677)"/>
<path d=""  transform="translate(2088, 677)"/>
<path d=""  transform="translate(2555, 677)"/>
<path d=""  transform="translate(2815, 677)"/>
<path d=""  transform="translate(3075, 677)"/>
<path d=""  transform="translate(3647, 677)"/>
<path d=""  transform="translate(3907, 677)"/>
<path d=""  transform="translate(4328, 677)"/>
<path d=""  transform="translate(4328, 677)"/>
<path d=""  transform="translate(4955, 677)"/>
<path d=""  transform="translate(4955, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5450 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(421, 677)"/>
<path d=""  transform="translate(681, 677)"/>
<path d=""  transform="translate(681, 677)"/>
<path d=""  transform="translate(941, 677)"/>
<path d=""  transform="translate(1568, 677)"/>
<path d=""  transform="translate(1828, 677)"/>
<path d=""  transform="translate(1828, 677)"/>
<path d=""  transform="translate(2088, 677)"/>
<path d=""  transform="translate(2555, 677)"/>
<path d=""  transform="translate(2815, 677)"/>
<path d=""  transform="translate(3075, 677)"/>
<path d=""  transform="translate(3675, 677)"/>
<path d=""  transform="translate(3935, 677)"/>
<path d=""  transform="translate(4356, 677)"/>
<path d=""  transform="translate(4356, 677)"/>
<path d=""  transform="translate(4983, 677)"/>
<path d=""  transform="translate(4983, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳑 ‍ 𐳦  = 𐳑‍𐳦</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CD1.ltr=0+421|space=1+260|space=1+0|space=3+260|uni10CE6.ltr=4+467|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CD1.ltr=9+421|space=9+0|uni10CE6.ltr=11+467</pre>



<pre>Got     : uni10CD1.ltr=0+421|space=1+260|space=1+0|space=3+260|uni10CE6.ltr=4+467|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CD1.ltr=9+421|space=9+0|uni10CE6.ltr=11+467</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3648 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(421, 677)"/>
<path d=""  transform="translate(681, 677)"/>
<path d=""  transform="translate(681, 677)"/>
<path d=""  transform="translate(941, 677)"/>
<path d=""  transform="translate(1408, 677)"/>
<path d=""  transform="translate(1668, 677)"/>
<path d=""  transform="translate(1928, 677)"/>
<path d=""  transform="translate(2500, 677)"/>
<path d=""  transform="translate(2760, 677)"/>
<path d=""  transform="translate(3181, 677)"/>
<path d=""  transform="translate(3181, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3676 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(421, 677)"/>
<path d=""  transform="translate(681, 677)"/>
<path d=""  transform="translate(681, 677)"/>
<path d=""  transform="translate(941, 677)"/>
<path d=""  transform="translate(1408, 677)"/>
<path d=""  transform="translate(1668, 677)"/>
<path d=""  transform="translate(1928, 677)"/>
<path d=""  transform="translate(2528, 677)"/>
<path d=""  transform="translate(2788, 677)"/>
<path d=""  transform="translate(3209, 677)"/>
<path d=""  transform="translate(3209, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳓 ‍ 𐳥  = 𐳓‍𐳥</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CD3.ltr=0+493|space=1+260|space=1+0|space=3+260|uni10CE5.ltr=4+277|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CD3.ltr=9+493|space=9+0|uni10CE5.ltr=11+277</pre>



<pre>Got     : uni10CD3.ltr=0+493|space=1+260|space=1+0|space=3+260|uni10CE5.ltr=4+277|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CD3.ltr=9+493|space=9+0|uni10CE5.ltr=11+277</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3412 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(493, 677)"/>
<path d=""  transform="translate(753, 677)"/>
<path d=""  transform="translate(753, 677)"/>
<path d=""  transform="translate(1013, 677)"/>
<path d=""  transform="translate(1290, 677)"/>
<path d=""  transform="translate(1550, 677)"/>
<path d=""  transform="translate(1810, 677)"/>
<path d=""  transform="translate(2382, 677)"/>
<path d=""  transform="translate(2642, 677)"/>
<path d=""  transform="translate(3135, 677)"/>
<path d=""  transform="translate(3135, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3440 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(493, 677)"/>
<path d=""  transform="translate(753, 677)"/>
<path d=""  transform="translate(753, 677)"/>
<path d=""  transform="translate(1013, 677)"/>
<path d=""  transform="translate(1290, 677)"/>
<path d=""  transform="translate(1550, 677)"/>
<path d=""  transform="translate(1810, 677)"/>
<path d=""  transform="translate(2410, 677)"/>
<path d=""  transform="translate(2670, 677)"/>
<path d=""  transform="translate(3163, 677)"/>
<path d=""  transform="translate(3163, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳓 ‍ 𐳮  = 𐳓‍𐳮</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CD3.ltr=0+493|space=1+260|space=1+0|space=3+260|uni10CEE.ltr=4+662|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CD3.ltr=9+493|space=9+0|uni10CEE.ltr=11+662</pre>



<pre>Got     : uni10CD3.ltr=0+493|space=1+260|space=1+0|space=3+260|uni10CEE.ltr=4+662|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CD3.ltr=9+493|space=9+0|uni10CEE.ltr=11+662</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4182 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(493, 677)"/>
<path d=""  transform="translate(753, 677)"/>
<path d=""  transform="translate(753, 677)"/>
<path d=""  transform="translate(1013, 677)"/>
<path d=""  transform="translate(1675, 677)"/>
<path d=""  transform="translate(1935, 677)"/>
<path d=""  transform="translate(2195, 677)"/>
<path d=""  transform="translate(2767, 677)"/>
<path d=""  transform="translate(3027, 677)"/>
<path d=""  transform="translate(3520, 677)"/>
<path d=""  transform="translate(3520, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4210 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(493, 677)"/>
<path d=""  transform="translate(753, 677)"/>
<path d=""  transform="translate(753, 677)"/>
<path d=""  transform="translate(1013, 677)"/>
<path d=""  transform="translate(1675, 677)"/>
<path d=""  transform="translate(1935, 677)"/>
<path d=""  transform="translate(2195, 677)"/>
<path d=""  transform="translate(2795, 677)"/>
<path d=""  transform="translate(3055, 677)"/>
<path d=""  transform="translate(3548, 677)"/>
<path d=""  transform="translate(3548, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳖 ‍ 𐳀  = 𐳖‍𐳀</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CD6.ltr=0+612|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CC0_10CD6.ltr=9+699</pre>



<pre>Got     : uni10CD6.ltr=0+612|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CC0_10CD6.ltr=9+699</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3627 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(612, 677)"/>
<path d=""  transform="translate(872, 677)"/>
<path d=""  transform="translate(872, 677)"/>
<path d=""  transform="translate(1132, 677)"/>
<path d=""  transform="translate(1576, 677)"/>
<path d=""  transform="translate(1836, 677)"/>
<path d=""  transform="translate(2096, 677)"/>
<path d=""  transform="translate(2668, 677)"/>
<path d=""  transform="translate(2928, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3655 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(612, 677)"/>
<path d=""  transform="translate(872, 677)"/>
<path d=""  transform="translate(872, 677)"/>
<path d=""  transform="translate(1132, 677)"/>
<path d=""  transform="translate(1576, 677)"/>
<path d=""  transform="translate(1836, 677)"/>
<path d=""  transform="translate(2096, 677)"/>
<path d=""  transform="translate(2696, 677)"/>
<path d=""  transform="translate(2956, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳖 ‍ 𐳁  = 𐳖‍𐳁</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CD6.ltr=0+612|space=1+260|space=1+0|space=3+260|uni10CC1.ltr=4+433|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CD6.ltr=9+612|space=9+0|uni10CC1.ltr=11+433</pre>



<pre>Got     : uni10CD6.ltr=0+612|space=1+260|space=1+0|space=3+260|uni10CC1.ltr=4+433|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CD6.ltr=9+612|space=9+0|uni10CC1.ltr=11+433</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3962 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(612, 677)"/>
<path d=""  transform="translate(872, 677)"/>
<path d=""  transform="translate(872, 677)"/>
<path d=""  transform="translate(1132, 677)"/>
<path d=""  transform="translate(1565, 677)"/>
<path d=""  transform="translate(1825, 677)"/>
<path d=""  transform="translate(2085, 677)"/>
<path d=""  transform="translate(2657, 677)"/>
<path d=""  transform="translate(2917, 677)"/>
<path d=""  transform="translate(3529, 677)"/>
<path d=""  transform="translate(3529, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3990 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(612, 677)"/>
<path d=""  transform="translate(872, 677)"/>
<path d=""  transform="translate(872, 677)"/>
<path d=""  transform="translate(1132, 677)"/>
<path d=""  transform="translate(1565, 677)"/>
<path d=""  transform="translate(1825, 677)"/>
<path d=""  transform="translate(2085, 677)"/>
<path d=""  transform="translate(2685, 677)"/>
<path d=""  transform="translate(2945, 677)"/>
<path d=""  transform="translate(3557, 677)"/>
<path d=""  transform="translate(3557, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳖 ‍ 𐳉  = 𐳖‍𐳉</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CD6.ltr=0+612|space=1+260|space=1+0|space=3+260|uni10CC9.ltr=4+411|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CD6.ltr=9+612|space=9+0|uni10CC9.ltr=11+411</pre>



<pre>Got     : uni10CD6.ltr=0+612|space=1+260|space=1+0|space=3+260|uni10CC9.ltr=4+411|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CD6.ltr=9+612|space=9+0|uni10CC9.ltr=11+411</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3918 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(612, 677)"/>
<path d=""  transform="translate(872, 677)"/>
<path d=""  transform="translate(872, 677)"/>
<path d=""  transform="translate(1132, 677)"/>
<path d=""  transform="translate(1543, 677)"/>
<path d=""  transform="translate(1803, 677)"/>
<path d=""  transform="translate(2063, 677)"/>
<path d=""  transform="translate(2635, 677)"/>
<path d=""  transform="translate(2895, 677)"/>
<path d=""  transform="translate(3507, 677)"/>
<path d=""  transform="translate(3507, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3946 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(612, 677)"/>
<path d=""  transform="translate(872, 677)"/>
<path d=""  transform="translate(872, 677)"/>
<path d=""  transform="translate(1132, 677)"/>
<path d=""  transform="translate(1543, 677)"/>
<path d=""  transform="translate(1803, 677)"/>
<path d=""  transform="translate(2063, 677)"/>
<path d=""  transform="translate(2663, 677)"/>
<path d=""  transform="translate(2923, 677)"/>
<path d=""  transform="translate(3535, 677)"/>
<path d=""  transform="translate(3535, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳖 ‍ 𐳛  = 𐳖‍𐳛</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CD6.ltr=0+612|space=1+260|space=1+0|space=3+260|uni10CDB.ltr=4+473|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CD6.ltr=9+612|space=9+0|uni10CDB.ltr=11+473</pre>



<pre>Got     : uni10CD6.ltr=0+612|space=1+260|space=1+0|space=3+260|uni10CDB.ltr=4+473|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CD6.ltr=9+612|space=9+0|uni10CDB.ltr=11+473</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4042 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(612, 677)"/>
<path d=""  transform="translate(872, 677)"/>
<path d=""  transform="translate(872, 677)"/>
<path d=""  transform="translate(1132, 677)"/>
<path d=""  transform="translate(1605, 677)"/>
<path d=""  transform="translate(1865, 677)"/>
<path d=""  transform="translate(2125, 677)"/>
<path d=""  transform="translate(2697, 677)"/>
<path d=""  transform="translate(2957, 677)"/>
<path d=""  transform="translate(3569, 677)"/>
<path d=""  transform="translate(3569, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4070 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(612, 677)"/>
<path d=""  transform="translate(872, 677)"/>
<path d=""  transform="translate(872, 677)"/>
<path d=""  transform="translate(1132, 677)"/>
<path d=""  transform="translate(1605, 677)"/>
<path d=""  transform="translate(1865, 677)"/>
<path d=""  transform="translate(2125, 677)"/>
<path d=""  transform="translate(2725, 677)"/>
<path d=""  transform="translate(2985, 677)"/>
<path d=""  transform="translate(3597, 677)"/>
<path d=""  transform="translate(3597, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳖 ‍ 𐳦  = 𐳖‍𐳦</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CD6.ltr=0+612|space=1+260|space=1+0|space=3+260|uni10CE6.ltr=4+467|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CD6.ltr=9@-60,0+552|space=9+0|uni10CE6.ltr=11+467</pre>



<pre>Got     : uni10CD6.ltr=0+612|space=1+260|space=1+0|space=3+260|uni10CE6.ltr=4+467|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CD6.ltr=9@-60,0+552|space=9+0|uni10CE6.ltr=11+467</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3970 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(612, 677)"/>
<path d=""  transform="translate(872, 677)"/>
<path d=""  transform="translate(872, 677)"/>
<path d=""  transform="translate(1132, 677)"/>
<path d=""  transform="translate(1599, 677)"/>
<path d=""  transform="translate(1859, 677)"/>
<path d=""  transform="translate(2119, 677)"/>
<path d=""  transform="translate(2691, 677)"/>
<path d=""  transform="translate(2891, 677)"/>
<path d=""  transform="translate(3503, 677)"/>
<path d=""  transform="translate(3503, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3998 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(612, 677)"/>
<path d=""  transform="translate(872, 677)"/>
<path d=""  transform="translate(872, 677)"/>
<path d=""  transform="translate(1132, 677)"/>
<path d=""  transform="translate(1599, 677)"/>
<path d=""  transform="translate(1859, 677)"/>
<path d=""  transform="translate(2119, 677)"/>
<path d=""  transform="translate(2719, 677)"/>
<path d=""  transform="translate(2919, 677)"/>
<path d=""  transform="translate(3531, 677)"/>
<path d=""  transform="translate(3531, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳙 ‍ 𐳀  = 𐳙‍𐳀</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CD9.ltr=0+420|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CD9.ltr=9+420|space=9+0|uni10CC0.ltr=11+444</pre>



<pre>Got     : uni10CD9.ltr=0+420|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CD9.ltr=9+420|space=9+0|uni10CC0.ltr=11+444</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3600 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(420, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(940, 677)"/>
<path d=""  transform="translate(1384, 677)"/>
<path d=""  transform="translate(1644, 677)"/>
<path d=""  transform="translate(1904, 677)"/>
<path d=""  transform="translate(2476, 677)"/>
<path d=""  transform="translate(2736, 677)"/>
<path d=""  transform="translate(3156, 677)"/>
<path d=""  transform="translate(3156, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3628 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(420, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(940, 677)"/>
<path d=""  transform="translate(1384, 677)"/>
<path d=""  transform="translate(1644, 677)"/>
<path d=""  transform="translate(1904, 677)"/>
<path d=""  transform="translate(2504, 677)"/>
<path d=""  transform="translate(2764, 677)"/>
<path d=""  transform="translate(3184, 677)"/>
<path d=""  transform="translate(3184, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳙 ‍ 𐳄  = 𐳙‍𐳄</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CD9.ltr=0+420|space=1+260|space=1+0|space=3+260|uni10CC4.ltr=4+447|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CD9.ltr=9+420|space=9+0|uni10CC4.ltr=11+447</pre>



<pre>Got     : uni10CD9.ltr=0+420|space=1+260|space=1+0|space=3+260|uni10CC4.ltr=4+447|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CD9.ltr=9+420|space=9+0|uni10CC4.ltr=11+447</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3606 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(420, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(940, 677)"/>
<path d=""  transform="translate(1387, 677)"/>
<path d=""  transform="translate(1647, 677)"/>
<path d=""  transform="translate(1907, 677)"/>
<path d=""  transform="translate(2479, 677)"/>
<path d=""  transform="translate(2739, 677)"/>
<path d=""  transform="translate(3159, 677)"/>
<path d=""  transform="translate(3159, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3634 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(420, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(940, 677)"/>
<path d=""  transform="translate(1387, 677)"/>
<path d=""  transform="translate(1647, 677)"/>
<path d=""  transform="translate(1907, 677)"/>
<path d=""  transform="translate(2507, 677)"/>
<path d=""  transform="translate(2767, 677)"/>
<path d=""  transform="translate(3187, 677)"/>
<path d=""  transform="translate(3187, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳙 ‍ 𐳇  = 𐳙‍𐳇</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CD9.ltr=0+420|space=1+260|space=1+0|space=3+260|uni10CC7.ltr=4+437|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CD9.ltr=9+420|space=9+0|uni10CC7.ltr=11+437</pre>



<pre>Got     : uni10CD9.ltr=0+420|space=1+260|space=1+0|space=3+260|uni10CC7.ltr=4+437|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CD9.ltr=9+420|space=9+0|uni10CC7.ltr=11+437</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3586 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(420, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(940, 677)"/>
<path d=""  transform="translate(1377, 677)"/>
<path d=""  transform="translate(1637, 677)"/>
<path d=""  transform="translate(1897, 677)"/>
<path d=""  transform="translate(2469, 677)"/>
<path d=""  transform="translate(2729, 677)"/>
<path d=""  transform="translate(3149, 677)"/>
<path d=""  transform="translate(3149, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3614 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(420, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(940, 677)"/>
<path d=""  transform="translate(1377, 677)"/>
<path d=""  transform="translate(1637, 677)"/>
<path d=""  transform="translate(1897, 677)"/>
<path d=""  transform="translate(2497, 677)"/>
<path d=""  transform="translate(2757, 677)"/>
<path d=""  transform="translate(3177, 677)"/>
<path d=""  transform="translate(3177, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳙 ‍ 𐳎  = 𐳙‍𐳎</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CD9.ltr=0+420|space=1+260|space=1+0|space=3+260|uni10CCE.ltr=4+450|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CD9.ltr=9+420|space=9+0|uni10CCE.ltr=11+450</pre>



<pre>Got     : uni10CD9.ltr=0+420|space=1+260|space=1+0|space=3+260|uni10CCE.ltr=4+450|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CD9.ltr=9+420|space=9+0|uni10CCE.ltr=11+450</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3612 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(420, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(940, 677)"/>
<path d=""  transform="translate(1390, 677)"/>
<path d=""  transform="translate(1650, 677)"/>
<path d=""  transform="translate(1910, 677)"/>
<path d=""  transform="translate(2482, 677)"/>
<path d=""  transform="translate(2742, 677)"/>
<path d=""  transform="translate(3162, 677)"/>
<path d=""  transform="translate(3162, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3640 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(420, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(940, 677)"/>
<path d=""  transform="translate(1390, 677)"/>
<path d=""  transform="translate(1650, 677)"/>
<path d=""  transform="translate(1910, 677)"/>
<path d=""  transform="translate(2510, 677)"/>
<path d=""  transform="translate(2770, 677)"/>
<path d=""  transform="translate(3190, 677)"/>
<path d=""  transform="translate(3190, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳙 ‍ 𐳐  = 𐳙‍𐳐</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CD9.ltr=0+420|space=1+260|space=1+0|space=3+260|uni10CD0.ltr=4+452|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CD9.ltr=9+420|space=9+0|uni10CD0.ltr=11+452</pre>



<pre>Got     : uni10CD9.ltr=0+420|space=1+260|space=1+0|space=3+260|uni10CD0.ltr=4+452|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CD9.ltr=9+420|space=9+0|uni10CD0.ltr=11+452</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3616 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(420, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(940, 677)"/>
<path d=""  transform="translate(1392, 677)"/>
<path d=""  transform="translate(1652, 677)"/>
<path d=""  transform="translate(1912, 677)"/>
<path d=""  transform="translate(2484, 677)"/>
<path d=""  transform="translate(2744, 677)"/>
<path d=""  transform="translate(3164, 677)"/>
<path d=""  transform="translate(3164, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3644 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(420, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(940, 677)"/>
<path d=""  transform="translate(1392, 677)"/>
<path d=""  transform="translate(1652, 677)"/>
<path d=""  transform="translate(1912, 677)"/>
<path d=""  transform="translate(2512, 677)"/>
<path d=""  transform="translate(2772, 677)"/>
<path d=""  transform="translate(3192, 677)"/>
<path d=""  transform="translate(3192, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳙 ‍ 𐳓  = 𐳙‍𐳓</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CD9.ltr=0+420|space=1+260|space=1+0|space=3+260|uni10CD3.ltr=4+493|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CD9.ltr=9+420|space=9+0|uni10CD3.ltr=11+493</pre>



<pre>Got     : uni10CD9.ltr=0+420|space=1+260|space=1+0|space=3+260|uni10CD3.ltr=4+493|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CD9.ltr=9+420|space=9+0|uni10CD3.ltr=11+493</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3698 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(420, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(940, 677)"/>
<path d=""  transform="translate(1433, 677)"/>
<path d=""  transform="translate(1693, 677)"/>
<path d=""  transform="translate(1953, 677)"/>
<path d=""  transform="translate(2525, 677)"/>
<path d=""  transform="translate(2785, 677)"/>
<path d=""  transform="translate(3205, 677)"/>
<path d=""  transform="translate(3205, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3726 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(420, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(940, 677)"/>
<path d=""  transform="translate(1433, 677)"/>
<path d=""  transform="translate(1693, 677)"/>
<path d=""  transform="translate(1953, 677)"/>
<path d=""  transform="translate(2553, 677)"/>
<path d=""  transform="translate(2813, 677)"/>
<path d=""  transform="translate(3233, 677)"/>
<path d=""  transform="translate(3233, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳙 ‍ 𐳠  = 𐳙‍𐳠</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CD9.ltr=0+420|space=1+260|space=1+0|space=3+260|uni10CE0.ltr=4+453|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CD9.ltr=9+420|space=9+0|uni10CE0.ltr=11+453</pre>



<pre>Got     : uni10CD9.ltr=0+420|space=1+260|space=1+0|space=3+260|uni10CE0.ltr=4+453|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CD9.ltr=9+420|space=9+0|uni10CE0.ltr=11+453</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3618 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(420, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(940, 677)"/>
<path d=""  transform="translate(1393, 677)"/>
<path d=""  transform="translate(1653, 677)"/>
<path d=""  transform="translate(1913, 677)"/>
<path d=""  transform="translate(2485, 677)"/>
<path d=""  transform="translate(2745, 677)"/>
<path d=""  transform="translate(3165, 677)"/>
<path d=""  transform="translate(3165, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3646 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(420, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(940, 677)"/>
<path d=""  transform="translate(1393, 677)"/>
<path d=""  transform="translate(1653, 677)"/>
<path d=""  transform="translate(1913, 677)"/>
<path d=""  transform="translate(2513, 677)"/>
<path d=""  transform="translate(2773, 677)"/>
<path d=""  transform="translate(3193, 677)"/>
<path d=""  transform="translate(3193, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳙 ‍ 𐳦  = 𐳙‍𐳦</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CD9.ltr=0+420|space=1+260|space=1+0|space=3+260|uni10CE6.ltr=4+467|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CD9.ltr=9@-40,0+380|space=9+0|uni10CE6.ltr=11+467</pre>



<pre>Got     : uni10CD9.ltr=0+420|space=1+260|space=1+0|space=3+260|uni10CE6.ltr=4+467|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CD9.ltr=9@-40,0+380|space=9+0|uni10CE6.ltr=11+467</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3606 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(420, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(940, 677)"/>
<path d=""  transform="translate(1407, 677)"/>
<path d=""  transform="translate(1667, 677)"/>
<path d=""  transform="translate(1927, 677)"/>
<path d=""  transform="translate(2499, 677)"/>
<path d=""  transform="translate(2719, 677)"/>
<path d=""  transform="translate(3139, 677)"/>
<path d=""  transform="translate(3139, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3634 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(420, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(680, 677)"/>
<path d=""  transform="translate(940, 677)"/>
<path d=""  transform="translate(1407, 677)"/>
<path d=""  transform="translate(1667, 677)"/>
<path d=""  transform="translate(1927, 677)"/>
<path d=""  transform="translate(2527, 677)"/>
<path d=""  transform="translate(2747, 677)"/>
<path d=""  transform="translate(3167, 677)"/>
<path d=""  transform="translate(3167, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳛 ‍ 𐳢  = 𐳛‍𐳢</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CDB.ltr=0+473|space=1+260|space=1+0|space=3+260|uni10CE2.ltr=4+627|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CE2_10CDB.ltr=9+740</pre>



<pre>Got     : uni10CDB.ltr=0+473|space=1+260|space=1+0|space=3+260|uni10CE2.ltr=4+627|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CE2_10CDB.ltr=9+740</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3712 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(473, 677)"/>
<path d=""  transform="translate(733, 677)"/>
<path d=""  transform="translate(733, 677)"/>
<path d=""  transform="translate(993, 677)"/>
<path d=""  transform="translate(1620, 677)"/>
<path d=""  transform="translate(1880, 677)"/>
<path d=""  transform="translate(2140, 677)"/>
<path d=""  transform="translate(2712, 677)"/>
<path d=""  transform="translate(2972, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3740 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(473, 677)"/>
<path d=""  transform="translate(733, 677)"/>
<path d=""  transform="translate(733, 677)"/>
<path d=""  transform="translate(993, 677)"/>
<path d=""  transform="translate(1620, 677)"/>
<path d=""  transform="translate(1880, 677)"/>
<path d=""  transform="translate(2140, 677)"/>
<path d=""  transform="translate(2740, 677)"/>
<path d=""  transform="translate(3000, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳢 ‍ 𐳀  = 𐳢‍𐳀</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CE2.ltr=0+627|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CC0_10CE2.ltr=9+792</pre>



<pre>Got     : uni10CE2.ltr=0+627|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CC0_10CE2.ltr=9+792</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3735 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(627, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(1147, 677)"/>
<path d=""  transform="translate(1591, 677)"/>
<path d=""  transform="translate(1851, 677)"/>
<path d=""  transform="translate(2111, 677)"/>
<path d=""  transform="translate(2683, 677)"/>
<path d=""  transform="translate(2943, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3763 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(627, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(1147, 677)"/>
<path d=""  transform="translate(1591, 677)"/>
<path d=""  transform="translate(1851, 677)"/>
<path d=""  transform="translate(2111, 677)"/>
<path d=""  transform="translate(2711, 677)"/>
<path d=""  transform="translate(2971, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳢 ‍ 𐳉  = 𐳢‍𐳉</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CE2.ltr=0+627|space=1+260|space=1+0|space=3+260|uni10CC9.ltr=4+411|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CE2.ltr=9+627|space=9+0|uni10CC9.ltr=11+411</pre>



<pre>Got     : uni10CE2.ltr=0+627|space=1+260|space=1+0|space=3+260|uni10CC9.ltr=4+411|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CE2.ltr=9+627|space=9+0|uni10CC9.ltr=11+411</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3948 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(627, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(1147, 677)"/>
<path d=""  transform="translate(1558, 677)"/>
<path d=""  transform="translate(1818, 677)"/>
<path d=""  transform="translate(2078, 677)"/>
<path d=""  transform="translate(2650, 677)"/>
<path d=""  transform="translate(2910, 677)"/>
<path d=""  transform="translate(3537, 677)"/>
<path d=""  transform="translate(3537, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3976 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(627, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(1147, 677)"/>
<path d=""  transform="translate(1558, 677)"/>
<path d=""  transform="translate(1818, 677)"/>
<path d=""  transform="translate(2078, 677)"/>
<path d=""  transform="translate(2678, 677)"/>
<path d=""  transform="translate(2938, 677)"/>
<path d=""  transform="translate(3565, 677)"/>
<path d=""  transform="translate(3565, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳢 ‍ 𐳐  = 𐳢‍𐳐</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CE2.ltr=0+627|space=1+260|space=1+0|space=3+260|uni10CD0.ltr=4+452|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CE2.ltr=9+627|space=9+0|uni10CD0.ltr=11+452</pre>



<pre>Got     : uni10CE2.ltr=0+627|space=1+260|space=1+0|space=3+260|uni10CD0.ltr=4+452|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CE2.ltr=9+627|space=9+0|uni10CD0.ltr=11+452</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4030 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(627, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(1147, 677)"/>
<path d=""  transform="translate(1599, 677)"/>
<path d=""  transform="translate(1859, 677)"/>
<path d=""  transform="translate(2119, 677)"/>
<path d=""  transform="translate(2691, 677)"/>
<path d=""  transform="translate(2951, 677)"/>
<path d=""  transform="translate(3578, 677)"/>
<path d=""  transform="translate(3578, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4058 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(627, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(1147, 677)"/>
<path d=""  transform="translate(1599, 677)"/>
<path d=""  transform="translate(1859, 677)"/>
<path d=""  transform="translate(2119, 677)"/>
<path d=""  transform="translate(2719, 677)"/>
<path d=""  transform="translate(2979, 677)"/>
<path d=""  transform="translate(3606, 677)"/>
<path d=""  transform="translate(3606, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳢 ‍ 𐳛  = 𐳢‍𐳛</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CE2.ltr=0+627|space=1+260|space=1+0|space=3+260|uni10CDB.ltr=4+473|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CDB_10CE2.ltr=9+740</pre>



<pre>Got     : uni10CE2.ltr=0+627|space=1+260|space=1+0|space=3+260|uni10CDB.ltr=4+473|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CDB_10CE2.ltr=9+740</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3712 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(627, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(1147, 677)"/>
<path d=""  transform="translate(1620, 677)"/>
<path d=""  transform="translate(1880, 677)"/>
<path d=""  transform="translate(2140, 677)"/>
<path d=""  transform="translate(2712, 677)"/>
<path d=""  transform="translate(2972, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3740 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(627, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(1147, 677)"/>
<path d=""  transform="translate(1620, 677)"/>
<path d=""  transform="translate(1880, 677)"/>
<path d=""  transform="translate(2140, 677)"/>
<path d=""  transform="translate(2740, 677)"/>
<path d=""  transform="translate(3000, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳢 ‍ 𐳦  = 𐳢‍𐳦</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CE2.ltr=0+627|space=1+260|space=1+0|space=3+260|uni10CE6.ltr=4+467|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CE2.ltr=9+627|space=9+0|uni10CE6.ltr=11+467</pre>



<pre>Got     : uni10CE2.ltr=0+627|space=1+260|space=1+0|space=3+260|uni10CE6.ltr=4+467|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CE2.ltr=9+627|space=9+0|uni10CE6.ltr=11+467</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4060 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(627, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(1147, 677)"/>
<path d=""  transform="translate(1614, 677)"/>
<path d=""  transform="translate(1874, 677)"/>
<path d=""  transform="translate(2134, 677)"/>
<path d=""  transform="translate(2706, 677)"/>
<path d=""  transform="translate(2966, 677)"/>
<path d=""  transform="translate(3593, 677)"/>
<path d=""  transform="translate(3593, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4088 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(627, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(1147, 677)"/>
<path d=""  transform="translate(1614, 677)"/>
<path d=""  transform="translate(1874, 677)"/>
<path d=""  transform="translate(2134, 677)"/>
<path d=""  transform="translate(2734, 677)"/>
<path d=""  transform="translate(2994, 677)"/>
<path d=""  transform="translate(3621, 677)"/>
<path d=""  transform="translate(3621, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳢 ‍ 𐳪  = 𐳢‍𐳪</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CE2.ltr=0+627|space=1+260|space=1+0|space=3+260|uni10CEA.ltr=4+662|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CEA_10CE2.ltr=9+932</pre>



<pre>Got     : uni10CE2.ltr=0+627|space=1+260|space=1+0|space=3+260|uni10CEA.ltr=4+662|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CEA_10CE2.ltr=9+932</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4093 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(627, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(1147, 677)"/>
<path d=""  transform="translate(1809, 677)"/>
<path d=""  transform="translate(2069, 677)"/>
<path d=""  transform="translate(2329, 677)"/>
<path d=""  transform="translate(2901, 677)"/>
<path d=""  transform="translate(3161, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4121 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(627, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(887, 677)"/>
<path d=""  transform="translate(1147, 677)"/>
<path d=""  transform="translate(1809, 677)"/>
<path d=""  transform="translate(2069, 677)"/>
<path d=""  transform="translate(2329, 677)"/>
<path d=""  transform="translate(2929, 677)"/>
<path d=""  transform="translate(3189, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳤 ‍ 𐳀  = 𐳤‍𐳀</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CE4.ltr=0+566|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CE4.ltr=9@-40,0+526|space=9+0|uni10CC0.ltr=11+444</pre>



<pre>Got     : uni10CE4.ltr=0+566|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CE4.ltr=9@-40,0+526|space=9+0|uni10CC0.ltr=11+444</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3852 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(566, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(1086, 677)"/>
<path d=""  transform="translate(1530, 677)"/>
<path d=""  transform="translate(1790, 677)"/>
<path d=""  transform="translate(2050, 677)"/>
<path d=""  transform="translate(2622, 677)"/>
<path d=""  transform="translate(2842, 677)"/>
<path d=""  transform="translate(3408, 677)"/>
<path d=""  transform="translate(3408, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3880 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(566, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(1086, 677)"/>
<path d=""  transform="translate(1530, 677)"/>
<path d=""  transform="translate(1790, 677)"/>
<path d=""  transform="translate(2050, 677)"/>
<path d=""  transform="translate(2650, 677)"/>
<path d=""  transform="translate(2870, 677)"/>
<path d=""  transform="translate(3436, 677)"/>
<path d=""  transform="translate(3436, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳤 ‍ 𐳉  = 𐳤‍𐳉</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CE4.ltr=0+566|space=1+260|space=1+0|space=3+260|uni10CC9.ltr=4+411|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CE4.ltr=9+566|space=9+0|uni10CC9.ltr=11+411</pre>



<pre>Got     : uni10CE4.ltr=0+566|space=1+260|space=1+0|space=3+260|uni10CC9.ltr=4+411|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CE4.ltr=9+566|space=9+0|uni10CC9.ltr=11+411</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3826 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(566, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(1086, 677)"/>
<path d=""  transform="translate(1497, 677)"/>
<path d=""  transform="translate(1757, 677)"/>
<path d=""  transform="translate(2017, 677)"/>
<path d=""  transform="translate(2589, 677)"/>
<path d=""  transform="translate(2849, 677)"/>
<path d=""  transform="translate(3415, 677)"/>
<path d=""  transform="translate(3415, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3854 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(566, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(1086, 677)"/>
<path d=""  transform="translate(1497, 677)"/>
<path d=""  transform="translate(1757, 677)"/>
<path d=""  transform="translate(2017, 677)"/>
<path d=""  transform="translate(2617, 677)"/>
<path d=""  transform="translate(2877, 677)"/>
<path d=""  transform="translate(3443, 677)"/>
<path d=""  transform="translate(3443, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳤 ‍ 𐳐  = 𐳤‍𐳐</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CE4.ltr=0+566|space=1+260|space=1+0|space=3+260|uni10CD0.ltr=4+452|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CE4.ltr=9+566|space=9+0|uni10CD0.ltr=11+452</pre>



<pre>Got     : uni10CE4.ltr=0+566|space=1+260|space=1+0|space=3+260|uni10CD0.ltr=4+452|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CE4.ltr=9+566|space=9+0|uni10CD0.ltr=11+452</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3908 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(566, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(1086, 677)"/>
<path d=""  transform="translate(1538, 677)"/>
<path d=""  transform="translate(1798, 677)"/>
<path d=""  transform="translate(2058, 677)"/>
<path d=""  transform="translate(2630, 677)"/>
<path d=""  transform="translate(2890, 677)"/>
<path d=""  transform="translate(3456, 677)"/>
<path d=""  transform="translate(3456, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3936 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(566, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(1086, 677)"/>
<path d=""  transform="translate(1538, 677)"/>
<path d=""  transform="translate(1798, 677)"/>
<path d=""  transform="translate(2058, 677)"/>
<path d=""  transform="translate(2658, 677)"/>
<path d=""  transform="translate(2918, 677)"/>
<path d=""  transform="translate(3484, 677)"/>
<path d=""  transform="translate(3484, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳤 ‍ 𐳓  = 𐳤‍𐳓</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CE4.ltr=0+566|space=1+260|space=1+0|space=3+260|uni10CD3.ltr=4+493|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CE4.ltr=9+566|space=9+0|uni10CD3.ltr=11+493</pre>



<pre>Got     : uni10CE4.ltr=0+566|space=1+260|space=1+0|space=3+260|uni10CD3.ltr=4+493|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CE4.ltr=9+566|space=9+0|uni10CD3.ltr=11+493</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3990 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(566, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(1086, 677)"/>
<path d=""  transform="translate(1579, 677)"/>
<path d=""  transform="translate(1839, 677)"/>
<path d=""  transform="translate(2099, 677)"/>
<path d=""  transform="translate(2671, 677)"/>
<path d=""  transform="translate(2931, 677)"/>
<path d=""  transform="translate(3497, 677)"/>
<path d=""  transform="translate(3497, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4018 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(566, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(1086, 677)"/>
<path d=""  transform="translate(1579, 677)"/>
<path d=""  transform="translate(1839, 677)"/>
<path d=""  transform="translate(2099, 677)"/>
<path d=""  transform="translate(2699, 677)"/>
<path d=""  transform="translate(2959, 677)"/>
<path d=""  transform="translate(3525, 677)"/>
<path d=""  transform="translate(3525, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳤 ‍ 𐳘  = 𐳤‍𐳘</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CE4.ltr=0+566|space=1+260|space=1+0|space=3+260|uni10CD8.ltr=4+481|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CE4.ltr=9+566|space=9+0|uni10CD8.ltr=11+481</pre>



<pre>Got     : uni10CE4.ltr=0+566|space=1+260|space=1+0|space=3+260|uni10CD8.ltr=4+481|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CE4.ltr=9+566|space=9+0|uni10CD8.ltr=11+481</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3966 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(566, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(1086, 677)"/>
<path d=""  transform="translate(1567, 677)"/>
<path d=""  transform="translate(1827, 677)"/>
<path d=""  transform="translate(2087, 677)"/>
<path d=""  transform="translate(2659, 677)"/>
<path d=""  transform="translate(2919, 677)"/>
<path d=""  transform="translate(3485, 677)"/>
<path d=""  transform="translate(3485, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3994 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(566, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(1086, 677)"/>
<path d=""  transform="translate(1567, 677)"/>
<path d=""  transform="translate(1827, 677)"/>
<path d=""  transform="translate(2087, 677)"/>
<path d=""  transform="translate(2687, 677)"/>
<path d=""  transform="translate(2947, 677)"/>
<path d=""  transform="translate(3513, 677)"/>
<path d=""  transform="translate(3513, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳤 ‍ 𐳛  = 𐳤‍𐳛</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CE4.ltr=0+566|space=1+260|space=1+0|space=3+260|uni10CDB.ltr=4+473|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CE4.ltr=9+566|space=9+0|uni10CDB.ltr=11+473</pre>



<pre>Got     : uni10CE4.ltr=0+566|space=1+260|space=1+0|space=3+260|uni10CDB.ltr=4+473|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CE4.ltr=9+566|space=9+0|uni10CDB.ltr=11+473</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3950 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(566, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(1086, 677)"/>
<path d=""  transform="translate(1559, 677)"/>
<path d=""  transform="translate(1819, 677)"/>
<path d=""  transform="translate(2079, 677)"/>
<path d=""  transform="translate(2651, 677)"/>
<path d=""  transform="translate(2911, 677)"/>
<path d=""  transform="translate(3477, 677)"/>
<path d=""  transform="translate(3477, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3978 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(566, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(1086, 677)"/>
<path d=""  transform="translate(1559, 677)"/>
<path d=""  transform="translate(1819, 677)"/>
<path d=""  transform="translate(2079, 677)"/>
<path d=""  transform="translate(2679, 677)"/>
<path d=""  transform="translate(2939, 677)"/>
<path d=""  transform="translate(3505, 677)"/>
<path d=""  transform="translate(3505, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳤 ‍ 𐳠  = 𐳤‍𐳠</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CE4.ltr=0+566|space=1+260|space=1+0|space=3+260|uni10CE0.ltr=4+453|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CE4.ltr=9+566|space=9+0|uni10CE0.ltr=11+453</pre>



<pre>Got     : uni10CE4.ltr=0+566|space=1+260|space=1+0|space=3+260|uni10CE0.ltr=4+453|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CE4.ltr=9+566|space=9+0|uni10CE0.ltr=11+453</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3910 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(566, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(1086, 677)"/>
<path d=""  transform="translate(1539, 677)"/>
<path d=""  transform="translate(1799, 677)"/>
<path d=""  transform="translate(2059, 677)"/>
<path d=""  transform="translate(2631, 677)"/>
<path d=""  transform="translate(2891, 677)"/>
<path d=""  transform="translate(3457, 677)"/>
<path d=""  transform="translate(3457, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3938 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(566, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(1086, 677)"/>
<path d=""  transform="translate(1539, 677)"/>
<path d=""  transform="translate(1799, 677)"/>
<path d=""  transform="translate(2059, 677)"/>
<path d=""  transform="translate(2659, 677)"/>
<path d=""  transform="translate(2919, 677)"/>
<path d=""  transform="translate(3485, 677)"/>
<path d=""  transform="translate(3485, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳤 ‍ 𐳦  = 𐳤‍𐳦</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CE4.ltr=0+566|space=1+260|space=1+0|space=3+260|uni10CE6.ltr=4+467|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CE4.ltr=9@-60,0+506|space=9+0|uni10CE6.ltr=11+467</pre>



<pre>Got     : uni10CE4.ltr=0+566|space=1+260|space=1+0|space=3+260|uni10CE6.ltr=4+467|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CE4.ltr=9@-60,0+506|space=9+0|uni10CE6.ltr=11+467</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3878 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(566, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(1086, 677)"/>
<path d=""  transform="translate(1553, 677)"/>
<path d=""  transform="translate(1813, 677)"/>
<path d=""  transform="translate(2073, 677)"/>
<path d=""  transform="translate(2645, 677)"/>
<path d=""  transform="translate(2845, 677)"/>
<path d=""  transform="translate(3411, 677)"/>
<path d=""  transform="translate(3411, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3906 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(566, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(826, 677)"/>
<path d=""  transform="translate(1086, 677)"/>
<path d=""  transform="translate(1553, 677)"/>
<path d=""  transform="translate(1813, 677)"/>
<path d=""  transform="translate(2073, 677)"/>
<path d=""  transform="translate(2673, 677)"/>
<path d=""  transform="translate(2873, 677)"/>
<path d=""  transform="translate(3439, 677)"/>
<path d=""  transform="translate(3439, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳥 ‍ 𐳦  = 𐳥‍𐳦</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CE5.ltr=0+277|space=1+260|space=1+0|space=3+260|uni10CE6.ltr=4+467|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CE5.ltr=9+277|space=9+0|uni10CE6.ltr=11+467</pre>



<pre>Got     : uni10CE5.ltr=0+277|space=1+260|space=1+0|space=3+260|uni10CE6.ltr=4+467|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CE5.ltr=9+277|space=9+0|uni10CE6.ltr=11+467</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3360 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(277, 677)"/>
<path d=""  transform="translate(537, 677)"/>
<path d=""  transform="translate(537, 677)"/>
<path d=""  transform="translate(797, 677)"/>
<path d=""  transform="translate(1264, 677)"/>
<path d=""  transform="translate(1524, 677)"/>
<path d=""  transform="translate(1784, 677)"/>
<path d=""  transform="translate(2356, 677)"/>
<path d=""  transform="translate(2616, 677)"/>
<path d=""  transform="translate(2893, 677)"/>
<path d=""  transform="translate(2893, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3388 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(277, 677)"/>
<path d=""  transform="translate(537, 677)"/>
<path d=""  transform="translate(537, 677)"/>
<path d=""  transform="translate(797, 677)"/>
<path d=""  transform="translate(1264, 677)"/>
<path d=""  transform="translate(1524, 677)"/>
<path d=""  transform="translate(1784, 677)"/>
<path d=""  transform="translate(2384, 677)"/>
<path d=""  transform="translate(2644, 677)"/>
<path d=""  transform="translate(2921, 677)"/>
<path d=""  transform="translate(2921, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳦 ‍ 𐳐  = 𐳦‍𐳐</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CE6.ltr=0+467|space=1+260|space=1+0|space=3+260|uni10CD0.ltr=4+452|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CD0_10CE6.ltr=9+559</pre>



<pre>Got     : uni10CE6.ltr=0+467|space=1+260|space=1+0|space=3+260|uni10CD0.ltr=4+452|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CD0_10CE6.ltr=9+559</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3350 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(467, 677)"/>
<path d=""  transform="translate(727, 677)"/>
<path d=""  transform="translate(727, 677)"/>
<path d=""  transform="translate(987, 677)"/>
<path d=""  transform="translate(1439, 677)"/>
<path d=""  transform="translate(1699, 677)"/>
<path d=""  transform="translate(1959, 677)"/>
<path d=""  transform="translate(2531, 677)"/>
<path d=""  transform="translate(2791, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3378 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(467, 677)"/>
<path d=""  transform="translate(727, 677)"/>
<path d=""  transform="translate(727, 677)"/>
<path d=""  transform="translate(987, 677)"/>
<path d=""  transform="translate(1439, 677)"/>
<path d=""  transform="translate(1699, 677)"/>
<path d=""  transform="translate(1959, 677)"/>
<path d=""  transform="translate(2559, 677)"/>
<path d=""  transform="translate(2819, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳨 ‍ 𐳀  = 𐳨‍𐳀</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CE8.ltr=0+538|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CE8.ltr=9@-10,0+528|space=9+0|uni10CC0.ltr=11+444</pre>



<pre>Got     : uni10CE8.ltr=0+538|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CE8.ltr=9@-10,0+528|space=9+0|uni10CC0.ltr=11+444</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3826 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(538, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(1058, 677)"/>
<path d=""  transform="translate(1502, 677)"/>
<path d=""  transform="translate(1762, 677)"/>
<path d=""  transform="translate(2022, 677)"/>
<path d=""  transform="translate(2594, 677)"/>
<path d=""  transform="translate(2844, 677)"/>
<path d=""  transform="translate(3382, 677)"/>
<path d=""  transform="translate(3382, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3854 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(538, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(798, 677)"/>
<path d=""  transform="translate(1058, 677)"/>
<path d=""  transform="translate(1502, 677)"/>
<path d=""  transform="translate(1762, 677)"/>
<path d=""  transform="translate(2022, 677)"/>
<path d=""  transform="translate(2622, 677)"/>
<path d=""  transform="translate(2872, 677)"/>
<path d=""  transform="translate(3410, 677)"/>
<path d=""  transform="translate(3410, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳪 ‍ 𐳖  = 𐳪‍𐳖</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CEA.ltr=0+662|space=1+260|space=1+0|space=3+260|uni10CD6.ltr=4+612|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CEA.ltr=9+662|space=9+0|uni10CD6.ltr=11+612</pre>



<pre>Got     : uni10CEA.ltr=0+662|space=1+260|space=1+0|space=3+260|uni10CD6.ltr=4+612|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CEA.ltr=9+662|space=9+0|uni10CD6.ltr=11+612</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4420 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(662, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(1182, 677)"/>
<path d=""  transform="translate(1794, 677)"/>
<path d=""  transform="translate(2054, 677)"/>
<path d=""  transform="translate(2314, 677)"/>
<path d=""  transform="translate(2886, 677)"/>
<path d=""  transform="translate(3146, 677)"/>
<path d=""  transform="translate(3808, 677)"/>
<path d=""  transform="translate(3808, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4448 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(662, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(1182, 677)"/>
<path d=""  transform="translate(1794, 677)"/>
<path d=""  transform="translate(2054, 677)"/>
<path d=""  transform="translate(2314, 677)"/>
<path d=""  transform="translate(2914, 677)"/>
<path d=""  transform="translate(3174, 677)"/>
<path d=""  transform="translate(3836, 677)"/>
<path d=""  transform="translate(3836, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳪 ‍ 𐳘  = 𐳪‍𐳘</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CEA.ltr=0+662|space=1+260|space=1+0|space=3+260|uni10CD8.ltr=4+481|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CEA.ltr=9+662|space=9+0|uni10CD8.ltr=11+481</pre>



<pre>Got     : uni10CEA.ltr=0+662|space=1+260|space=1+0|space=3+260|uni10CD8.ltr=4+481|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CEA.ltr=9+662|space=9+0|uni10CD8.ltr=11+481</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4158 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(662, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(1182, 677)"/>
<path d=""  transform="translate(1663, 677)"/>
<path d=""  transform="translate(1923, 677)"/>
<path d=""  transform="translate(2183, 677)"/>
<path d=""  transform="translate(2755, 677)"/>
<path d=""  transform="translate(3015, 677)"/>
<path d=""  transform="translate(3677, 677)"/>
<path d=""  transform="translate(3677, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4186 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(662, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(1182, 677)"/>
<path d=""  transform="translate(1663, 677)"/>
<path d=""  transform="translate(1923, 677)"/>
<path d=""  transform="translate(2183, 677)"/>
<path d=""  transform="translate(2783, 677)"/>
<path d=""  transform="translate(3043, 677)"/>
<path d=""  transform="translate(3705, 677)"/>
<path d=""  transform="translate(3705, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳪 ‍ 𐳢  = 𐳪‍𐳢</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CEA.ltr=0+662|space=1+260|space=1+0|space=3+260|uni10CE2.ltr=4+627|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CE2_10CEA.ltr=9+947</pre>



<pre>Got     : uni10CEA.ltr=0+662|space=1+260|space=1+0|space=3+260|uni10CE2.ltr=4+627|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CE2_10CEA.ltr=9+947</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4108 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(662, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(1182, 677)"/>
<path d=""  transform="translate(1809, 677)"/>
<path d=""  transform="translate(2069, 677)"/>
<path d=""  transform="translate(2329, 677)"/>
<path d=""  transform="translate(2901, 677)"/>
<path d=""  transform="translate(3161, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4136 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(662, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(1182, 677)"/>
<path d=""  transform="translate(1809, 677)"/>
<path d=""  transform="translate(2069, 677)"/>
<path d=""  transform="translate(2329, 677)"/>
<path d=""  transform="translate(2929, 677)"/>
<path d=""  transform="translate(3189, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳮 ‍ 𐳀  = 𐳮‍𐳀</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CEE.ltr=0+662|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CEE.ltr=9+662|space=9+0|uni10CC0.ltr=11+444</pre>



<pre>Got     : uni10CEE.ltr=0+662|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CEE.ltr=9+662|space=9+0|uni10CC0.ltr=11+444</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4084 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(662, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(1182, 677)"/>
<path d=""  transform="translate(1626, 677)"/>
<path d=""  transform="translate(1886, 677)"/>
<path d=""  transform="translate(2146, 677)"/>
<path d=""  transform="translate(2718, 677)"/>
<path d=""  transform="translate(2978, 677)"/>
<path d=""  transform="translate(3640, 677)"/>
<path d=""  transform="translate(3640, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4112 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(662, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(1182, 677)"/>
<path d=""  transform="translate(1626, 677)"/>
<path d=""  transform="translate(1886, 677)"/>
<path d=""  transform="translate(2146, 677)"/>
<path d=""  transform="translate(2746, 677)"/>
<path d=""  transform="translate(3006, 677)"/>
<path d=""  transform="translate(3668, 677)"/>
<path d=""  transform="translate(3668, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳮 ‍ 𐳀 ‍ 𐳢  = 𐳮‍𐳀‍𐳢</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CEE.ltr=0+662|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=5+0|space=7+260|uni10CE2.ltr=8+627|space=9+260|space=10+260|.notdef=11+600|space=12+260|uni10CEE.ltr=13+662|space=13+0|uni10CE2_10CC0.ltr=15+794</pre>



<pre>Got     : uni10CEE.ltr=0+662|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=5+0|space=7+260|uni10CE2.ltr=8+627|space=9+260|space=10+260|equal=11+572|space=12+260|uni10CEE.ltr=13+662|space=13+0|uni10CE2_10CC0.ltr=15+794</pre>



<pre>                                                                                                                                                                ^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5581 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(662, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(1182, 677)"/>
<path d=""  transform="translate(1626, 677)"/>
<path d=""  transform="translate(1886, 677)"/>
<path d=""  transform="translate(1886, 677)"/>
<path d=""  transform="translate(2146, 677)"/>
<path d=""  transform="translate(2773, 677)"/>
<path d=""  transform="translate(3033, 677)"/>
<path d=""  transform="translate(3293, 677)"/>
<path d=""  transform="translate(3865, 677)"/>
<path d=""  transform="translate(4125, 677)"/>
<path d=""  transform="translate(4787, 677)"/>
<path d=""  transform="translate(4787, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5609 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(662, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(1182, 677)"/>
<path d=""  transform="translate(1626, 677)"/>
<path d=""  transform="translate(1886, 677)"/>
<path d=""  transform="translate(1886, 677)"/>
<path d=""  transform="translate(2146, 677)"/>
<path d=""  transform="translate(2773, 677)"/>
<path d=""  transform="translate(3033, 677)"/>
<path d=""  transform="translate(3293, 677)"/>
<path d=""  transform="translate(3893, 677)"/>
<path d=""  transform="translate(4153, 677)"/>
<path d=""  transform="translate(4815, 677)"/>
<path d=""  transform="translate(4815, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳮 ‍ 𐳁 ‍ 𐳢  = 𐳮‍𐳁‍𐳢</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CEE.ltr=0+662|space=1+260|space=1+0|space=3+260|uni10CC1.ltr=4+433|space=5+260|space=5+0|space=7+260|uni10CE2.ltr=8+627|space=9+260|space=10+260|.notdef=11+600|space=12+260|uni10CEE.ltr=13+662|space=13+0|uni10CC1.ltr=15+433|space=15+0|uni10CE2.ltr=17+627</pre>



<pre>Got     : uni10CEE.ltr=0+662|space=1+260|space=1+0|space=3+260|uni10CC1.ltr=4+433|space=5+260|space=5+0|space=7+260|uni10CE2.ltr=8+627|space=9+260|space=10+260|equal=11+572|space=12+260|uni10CEE.ltr=13+662|space=13+0|uni10CC1.ltr=15+433|space=15+0|uni10CE2.ltr=17+627</pre>



<pre>                                                                                                                                                                ^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5836 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(662, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(1182, 677)"/>
<path d=""  transform="translate(1615, 677)"/>
<path d=""  transform="translate(1875, 677)"/>
<path d=""  transform="translate(1875, 677)"/>
<path d=""  transform="translate(2135, 677)"/>
<path d=""  transform="translate(2762, 677)"/>
<path d=""  transform="translate(3022, 677)"/>
<path d=""  transform="translate(3282, 677)"/>
<path d=""  transform="translate(3854, 677)"/>
<path d=""  transform="translate(4114, 677)"/>
<path d=""  transform="translate(4776, 677)"/>
<path d=""  transform="translate(4776, 677)"/>
<path d=""  transform="translate(5209, 677)"/>
<path d=""  transform="translate(5209, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5864 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(662, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(1182, 677)"/>
<path d=""  transform="translate(1615, 677)"/>
<path d=""  transform="translate(1875, 677)"/>
<path d=""  transform="translate(1875, 677)"/>
<path d=""  transform="translate(2135, 677)"/>
<path d=""  transform="translate(2762, 677)"/>
<path d=""  transform="translate(3022, 677)"/>
<path d=""  transform="translate(3282, 677)"/>
<path d=""  transform="translate(3882, 677)"/>
<path d=""  transform="translate(4142, 677)"/>
<path d=""  transform="translate(4804, 677)"/>
<path d=""  transform="translate(4804, 677)"/>
<path d=""  transform="translate(5237, 677)"/>
<path d=""  transform="translate(5237, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳮 ‍ 𐳘  = 𐳮‍𐳘</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CEE.ltr=0+662|space=1+260|space=1+0|space=3+260|uni10CD8.ltr=4+481|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CEE.ltr=9+662|space=9+0|uni10CD8.ltr=11+481</pre>



<pre>Got     : uni10CEE.ltr=0+662|space=1+260|space=1+0|space=3+260|uni10CD8.ltr=4+481|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CEE.ltr=9+662|space=9+0|uni10CD8.ltr=11+481</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4158 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(662, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(1182, 677)"/>
<path d=""  transform="translate(1663, 677)"/>
<path d=""  transform="translate(1923, 677)"/>
<path d=""  transform="translate(2183, 677)"/>
<path d=""  transform="translate(2755, 677)"/>
<path d=""  transform="translate(3015, 677)"/>
<path d=""  transform="translate(3677, 677)"/>
<path d=""  transform="translate(3677, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4186 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(662, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(1182, 677)"/>
<path d=""  transform="translate(1663, 677)"/>
<path d=""  transform="translate(1923, 677)"/>
<path d=""  transform="translate(2183, 677)"/>
<path d=""  transform="translate(2783, 677)"/>
<path d=""  transform="translate(3043, 677)"/>
<path d=""  transform="translate(3705, 677)"/>
<path d=""  transform="translate(3705, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳮 ‍ 𐳮  = 𐳮‍𐳮</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CEE.ltr=0+662|space=1+260|space=1+0|space=3+260|uni10CEE.ltr=4+662|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CEE_10CEE.ltr=9+662</pre>



<pre>Got     : uni10CEE.ltr=0+662|space=1+260|space=1+0|space=3+260|uni10CEE.ltr=4+662|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CEE_10CEE.ltr=9+662</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3858 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(662, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(1182, 677)"/>
<path d=""  transform="translate(1844, 677)"/>
<path d=""  transform="translate(2104, 677)"/>
<path d=""  transform="translate(2364, 677)"/>
<path d=""  transform="translate(2936, 677)"/>
<path d=""  transform="translate(3196, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3886 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(662, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(922, 677)"/>
<path d=""  transform="translate(1182, 677)"/>
<path d=""  transform="translate(1844, 677)"/>
<path d=""  transform="translate(2104, 677)"/>
<path d=""  transform="translate(2364, 677)"/>
<path d=""  transform="translate(2964, 677)"/>
<path d=""  transform="translate(3224, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳯 ‍ 𐳀  = 𐳯‍𐳀</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CEF.ltr=0+615|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CEF.ltr=9+615|space=9+0|uni10CC0.ltr=11+444</pre>



<pre>Got     : uni10CEF.ltr=0+615|space=1+260|space=1+0|space=3+260|uni10CC0.ltr=4+444|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CEF.ltr=9+615|space=9+0|uni10CC0.ltr=11+444</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3990 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(615, 677)"/>
<path d=""  transform="translate(875, 677)"/>
<path d=""  transform="translate(875, 677)"/>
<path d=""  transform="translate(1135, 677)"/>
<path d=""  transform="translate(1579, 677)"/>
<path d=""  transform="translate(1839, 677)"/>
<path d=""  transform="translate(2099, 677)"/>
<path d=""  transform="translate(2671, 677)"/>
<path d=""  transform="translate(2931, 677)"/>
<path d=""  transform="translate(3546, 677)"/>
<path d=""  transform="translate(3546, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4018 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(615, 677)"/>
<path d=""  transform="translate(875, 677)"/>
<path d=""  transform="translate(875, 677)"/>
<path d=""  transform="translate(1135, 677)"/>
<path d=""  transform="translate(1579, 677)"/>
<path d=""  transform="translate(1839, 677)"/>
<path d=""  transform="translate(2099, 677)"/>
<path d=""  transform="translate(2699, 677)"/>
<path d=""  transform="translate(2959, 677)"/>
<path d=""  transform="translate(3574, 677)"/>
<path d=""  transform="translate(3574, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳯 ‍ 𐳢  = 𐳯‍𐳢</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CEF.ltr=0+615|space=1+260|space=1+0|space=3+260|uni10CE2.ltr=4+627|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CEF.ltr=9+615|space=9+0|uni10CE2.ltr=11+627</pre>



<pre>Got     : uni10CEF.ltr=0+615|space=1+260|space=1+0|space=3+260|uni10CE2.ltr=4+627|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CEF.ltr=9+615|space=9+0|uni10CE2.ltr=11+627</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4356 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(615, 677)"/>
<path d=""  transform="translate(875, 677)"/>
<path d=""  transform="translate(875, 677)"/>
<path d=""  transform="translate(1135, 677)"/>
<path d=""  transform="translate(1762, 677)"/>
<path d=""  transform="translate(2022, 677)"/>
<path d=""  transform="translate(2282, 677)"/>
<path d=""  transform="translate(2854, 677)"/>
<path d=""  transform="translate(3114, 677)"/>
<path d=""  transform="translate(3729, 677)"/>
<path d=""  transform="translate(3729, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4384 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(615, 677)"/>
<path d=""  transform="translate(875, 677)"/>
<path d=""  transform="translate(875, 677)"/>
<path d=""  transform="translate(1135, 677)"/>
<path d=""  transform="translate(1762, 677)"/>
<path d=""  transform="translate(2022, 677)"/>
<path d=""  transform="translate(2282, 677)"/>
<path d=""  transform="translate(2882, 677)"/>
<path d=""  transform="translate(3142, 677)"/>
<path d=""  transform="translate(3757, 677)"/>
<path d=""  transform="translate(3757, 677)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐳯 ‍ 𐳦  = 𐳯‍𐳦</span> (fontdiff-OldHungarian.html)</li>


<pre>Expected: uni10CEF.ltr=0+615|space=1+260|space=1+0|space=3+260|uni10CE6.ltr=4+467|space=5+260|space=6+260|.notdef=7+600|space=8+260|uni10CEF.ltr=9+615|space=9+0|uni10CE6.ltr=11+467</pre>



<pre>Got     : uni10CEF.ltr=0+615|space=1+260|space=1+0|space=3+260|uni10CE6.ltr=4+467|space=5+260|space=6+260|equal=7+572|space=8+260|uni10CEF.ltr=9+615|space=9+0|uni10CE6.ltr=11+467</pre>



<pre>                                                                                                          +++++ ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4036 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(615, 677)"/>
<path d=""  transform="translate(875, 677)"/>
<path d=""  transform="translate(875, 677)"/>
<path d=""  transform="translate(1135, 677)"/>
<path d=""  transform="translate(1602, 677)"/>
<path d=""  transform="translate(1862, 677)"/>
<path d=""  transform="translate(2122, 677)"/>
<path d=""  transform="translate(2694, 677)"/>
<path d=""  transform="translate(2954, 677)"/>
<path d=""  transform="translate(3569, 677)"/>
<path d=""  transform="translate(3569, 677)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4064 2036" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 677)"/>
<path d=""  transform="translate(615, 677)"/>
<path d=""  transform="translate(875, 677)"/>
<path d=""  transform="translate(875, 677)"/>
<path d=""  transform="translate(1135, 677)"/>
<path d=""  transform="translate(1602, 677)"/>
<path d=""  transform="translate(1862, 677)"/>
<path d=""  transform="translate(2122, 677)"/>
<path d=""  transform="translate(2722, 677)"/>
<path d=""  transform="translate(2982, 677)"/>
<path d=""  transform="translate(3597, 677)"/>
<path d=""  transform="translate(3597, 677)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni10CC0 + ZWJ

	- ZWJ + uni10CE6

	- uni10CE6 + ZWJ

	- ZWJ + uni10CC2

	- uni10CC2 + ZWJ

	- ZWJ + uni10CC7

	- uni10CC7 + ZWJ

	- ZWJ + uni10CD6

	- uni10CD6 + ZWJ

	- ZWJ + uni10CE2 

	- And 87 more.

Use -F or --full-lists to disable shortening of long lists. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 commaaccent2 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<159.0,84.0>--<159.0,80.0>>

	* at (U+0040) contains a short segment B<<613.0,293.0>-<612.0,275.0>-<612.0,267.5>>

	* at (U+0040) contains a short segment B<<612.0,267.5>-<612.0,260.0>-<612.0,257.0>>

	* M (U+004D) contains a short segment L<<177.0,626.0>--<173.0,626.0>>

	* M (U+004D) contains a short segment L<<450.0,129.0>--<454.0,129.0>>

	* N (U+004E) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* N (U+004E) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* Q (U+0051) contains a short segment B<<416.0,-9.0>-<410.0,-9.0>-<403.5,-9.5>>

	* Q (U+0051) contains a short segment B<<403.5,-9.5>-<397.0,-10.0>-<391.0,-10.0>>

	* W (U+0057) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>> 

	* And 80 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni10CFD (U+10CFD): L<<243.0,183.0>--<240.0,600.0>> 

	* And uni10CFD (U+10CFD): L<<327.0,600.0>--<324.0,182.0>> [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 11 | 9 | 113 | 7 | 95 | 0 |
| 0% | 5% | 4% | 48% | 3% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**

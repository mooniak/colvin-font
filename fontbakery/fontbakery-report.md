## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[22] DadigamaDEV-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check glyphs do not have duplicate components which have the same x,y coordinates. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.glyf.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs have duplicate components which have the same x,y coordinates:
* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0}
* {'glyph': 'guillemotleft', 'component': 'guilsinglleft', 'x': 0, 'y': 0} and {'glyph': 'guillemotright', 'component': 'guilsinglright', 'x': 0, 'y': 0}</p>
 [code: found-duplicates]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoAscender (800) and hhea ascent (816) must be equal.</p>
 [code: ascender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>No GF glyphset was found to be supported &gt;80%, so language shaping support couldn't get checked.</p>
 [code: no-glyphset-supported]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set.</p>
 [code: missing]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.copyright.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2021 Damith Welikala&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left">Dadigama DEV</td>
<td align="left">Dadigama DEV</td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Regular</td>
<td align="left">Regular</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">Dadigama DEV Regular</td>
<td align="left">Dadigama DEV Regular</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left"><strong>CCMoscowT2</strong></td>
<td align="left"><strong>DadigamaDEV-Regular</strong></td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0024 (DOLLAR SIGN)


- 0x0025 (PERCENT SIGN)


- 0x0026 (AMPERSAND)


- 0x002B (PLUS SIGN)


- 0x0030 (DIGIT ZERO)


- 0x0031 (DIGIT ONE)


- 0x0032 (DIGIT TWO)


- 0x0033 (DIGIT THREE)


- 0x0034 (DIGIT FOUR)


- 0x0035 (DIGIT FIVE)


- 0x0036 (DIGIT SIX)


- 0x0037 (DIGIT SEVEN)


- 0x0038 (DIGIT EIGHT)


- 0x0039 (DIGIT NINE)


- 0x003C (LESS-THAN SIGN)


- 0x003D (EQUALS SIGN)


- 0x003E (GREATER-THAN SIGN)


- 0x0040 (COMMERCIAL AT)


- 0x0041 (LATIN CAPITAL LETTER A)


- 0x0042 (LATIN CAPITAL LETTER B)


- 0x0043 (LATIN CAPITAL LETTER C)


- 0x0044 (LATIN CAPITAL LETTER D)


- 0x0045 (LATIN CAPITAL LETTER E)


- 0x0046 (LATIN CAPITAL LETTER F)


- 0x0047 (LATIN CAPITAL LETTER G)


- 0x0048 (LATIN CAPITAL LETTER H)


- 0x0049 (LATIN CAPITAL LETTER I)


- 0x004A (LATIN CAPITAL LETTER J)


- 0x004B (LATIN CAPITAL LETTER K)


- 0x004C (LATIN CAPITAL LETTER L)


- 0x004D (LATIN CAPITAL LETTER M)


- 0x004E (LATIN CAPITAL LETTER N)


- 0x004F (LATIN CAPITAL LETTER O)


- 0x0050 (LATIN CAPITAL LETTER P)


- 0x0051 (LATIN CAPITAL LETTER Q)


- 0x0052 (LATIN CAPITAL LETTER R)


- 0x0053 (LATIN CAPITAL LETTER S)


- 0x0054 (LATIN CAPITAL LETTER T)


- 0x0055 (LATIN CAPITAL LETTER U)


- 0x0056 (LATIN CAPITAL LETTER V)


- 0x0057 (LATIN CAPITAL LETTER W)


- 0x0058 (LATIN CAPITAL LETTER X)


- 0x0059 (LATIN CAPITAL LETTER Y)


- 0x005A (LATIN CAPITAL LETTER Z)


- 0x005E (CIRCUMFLEX ACCENT)


- 0x0060 (GRAVE ACCENT)


- 0x0061 (LATIN SMALL LETTER A)


- 0x0062 (LATIN SMALL LETTER B)


- 0x0063 (LATIN SMALL LETTER C)


- 0x0064 (LATIN SMALL LETTER D)


- 0x0065 (LATIN SMALL LETTER E)


- 0x0066 (LATIN SMALL LETTER F)


- 0x0067 (LATIN SMALL LETTER G)


- 0x0068 (LATIN SMALL LETTER H)


- 0x0069 (LATIN SMALL LETTER I)


- 0x006A (LATIN SMALL LETTER J)


- 0x006B (LATIN SMALL LETTER K)


- 0x006C (LATIN SMALL LETTER L)


- 0x006D (LATIN SMALL LETTER M)


- 0x006E (LATIN SMALL LETTER N)


- 0x006F (LATIN SMALL LETTER O)


- 0x0070 (LATIN SMALL LETTER P)


- 0x0071 (LATIN SMALL LETTER Q)


- 0x0072 (LATIN SMALL LETTER R)


- 0x0073 (LATIN SMALL LETTER S)


- 0x0074 (LATIN SMALL LETTER T)


- 0x0075 (LATIN SMALL LETTER U)


- 0x0076 (LATIN SMALL LETTER V)


- 0x0077 (LATIN SMALL LETTER W)


- 0x0078 (LATIN SMALL LETTER X)


- 0x0079 (LATIN SMALL LETTER Y)


- 0x007A (LATIN SMALL LETTER Z)


- 0x007C (VERTICAL LINE)


- 0x007E (TILDE)


- 0x00A2 (CENT SIGN)


- 0x00A3 (POUND SIGN)


- 0x00A5 (YEN SIGN)


- 0x00A7 (SECTION SIGN)


- 0x00A8 (DIAERESIS)


- 0x00A9 (COPYRIGHT SIGN)


- 0x00AA (FEMININE ORDINAL INDICATOR)


- 0x00AE (REGISTERED SIGN)


- 0x00AF (MACRON)


- 0x00B0 (DEGREE SIGN)


- 0x00B4 (ACUTE ACCENT)


- 0x00B6 (PILCROW SIGN)


- 0x00B8 (CEDILLA)


- 0x00BA (MASCULINE ORDINAL INDICATOR)


- 0x00C0 (LATIN CAPITAL LETTER A WITH GRAVE)


- 0x00C1 (LATIN CAPITAL LETTER A WITH ACUTE)


- 0x00C2 (LATIN CAPITAL LETTER A WITH CIRCUMFLEX)


- 0x00C3 (LATIN CAPITAL LETTER A WITH TILDE)


- 0x00C4 (LATIN CAPITAL LETTER A WITH DIAERESIS)


- 0x00C5 (LATIN CAPITAL LETTER A WITH RING ABOVE)


- 0x00C6 (LATIN CAPITAL LETTER AE)


- 0x00C7 (LATIN CAPITAL LETTER C WITH CEDILLA)


- 0x00C8 (LATIN CAPITAL LETTER E WITH GRAVE)


- 0x00C9 (LATIN CAPITAL LETTER E WITH ACUTE)


- 0x00CA (LATIN CAPITAL LETTER E WITH CIRCUMFLEX)


- 0x00CB (LATIN CAPITAL LETTER E WITH DIAERESIS)


- 0x00CC (LATIN CAPITAL LETTER I WITH GRAVE)


- 0x00CD (LATIN CAPITAL LETTER I WITH ACUTE)


- 0x00CE (LATIN CAPITAL LETTER I WITH CIRCUMFLEX)


- 0x00CF (LATIN CAPITAL LETTER I WITH DIAERESIS)


- 0x00D0 (LATIN CAPITAL LETTER ETH)


- 0x00D1 (LATIN CAPITAL LETTER N WITH TILDE)


- 0x00D2 (LATIN CAPITAL LETTER O WITH GRAVE)


- 0x00D3 (LATIN CAPITAL LETTER O WITH ACUTE)


- 0x00D4 (LATIN CAPITAL LETTER O WITH CIRCUMFLEX)


- 0x00D5 (LATIN CAPITAL LETTER O WITH TILDE)


- 0x00D6 (LATIN CAPITAL LETTER O WITH DIAERESIS)


- 0x00D7 (MULTIPLICATION SIGN)


- 0x00D8 (LATIN CAPITAL LETTER O WITH STROKE)


- 0x00D9 (LATIN CAPITAL LETTER U WITH GRAVE)


- 0x00DA (LATIN CAPITAL LETTER U WITH ACUTE)


- 0x00DB (LATIN CAPITAL LETTER U WITH CIRCUMFLEX)


- 0x00DC (LATIN CAPITAL LETTER U WITH DIAERESIS)


- 0x00DD (LATIN CAPITAL LETTER Y WITH ACUTE)


- 0x00DE (LATIN CAPITAL LETTER THORN)


- 0x00DF (LATIN SMALL LETTER SHARP S)


- 0x00E0 (LATIN SMALL LETTER A WITH GRAVE)


- 0x00E1 (LATIN SMALL LETTER A WITH ACUTE)


- 0x00E2 (LATIN SMALL LETTER A WITH CIRCUMFLEX)


- 0x00E3 (LATIN SMALL LETTER A WITH TILDE)


- 0x00E4 (LATIN SMALL LETTER A WITH DIAERESIS)


- 0x00E5 (LATIN SMALL LETTER A WITH RING ABOVE)


- 0x00E6 (LATIN SMALL LETTER AE)


- 0x00E7 (LATIN SMALL LETTER C WITH CEDILLA)


- 0x00E8 (LATIN SMALL LETTER E WITH GRAVE)


- 0x00E9 (LATIN SMALL LETTER E WITH ACUTE)


- 0x00EA (LATIN SMALL LETTER E WITH CIRCUMFLEX)


- 0x00EB (LATIN SMALL LETTER E WITH DIAERESIS)


- 0x00EC (LATIN SMALL LETTER I WITH GRAVE)


- 0x00ED (LATIN SMALL LETTER I WITH ACUTE)


- 0x00EE (LATIN SMALL LETTER I WITH CIRCUMFLEX)


- 0x00EF (LATIN SMALL LETTER I WITH DIAERESIS)


- 0x00F0 (LATIN SMALL LETTER ETH)


- 0x00F1 (LATIN SMALL LETTER N WITH TILDE)


- 0x00F2 (LATIN SMALL LETTER O WITH GRAVE)


- 0x00F3 (LATIN SMALL LETTER O WITH ACUTE)


- 0x00F4 (LATIN SMALL LETTER O WITH CIRCUMFLEX)


- 0x00F5 (LATIN SMALL LETTER O WITH TILDE)


- 0x00F6 (LATIN SMALL LETTER O WITH DIAERESIS)


- 0x00F7 (DIVISION SIGN)


- 0x00F8 (LATIN SMALL LETTER O WITH STROKE)


- 0x00F9 (LATIN SMALL LETTER U WITH GRAVE)


- 0x00FA (LATIN SMALL LETTER U WITH ACUTE)


- 0x00FB (LATIN SMALL LETTER U WITH CIRCUMFLEX)


- 0x00FC (LATIN SMALL LETTER U WITH DIAERESIS)


- 0x00FD (LATIN SMALL LETTER Y WITH ACUTE)


- 0x00FE (LATIN SMALL LETTER THORN)


- 0x00FF (LATIN SMALL LETTER Y WITH DIAERESIS)


- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


- 0x0106 (LATIN CAPITAL LETTER C WITH ACUTE)


- 0x0107 (LATIN SMALL LETTER C WITH ACUTE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x0118 (LATIN CAPITAL LETTER E WITH OGONEK)


- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


- 0x0131 (LATIN SMALL LETTER DOTLESS I)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0141 (LATIN CAPITAL LETTER L WITH STROKE)


- 0x0142 (LATIN SMALL LETTER L WITH STROKE)


- 0x0143 (LATIN CAPITAL LETTER N WITH ACUTE)


- 0x0144 (LATIN SMALL LETTER N WITH ACUTE)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0152 (LATIN CAPITAL LIGATURE OE)


- 0x0153 (LATIN SMALL LIGATURE OE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015A (LATIN CAPITAL LETTER S WITH ACUTE)


- 0x015B (LATIN SMALL LETTER S WITH ACUTE)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0160 (LATIN CAPITAL LETTER S WITH CARON)


- 0x0161 (LATIN SMALL LETTER S WITH CARON)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0178 (LATIN CAPITAL LETTER Y WITH DIAERESIS)


- 0x0179 (LATIN CAPITAL LETTER Z WITH ACUTE)


- 0x017A (LATIN SMALL LETTER Z WITH ACUTE)


- 0x017B (LATIN CAPITAL LETTER Z WITH DOT ABOVE)


- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


- 0x017D (LATIN CAPITAL LETTER Z WITH CARON)


- 0x017E (LATIN SMALL LETTER Z WITH CARON)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


- 0x02C7 (CARON)


- 0x02D8 (BREVE)


- 0x02D9 (DOT ABOVE)


- 0x02DA (RING ABOVE)


- 0x02DB (OGONEK)


- 0x02DC (SMALL TILDE)


- 0x02DD (DOUBLE ACUTE ACCENT)


- 0x0300 (COMBINING GRAVE ACCENT)


- 0x0301 (COMBINING ACUTE ACCENT)


- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


- 0x0303 (COMBINING TILDE)


- 0x0304 (COMBINING MACRON)


- 0x0306 (COMBINING BREVE)


- 0x0307 (COMBINING DOT ABOVE)


- 0x0308 (COMBINING DIAERESIS)


- 0x030A (COMBINING RING ABOVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x030C (COMBINING CARON)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0327 (COMBINING CEDILLA)


- 0x0328 (COMBINING OGONEK)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)


- 0x20AC (EURO SIGN)


- 0x2122 (TRADE MARK SIGN)


- 0x2212 (MINUS SIGN)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Version format is correct in 'name' table? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The NameID.VERSION_STRING (nameID=5) value must follow the pattern &quot;Version X.Y&quot; with X.Y greater than or equal to 1.000. Current version string is: &quot;Version 0.001; ttfautohint (v1.8.4.7-5d5b)&quot;</p>
 [code: bad-version-strings]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font can render its own name. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>.notdef glyphs were found when attempting to render Dadigama DEV</p>
 [code: render-own-name]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1032 when it should be at least 1200</p>
 [code: bad-hhea-range]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check glyphs in mark glyph class are non-spacing. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following spacing glyphs may be in the GDEF mark glyph class by mistake:
sinAnusvara (U+0D82), sinMatraAa (U+0DCF), sinMatraAae (U+0DD1), sinMatraAe (U+0DD0), sinMatraAi (U+0DDB), sinMatraAu (U+0DDE), sinMatraE (U+0DD9), sinMatraEe (U+0DDA), sinMatraLl (U+0DF3), sinMatraLs (U+0DDF), sinMatraO (U+0DDC), sinMatraOo (U+0DDD), sinMatraR (U+0DD8), sinMatraRr (U+0DF2), sinVirama (U+0DCA) and sinVisarga (U+0D83)</p>
 [code: spacing-mark-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check GDEF mark glyph class doesn't have characters that are not marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following non-mark characters should not be in the GDEF mark glyph class:
U+0D82, U+0D83, U+0DCF, U+0DD0, U+0DD1, U+0DD8, U+0DD9, U+0DDA, U+0DDB, U+0DDC, U+0DDD, U+0DDE, U+0DDF, U+0DF2 and U+0DF3</p>
 [code: non-mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: uni00AD	Contours detected: 1	Expected: 0

- Glyph name: ellipsis	Contours detected: 5	Expected: 3

- Glyph name: ellipsis	Contours detected: 5	Expected: 3

- Glyph name: uni00AD	Contours detected: 1	Expected: 0
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- mooniak

- periodcentered.loclCAT

- sinDAe.ss01

- sinDda.virama

- sinDrI

- sinDrIi

- sinDra

- sinFRI

- sinFRIi

- sinNDRI

- sinNDRIi

- sinNdRa

- sinNdda

- sinRakar

- sinSsRI

- sinSsRIi
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* quotedbl (U+0022): L&lt;&lt;216.0,510.0&gt;--&lt;194.0,627.0&gt;&gt; -&gt; L&lt;&lt;194.0,627.0&gt;--&lt;185.0,675.0&gt;&gt;

* quotedblleft (U+201C): L&lt;&lt;216.0,510.0&gt;--&lt;194.0,627.0&gt;&gt; -&gt; L&lt;&lt;194.0,627.0&gt;--&lt;185.0,675.0&gt;&gt;

* quotedblright (U+201D): L&lt;&lt;216.0,510.0&gt;--&lt;194.0,627.0&gt;&gt; -&gt; L&lt;&lt;194.0,627.0&gt;--&lt;185.0,675.0&gt;&gt;

* sinNDhIi: L&lt;&lt;675.0,407.0&gt;--&lt;675.0,407.0&gt;&gt; -&gt; L&lt;&lt;675.0,407.0&gt;--&lt;675.0,407.0&gt;&gt;

* sinNThU: L&lt;&lt;644.0,353.0&gt;--&lt;644.0,353.0&gt;&gt; -&gt; L&lt;&lt;644.0,353.0&gt;--&lt;644.0,353.0&gt;&gt;

* sinTThU: L&lt;&lt;651.0,387.0&gt;--&lt;651.0,387.0&gt;&gt; -&gt; L&lt;&lt;651.0,387.0&gt;--&lt;651.0,387.0&gt;&gt;

* sinTThUu: L&lt;&lt;650.0,387.0&gt;--&lt;650.0,387.0&gt;&gt; -&gt; L&lt;&lt;650.0,387.0&gt;--&lt;650.0,387.0&gt;&gt;

* sinTTha: L&lt;&lt;651.0,387.0&gt;--&lt;651.0,387.0&gt;&gt; -&gt; L&lt;&lt;651.0,387.0&gt;--&lt;651.0,387.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* sinC.virama: B&lt;&lt;402.5,557.5&gt;-&lt;452.0,536.0&gt;-&lt;490.0,498.0&gt;&gt;/B&lt;&lt;490.0,498.0&gt;-&lt;451.0,560.0&gt;-&lt;399.5,596.0&gt;&gt; = 12.828782871455394

* sinCR.virama: B&lt;&lt;402.5,557.5&gt;-&lt;452.0,536.0&gt;-&lt;490.0,498.0&gt;&gt;/B&lt;&lt;490.0,498.0&gt;-&lt;451.0,560.0&gt;-&lt;399.5,596.0&gt;&gt; = 12.828782871455394

* sinD.virama: B&lt;&lt;373.5,-9.0&gt;-&lt;387.0,23.0&gt;-&lt;412.0,44.0&gt;&gt;/B&lt;&lt;412.0,44.0&gt;-&lt;388.0,28.0&gt;-&lt;345.0,12.5&gt;&gt; = 6.340191745909908

* sinDI: B&lt;&lt;373.5,-9.0&gt;-&lt;387.0,23.0&gt;-&lt;412.0,44.0&gt;&gt;/B&lt;&lt;412.0,44.0&gt;-&lt;388.0,28.0&gt;-&lt;345.0,12.5&gt;&gt; = 6.340191745909908

* sinDIi: B&lt;&lt;373.5,-9.0&gt;-&lt;387.0,23.0&gt;-&lt;412.0,44.0&gt;&gt;/B&lt;&lt;412.0,44.0&gt;-&lt;388.0,28.0&gt;-&lt;345.0,12.5&gt;&gt; = 6.340191745909908

* sinDa (U+0DAF): B&lt;&lt;373.5,-9.0&gt;-&lt;387.0,23.0&gt;-&lt;412.0,44.0&gt;&gt;/B&lt;&lt;412.0,44.0&gt;-&lt;388.0,28.0&gt;-&lt;345.0,12.5&gt;&gt; = 6.340191745909908

* sinDd.virama: B&lt;&lt;454.0,549.0&gt;-&lt;518.0,521.0&gt;-&lt;561.0,476.0&gt;&gt;/B&lt;&lt;561.0,476.0&gt;-&lt;517.0,552.0&gt;-&lt;457.0,594.5&gt;&gt; = 13.62946450555866

* sinDdR.virama: B&lt;&lt;454.0,549.0&gt;-&lt;518.0,521.0&gt;-&lt;561.0,476.0&gt;&gt;/B&lt;&lt;561.0,476.0&gt;-&lt;517.0,552.0&gt;-&lt;457.0,594.5&gt;&gt; = 13.62946450555866

* sinDh.virama: B&lt;&lt;470.5,551.0&gt;-&lt;527.0,526.0&gt;-&lt;569.0,483.0&gt;&gt;/B&lt;&lt;569.0,483.0&gt;-&lt;525.0,557.0&gt;-&lt;466.5,598.0&gt;&gt; = 13.590475400095416

* sinDhR.virama: B&lt;&lt;470.5,551.0&gt;-&lt;527.0,526.0&gt;-&lt;569.0,483.0&gt;&gt;/B&lt;&lt;569.0,483.0&gt;-&lt;525.0,557.0&gt;-&lt;466.5,598.0&gt;&gt; = 13.590475400095416

* sinDvocR: B&lt;&lt;373.5,-9.0&gt;-&lt;387.0,23.0&gt;-&lt;412.0,44.0&gt;&gt;/B&lt;&lt;412.0,44.0&gt;-&lt;388.0,28.0&gt;-&lt;345.0,12.5&gt;&gt; = 6.340191745909908

* sinDvocRr: B&lt;&lt;373.5,-9.0&gt;-&lt;387.0,23.0&gt;-&lt;412.0,44.0&gt;&gt;/B&lt;&lt;412.0,44.0&gt;-&lt;388.0,28.0&gt;-&lt;345.0,12.5&gt;&gt; = 6.340191745909908

* sinGUu: L&lt;&lt;445.0,-24.0&gt;--&lt;414.0,8.0&gt;&gt;/B&lt;&lt;414.0,8.0&gt;-&lt;417.0,6.0&gt;-&lt;425.0,5.5&gt;&gt; = 12.219312923219373

* sinJh.virama: B&lt;&lt;901.5,552.0&gt;-&lt;957.0,528.0&gt;-&lt;999.0,486.0&gt;&gt;/B&lt;&lt;999.0,486.0&gt;-&lt;955.0,559.0&gt;-&lt;896.5,599.0&gt;&gt; = 13.920960364920752

* sinJhR.virama: B&lt;&lt;901.5,552.0&gt;-&lt;957.0,528.0&gt;-&lt;999.0,486.0&gt;&gt;/B&lt;&lt;999.0,486.0&gt;-&lt;955.0,559.0&gt;-&lt;896.5,599.0&gt;&gt; = 13.920960364920752

* sinJny.virama: B&lt;&lt;741.5,-9.0&gt;-&lt;755.0,23.0&gt;-&lt;780.0,44.0&gt;&gt;/B&lt;&lt;780.0,44.0&gt;-&lt;756.0,28.0&gt;-&lt;713.5,12.5&gt;&gt; = 6.340191745909908

* sinJnyI: B&lt;&lt;749.5,-9.0&gt;-&lt;763.0,23.0&gt;-&lt;788.0,44.0&gt;&gt;/B&lt;&lt;788.0,44.0&gt;-&lt;764.0,28.0&gt;-&lt;721.5,12.5&gt;&gt; = 6.340191745909908

* sinJnyIi: B&lt;&lt;749.5,-9.0&gt;-&lt;763.0,23.0&gt;-&lt;788.0,44.0&gt;&gt;/B&lt;&lt;788.0,44.0&gt;-&lt;764.0,28.0&gt;-&lt;721.5,12.5&gt;&gt; = 6.340191745909908

* sinJnya (U+0DA5): B&lt;&lt;749.5,-9.0&gt;-&lt;763.0,23.0&gt;-&lt;788.0,44.0&gt;&gt;/B&lt;&lt;788.0,44.0&gt;-&lt;764.0,28.0&gt;-&lt;721.5,12.5&gt;&gt; = 6.340191745909908

* sinKSs.virama: L&lt;&lt;536.0,392.0&gt;--&lt;536.0,392.0&gt;&gt;/B&lt;&lt;536.0,392.0&gt;-&lt;503.0,399.0&gt;-&lt;466.0,399.0&gt;&gt; = 11.976132444203333

* sinKSsI: L&lt;&lt;512.0,392.0&gt;--&lt;512.0,392.0&gt;&gt;/B&lt;&lt;512.0,392.0&gt;-&lt;479.0,399.0&gt;-&lt;442.0,399.0&gt;&gt; = 11.976132444203333

* sinKSsIi: L&lt;&lt;551.0,392.0&gt;--&lt;551.0,392.0&gt;&gt;/B&lt;&lt;551.0,392.0&gt;-&lt;518.0,399.0&gt;-&lt;481.0,399.0&gt;&gt; = 11.976132444203333

* sinKSsU: L&lt;&lt;536.0,392.0&gt;--&lt;536.0,392.0&gt;&gt;/B&lt;&lt;536.0,392.0&gt;-&lt;503.0,399.0&gt;-&lt;466.0,399.0&gt;&gt; = 11.976132444203333

* sinKSsUu: L&lt;&lt;551.0,392.0&gt;--&lt;551.0,392.0&gt;&gt;/B&lt;&lt;551.0,392.0&gt;-&lt;518.0,399.0&gt;-&lt;481.0,399.0&gt;&gt; = 11.976132444203333

* sinKSsa: L&lt;&lt;551.0,392.0&gt;--&lt;551.0,392.0&gt;&gt;/B&lt;&lt;551.0,392.0&gt;-&lt;518.0,399.0&gt;-&lt;481.0,399.0&gt;&gt; = 11.976132444203333

* sinKUu: L&lt;&lt;646.0,-27.0&gt;--&lt;615.0,5.0&gt;&gt;/B&lt;&lt;615.0,5.0&gt;-&lt;618.0,3.0&gt;-&lt;626.0,2.5&gt;&gt; = 12.219312923219373

* sinKh.virama: B&lt;&lt;446.5,536.5&gt;-&lt;508.0,509.0&gt;-&lt;551.0,462.0&gt;&gt;/B&lt;&lt;551.0,462.0&gt;-&lt;506.0,544.0&gt;-&lt;444.5,589.5&gt;&gt; = 13.698074722884474

* sinKhR.virama: B&lt;&lt;446.5,536.5&gt;-&lt;508.0,509.0&gt;-&lt;551.0,462.0&gt;&gt;/B&lt;&lt;551.0,462.0&gt;-&lt;506.0,544.0&gt;-&lt;444.5,589.5&gt;&gt; = 13.698074722884474

* sinLlU: B&lt;&lt;71.0,247.0&gt;-&lt;71.0,167.0&gt;-&lt;121.0,111.0&gt;&gt;/B&lt;&lt;121.0,111.0&gt;-&lt;115.0,122.0&gt;-&lt;110.0,138.5&gt;&gt; = 13.149840037932645

* sinLlUu: B&lt;&lt;71.0,247.0&gt;-&lt;71.0,167.0&gt;-&lt;121.0,111.0&gt;&gt;/B&lt;&lt;121.0,111.0&gt;-&lt;115.0,122.0&gt;-&lt;110.0,138.5&gt;&gt; = 13.149840037932645

* sinM.virama: B&lt;&lt;448.0,550.0&gt;-&lt;500.0,529.0&gt;-&lt;538.0,492.0&gt;&gt;/B&lt;&lt;538.0,492.0&gt;-&lt;494.0,561.0&gt;-&lt;437.0,599.0&gt;&gt; = 13.239008173138934

* sinMR.virama: B&lt;&lt;448.0,550.0&gt;-&lt;500.0,529.0&gt;-&lt;538.0,492.0&gt;&gt;/B&lt;&lt;538.0,492.0&gt;-&lt;494.0,561.0&gt;-&lt;437.0,599.0&gt;&gt; = 13.239008173138934

* sinMatraUu.alt1: L&lt;&lt;-47.0,-29.0&gt;--&lt;-78.0,3.0&gt;&gt;/B&lt;&lt;-78.0,3.0&gt;-&lt;-75.0,1.0&gt;-&lt;-67.0,0.5&gt;&gt; = 12.219312923219373

* sinMb.virama: B&lt;&lt;451.0,555.5&gt;-&lt;507.0,537.0&gt;-&lt;552.0,498.0&gt;&gt;/B&lt;&lt;552.0,498.0&gt;-&lt;503.0,563.0&gt;-&lt;438.5,599.0&gt;&gt; = 12.07494354637176

* sinND.virama: B&lt;&lt;816.5,-9.0&gt;-&lt;830.0,23.0&gt;-&lt;855.0,44.0&gt;&gt;/B&lt;&lt;855.0,44.0&gt;-&lt;831.0,28.0&gt;-&lt;788.0,12.5&gt;&gt; = 6.340191745909908

* sinNDI: B&lt;&lt;816.5,-9.0&gt;-&lt;830.0,23.0&gt;-&lt;855.0,44.0&gt;&gt;/B&lt;&lt;855.0,44.0&gt;-&lt;831.0,28.0&gt;-&lt;788.0,12.5&gt;&gt; = 6.340191745909908

* sinNDIi: B&lt;&lt;816.5,-9.0&gt;-&lt;830.0,23.0&gt;-&lt;855.0,44.0&gt;&gt;/B&lt;&lt;855.0,44.0&gt;-&lt;831.0,28.0&gt;-&lt;788.0,12.5&gt;&gt; = 6.340191745909908

* sinNDa: B&lt;&lt;816.5,-9.0&gt;-&lt;830.0,23.0&gt;-&lt;855.0,44.0&gt;&gt;/B&lt;&lt;855.0,44.0&gt;-&lt;831.0,28.0&gt;-&lt;788.0,12.5&gt;&gt; = 6.340191745909908

* sinNDh.virama: B&lt;&lt;903.5,551.0&gt;-&lt;960.0,526.0&gt;-&lt;1002.0,483.0&gt;&gt;/B&lt;&lt;1002.0,483.0&gt;-&lt;958.0,557.0&gt;-&lt;899.5,598.0&gt;&gt; = 13.590475400095416

* sinNVU: L&lt;&lt;510.0,404.0&gt;--&lt;510.0,404.0&gt;&gt;/B&lt;&lt;510.0,404.0&gt;-&lt;466.0,403.0&gt;-&lt;421.5,385.0&gt;&gt; = 1.3019526725787232

* sinNd.virama: B&lt;&lt;398.5,-6.0&gt;-&lt;410.0,24.0&gt;-&lt;432.0,49.0&gt;&gt;/B&lt;&lt;432.0,49.0&gt;-&lt;411.0,25.0&gt;-&lt;371.5,12.5&gt;&gt; = 0.16185205398348554

* sinNd.virama: B&lt;&lt;69.0,233.0&gt;-&lt;69.0,216.0&gt;-&lt;71.0,201.0&gt;&gt;/B&lt;&lt;71.0,201.0&gt;-&lt;77.0,280.0&gt;-&lt;138.0,308.5&gt;&gt; = 11.937883320280813

* sinNdI: B&lt;&lt;398.5,-6.0&gt;-&lt;410.0,24.0&gt;-&lt;432.0,49.0&gt;&gt;/B&lt;&lt;432.0,49.0&gt;-&lt;411.0,25.0&gt;-&lt;371.5,12.5&gt;&gt; = 0.16185205398348554

* sinNdI: B&lt;&lt;69.0,233.0&gt;-&lt;69.0,216.0&gt;-&lt;71.0,201.0&gt;&gt;/B&lt;&lt;71.0,201.0&gt;-&lt;77.0,280.0&gt;-&lt;138.0,308.5&gt;&gt; = 11.937883320280813

* sinNdIi: B&lt;&lt;398.5,-6.0&gt;-&lt;410.0,24.0&gt;-&lt;432.0,49.0&gt;&gt;/B&lt;&lt;432.0,49.0&gt;-&lt;411.0,25.0&gt;-&lt;371.5,12.5&gt;&gt; = 0.16185205398348554

* sinNdIi: B&lt;&lt;69.0,233.0&gt;-&lt;69.0,216.0&gt;-&lt;71.0,201.0&gt;&gt;/B&lt;&lt;71.0,201.0&gt;-&lt;77.0,280.0&gt;-&lt;138.0,308.5&gt;&gt; = 11.937883320280813

* sinNda (U+0DB3): B&lt;&lt;398.5,-6.0&gt;-&lt;410.0,24.0&gt;-&lt;432.0,49.0&gt;&gt;/B&lt;&lt;432.0,49.0&gt;-&lt;411.0,25.0&gt;-&lt;371.5,12.5&gt;&gt; = 0.16185205398348554

* sinNda (U+0DB3): B&lt;&lt;69.0,233.0&gt;-&lt;69.0,216.0&gt;-&lt;71.0,201.0&gt;&gt;/B&lt;&lt;71.0,201.0&gt;-&lt;77.0,280.0&gt;-&lt;138.0,308.5&gt;&gt; = 11.937883320280813

* sinNndd.virama: B&lt;&lt;488.0,549.0&gt;-&lt;552.0,521.0&gt;-&lt;595.0,476.0&gt;&gt;/B&lt;&lt;595.0,476.0&gt;-&lt;551.0,552.0&gt;-&lt;491.0,594.5&gt;&gt; = 13.62946450555866

* sinNngUu: L&lt;&lt;503.0,-27.0&gt;--&lt;472.0,5.0&gt;&gt;/B&lt;&lt;472.0,5.0&gt;-&lt;475.0,3.0&gt;-&lt;483.0,2.5&gt;&gt; = 12.219312923219373

* sinNy.virama: B&lt;&lt;940.0,-9.0&gt;-&lt;954.0,23.0&gt;-&lt;978.0,44.0&gt;&gt;/B&lt;&lt;978.0,44.0&gt;-&lt;955.0,28.0&gt;-&lt;912.0,12.5&gt;&gt; = 6.361436008752841

* sinNyI: B&lt;&lt;937.0,-9.0&gt;-&lt;951.0,23.0&gt;-&lt;975.0,44.0&gt;&gt;/B&lt;&lt;975.0,44.0&gt;-&lt;952.0,28.0&gt;-&lt;909.0,12.5&gt;&gt; = 6.361436008752841

* sinNyIi: B&lt;&lt;940.0,-9.0&gt;-&lt;954.0,23.0&gt;-&lt;978.0,44.0&gt;&gt;/B&lt;&lt;978.0,44.0&gt;-&lt;955.0,28.0&gt;-&lt;912.0,12.5&gt;&gt; = 6.361436008752841

* sinNya (U+0DA4): B&lt;&lt;940.0,-9.0&gt;-&lt;954.0,23.0&gt;-&lt;978.0,44.0&gt;&gt;/B&lt;&lt;978.0,44.0&gt;-&lt;955.0,28.0&gt;-&lt;912.0,12.5&gt;&gt; = 6.361436008752841

* sinOo (U+0D95): B&lt;&lt;454.0,558.0&gt;-&lt;513.0,540.0&gt;-&lt;559.0,496.0&gt;&gt;/B&lt;&lt;559.0,496.0&gt;-&lt;516.0,563.0&gt;-&lt;459.5,600.0&gt;&gt; = 13.581045837484632

* sinPhI: B&lt;&lt;380.0,544.5&gt;-&lt;407.0,521.0&gt;-&lt;429.0,496.0&gt;&gt;/L&lt;&lt;429.0,496.0&gt;--&lt;425.0,503.0&gt;&gt; = 11.602895922751435

* sinRAe: B&lt;&lt;470.0,381.5&gt;-&lt;504.0,343.0&gt;-&lt;516.0,289.0&gt;&gt;/L&lt;&lt;516.0,289.0&gt;--&lt;516.0,672.0&gt;&gt; = 12.528807709151492

* sinRAe: L&lt;&lt;516.0,94.0&gt;--&lt;516.0,189.0&gt;&gt;/B&lt;&lt;516.0,189.0&gt;-&lt;504.0,139.0&gt;-&lt;470.5,96.0&gt;&gt; = 13.495733280795811

* sinShI: B&lt;&lt;87.0,393.0&gt;-&lt;135.0,460.0&gt;-&lt;234.0,477.0&gt;&gt;/B&lt;&lt;234.0,477.0&gt;-&lt;210.0,478.0&gt;-&lt;184.0,486.5&gt;&gt; = 12.129585317425956

* sinShRI: B&lt;&lt;78.0,393.0&gt;-&lt;126.0,460.0&gt;-&lt;225.0,477.0&gt;&gt;/B&lt;&lt;225.0,477.0&gt;-&lt;201.0,478.0&gt;-&lt;175.0,486.5&gt;&gt; = 12.129585317425956

* sinTTh.virama: B&lt;&lt;232.0,328.5&gt;-&lt;215.0,312.0&gt;-&lt;209.0,306.0&gt;&gt;/B&lt;&lt;209.0,306.0&gt;-&lt;223.0,317.0&gt;-&lt;254.5,328.0&gt;&gt; = 6.842773412630916

* sinTThI: B&lt;&lt;225.0,327.5&gt;-&lt;208.0,311.0&gt;-&lt;202.0,305.0&gt;&gt;/B&lt;&lt;202.0,305.0&gt;-&lt;216.0,316.0&gt;-&lt;247.5,327.0&gt;&gt; = 6.842773412630916

* sinTThIi: B&lt;&lt;231.0,327.5&gt;-&lt;214.0,311.0&gt;-&lt;208.0,305.0&gt;&gt;/B&lt;&lt;208.0,305.0&gt;-&lt;222.0,316.0&gt;-&lt;253.5,327.0&gt;&gt; = 6.842773412630916

* sinTThU: B&lt;&lt;233.0,327.5&gt;-&lt;216.0,311.0&gt;-&lt;210.0,305.0&gt;&gt;/B&lt;&lt;210.0,305.0&gt;-&lt;224.0,316.0&gt;-&lt;255.5,327.0&gt;&gt; = 6.842773412630916

* sinTThUu: B&lt;&lt;228.0,327.5&gt;-&lt;211.0,311.0&gt;-&lt;205.0,305.0&gt;&gt;/B&lt;&lt;205.0,305.0&gt;-&lt;219.0,316.0&gt;-&lt;250.5,327.0&gt;&gt; = 6.842773412630916

* sinTTha: B&lt;&lt;233.0,327.5&gt;-&lt;216.0,311.0&gt;-&lt;210.0,305.0&gt;&gt;/B&lt;&lt;210.0,305.0&gt;-&lt;224.0,316.0&gt;-&lt;255.5,327.0&gt;&gt; = 6.842773412630916

* sinTUu: L&lt;&lt;556.0,-17.0&gt;--&lt;525.0,15.0&gt;&gt;/B&lt;&lt;525.0,15.0&gt;-&lt;528.0,13.0&gt;-&lt;536.0,12.5&gt;&gt; = 12.219312923219373

* sinTVa: L&lt;&lt;549.0,367.0&gt;--&lt;549.0,367.0&gt;&gt;/B&lt;&lt;549.0,367.0&gt;-&lt;531.0,368.0&gt;-&lt;520.0,381.0&gt;&gt; = 3.1798301198641643

* sinTtTthUu: L&lt;&lt;712.0,122.0&gt;--&lt;712.0,138.0&gt;&gt;/B&lt;&lt;712.0,138.0&gt;-&lt;711.0,134.0&gt;-&lt;701.0,120.5&gt;&gt; = 14.036243467926484

* sinYU.post: B&lt;&lt;507.0,175.0&gt;-&lt;507.0,143.0&gt;-&lt;495.0,114.0&gt;&gt;/B&lt;&lt;495.0,114.0&gt;-&lt;499.0,120.0&gt;-&lt;503.5,126.0&gt;&gt; = 11.210633128876657
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* sinGh.virama: L&lt;&lt;30.0,336.0&gt;--&lt;283.0,335.0&gt;&gt;

* sinGhI: L&lt;&lt;30.0,336.0&gt;--&lt;283.0,335.0&gt;&gt;

* sinGhIi: L&lt;&lt;30.0,336.0&gt;--&lt;283.0,335.0&gt;&gt;

* sinGhRI: L&lt;&lt;30.0,336.0&gt;--&lt;283.0,335.0&gt;&gt;

* sinGhRIi: L&lt;&lt;30.0,336.0&gt;--&lt;283.0,335.0&gt;&gt;

* sinGhRa: L&lt;&lt;30.0,336.0&gt;--&lt;283.0,335.0&gt;&gt;

* sinGhU: L&lt;&lt;30.0,336.0&gt;--&lt;283.0,335.0&gt;&gt;

* sinGhUu: L&lt;&lt;30.0,336.0&gt;--&lt;283.0,335.0&gt;&gt;

* sinGha (U+0D9D): L&lt;&lt;30.0,336.0&gt;--&lt;283.0,335.0&gt;&gt;

* sinLl.virama: L&lt;&lt;408.0,369.0&gt;--&lt;606.0,370.0&gt;&gt;

* sinLlI: L&lt;&lt;408.0,369.0&gt;--&lt;606.0,370.0&gt;&gt;

* sinLlIi: L&lt;&lt;408.0,366.0&gt;--&lt;606.0,367.0&gt;&gt;

* sinLla (U+0DC5): L&lt;&lt;408.0,369.0&gt;--&lt;606.0,370.0&gt;&gt;

* sinS.virama: L&lt;&lt;30.0,336.0&gt;--&lt;283.0,335.0&gt;&gt;

* sinSI: L&lt;&lt;30.0,336.0&gt;--&lt;283.0,335.0&gt;&gt;

* sinSIi: L&lt;&lt;30.0,336.0&gt;--&lt;283.0,335.0&gt;&gt;

* sinSR.virama: L&lt;&lt;30.0,336.0&gt;--&lt;283.0,335.0&gt;&gt;

* sinSRI: L&lt;&lt;30.0,336.0&gt;--&lt;283.0,335.0&gt;&gt;

* sinSRIi: L&lt;&lt;30.0,336.0&gt;--&lt;283.0,335.0&gt;&gt;

* sinSRa: L&lt;&lt;30.0,336.0&gt;--&lt;283.0,335.0&gt;&gt;

* sinSU: L&lt;&lt;30.0,336.0&gt;--&lt;283.0,335.0&gt;&gt;

* sinSUu: L&lt;&lt;30.0,336.0&gt;--&lt;283.0,335.0&gt;&gt;

* sinSa (U+0DC3): L&lt;&lt;30.0,336.0&gt;--&lt;283.0,335.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure Stylistic Sets have description. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gsub.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The stylistic set ss02 lacks a description string on the 'name' table.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'MNIK' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/DadigamaDEV-Regular.ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 11 | 12 | 121 | 7 | 100 | 0 | 
| 0% | 0% | 4% | 5% | 48% | 3% | 40% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG

<!-- -*- coding: utf-8 -*- -->
# Experimental Harano Aji Fonts K1

Harano Aji Fonts K1 (Harano Aji Mincho K1 and Harano Aji Gothic K1)
are fonts obtained by replacing Adobe-Identity-0 (AI0) CIDs
of Source Han fonts (Source Han Serif and Source Han Sans)
with Adobe-Korea1 (AK1) CIDs.

There are 14 fonts, 7 weights each for Mincho and Gothic.

## Distribution

* Japanese (JP): Adobe-Japan1
    + [
https://github.com/trueroad/HaranoAjiFonts
](https://github.com/trueroad/HaranoAjiFonts)
* (Experimental) Simplified Chinese (CN): Adobe-GB1
    + [
https://github.com/trueroad/HaranoAjiFontsCN
](https://github.com/trueroad/HaranoAjiFontsCN)
* (Experimental) Traditional Chinese (TW): Adobe-CNS1
    + [
https://github.com/trueroad/HaranoAjiFontsTW
](https://github.com/trueroad/HaranoAjiFontsTW)
* (Experimental) Korean (KR): Adobe-KR
    + [
https://github.com/trueroad/HaranoAjiFontsKR
](https://github.com/trueroad/HaranoAjiFontsKR)
* (Experimental) Korean (K1): Adobe-Korea1
    + [
https://github.com/trueroad/HaranoAjiFontsK1
](https://github.com/trueroad/HaranoAjiFontsK1)

See [
Harano Aji Fonts generator
](https://github.com/trueroad/HaranoAjiFonts-generator)
for details.

## Release Notes

* [
20210410
](https://github.com/trueroad/HaranoAjiFontsK1/releases/tag/20210410)
(JP, CN, TW, KR, K1)
    + Based on SourceHanSans 2.003 (JP, CN, TW, KR, K1)
    + Update
        + SourceHanSans 2.003
        + ttx 4.22.0
    + Number of contained glyphs (JP)
        - HaranoAjiMincho: 17554
          (conversion 16862 + glyph processing 691 + .notdef 1)
        - HaranoAjiGothic: 17559
          (conversion 16866 + glyph processing 692 + .notdef 1)
* [
20210101
](https://github.com/trueroad/HaranoAjiFontsK1/releases/tag/20210101)
(JP, CN, TW, KR, K1)
    + Based on SourceHanSans 2.002 (JP, CN, TW, KR, K1)
    + Add many Kana glyphs (JP)
    + Add many GSUB features and entries (JP)
    + Update
        + SourceHanSans 2.002
        + ttx 4.18.2
    + Number of contained glyphs (JP)
        - HaranoAjiMincho: 17554
          (conversion 16862 + glyph processing 691 + .notdef 1)
        - HaranoAjiGothic: 17559
          (conversion 16867 + glyph processing 691 + .notdef 1)
* [
20200612
](https://github.com/trueroad/HaranoAjiFontsK1/releases/tag/20200612)
(JP, CN, TW, KR, K1)
    + Add `cmap` table from CMap such as AJ1
      and change CID in `cmap` table according to CMap (JP, CN, TW, KR, K1)
    + Add AJ1 CID+151 by copying from AJ1 CID+14 (JP)
    + Change size reducing method for size exceeded `cmap` table format 4
      (TW, KR)
    + Add `GPOS` table (KR)
    + Improve generator
    + Update
        + ttx 4.12.0
    + Number of contained glyphs (JP)
        - HaranoAjiMincho: 16888
          (conversion 16678 + glyph processing 209 + .notdef 1)
        - HaranoAjiGothic: 16893
          (conversion 16683 + glyph processing 209 + .notdef 1)
* [
20200524
](https://github.com/trueroad/HaranoAjiFontsK1/releases/tag/20200524)
(JP, CN, TW, KR, K1)
    + Add proportional Kana glyphs (JP)
    + Add some space glyphs (JP, KR)
    + Fix broken `GPOS` table such as palt (JP, CN, TW, KR)
    + Change width of Monospaced glyphs in **experimental** Korean font (KR)
    + Add **experimental** Korean font variation (K1)
        + Korean: Adobe-Korea1, suffix K1
            + UniKS-UTF32-H 1.008
    + Update
        + ttx 4.10.2
    + Number of contained glyphs (JP)
        - HaranoAjiMincho: 16887
          (conversion 16678 + glyph processing 208 + .notdef 1)
        - HaranoAjiGothic: 16892
          (conversion 16683 + glyph processing 208 + .notdef 1)

## LICENSE

Copyright (C) 2019-2021
Masamichi Hosoda, with Reserved Font Name 'Harano Aji'.

Copyright 2014-2021 Adobe (http://www.adobe.com/),
with Reserved Font Name 'Source'.

Copyright 2017 Adobe Systems Incorporated (http://www.adobe.com/),
with Reserved Font Name 'Source'.

Source is a trademark of Adobe in the United States and/or other countries.

This Font Software is licensed under the SIL Open Font License, Version 1.1.
See [LICENSE](LICENSE).

# Hershey-Unicode-Mapping

The most comprehensive mapping of Dr. A. V. Hershey's Vector Fonts to Unicode, including most special characters, Roman, Greek, Cyrillic, Italic, Gothic, Kanji, Hiragana and Katakana.

To put the whole repository in the public domain, the JHF glyph data has been omitted, which would require to copy a long and partially incorrect block of text.

## Files

The HTML files contain SVG renderings of each glyph, corresponding Unicode glyphs and comments.

If you don't want to download them, they're hosted here: [hershey_occidental.html](https://kaloffl.github.io/0021/hershey_occidental.html), [hershey_oriental.html](https://kaloffl.github.io/0021/hershey_oriental.html).

The CSV files only contain the Hershey Font id, as well as up to two Unicode mappings.

Glyphs with multiple Unicode mappings could represent either one, like [1051](https://kaloffl.github.io/0021/hershey_occidental.html#1051), which could be a regular 'A' in an italic font, or '𝐴 (Mathematical Italic Capital A)' in a regular font.

## Origin

The Hershey Fonts are posted in various places on the internet, and it is often difficult to tell where the data came from and if it has been modified.

The data in this repository came from the archive posted to the mod.sources Usenet group by Pete Holzmann's USENET FONT CONSORTIUM back in 1986.
That data came from a magnetic tape bought from the NTIS, and was converted into a more compact format designed by James Hurt.
Pretty much all Hershey Font data you find today is in that format.

One modification has been made by me: the Usenet data appears to have suffered a bit-flip in the right bearing of glyph [3010 (triplex J)](https://kaloffl.github.io/0021/hershey_occidental.html#3010), I changed it to the correct value according to Wolcott[1].

The mapping has been done manually by me, with help from the descriptions in Wolcott's report[1] and checked against Reinholtz's mapping [2].
The Kanji have been mapped to Unicode via handwriting recognition and validated by checking the On pronunciation provided by Hershey[3] with a modern dictionary.
The number of each Kanji in Hershey's font corresponds to it's number in [4], which has been used to validate Kanji where modern fonts diverge from Hershey's font.
All in all I'm quite confident in the correctness of the mapping, despite not knowing the language.

## References

[1] Hershey, A. V. "Calligraphy for Computers". 1967. U, S, Naval Weapons Laboratory. NTRL report number AD662398. Web http://ntrl.ntis.gov (2024-05-20).

[2] Reinholtz. Web https://github.com/reinholtz/hershey-fonts-with-unicode (2024-05-20).

[3] Wolcott, N. M.; Hilsenrath, J. "Contribution to Computer Typesetting Techniques: Tables of Coordinates for Hershey's Repertory of Occidental Type Fonts and Graphic Symbols". 1976. National Bureau of Standards Department of Commerce. NTRL report number. PB251845. Web http://ntrl.ntis.gov (2024-05-20)

[4] Nelson, A. N. "The Modern Reader's Japanese-English Character Dictionary". 1962. Charles E. Tuttle Company, Rutland, Vermont.

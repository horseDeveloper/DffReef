# Quick introduction to the fonts
![Purple line](/DffAssets/imgs-for-docs/svg--900x05--c--ff5975.svg)<br>
What are variable fonts? <br>
     🔗 [Interactive example](https://fonts.google.com/specimen/Readex+Pro/tester): choose your writing system (Latin/Arabic) and play with the sliders on the left.<br>
     🔗 [Formal explanation](https://fonts.google.com/knowledge/introducing_type/introducing_variable_fonts) (text + images)

## Lexend & Readex Font Families
**Lexend** is a typeface with variable weight axis (Thin to Black) and variable width axis. It is designed to improve reading fluency. <br>
Read more: [🔗 Official website - Lexend.com](https://www.lexend.com/) ; [🔗 GitHub/GoogleFonts page](https://github.com/googlefonts/lexend) ; [🔗 Google Fonts](https://fonts.google.com/specimen/Lexend)

**Readex Pro** is the world-script expansion of Lexend. It's the same as Lexend, with the addition of more scripts (at this moment: Arabic) <br>
Read more: - [🔗 Official website - Lexend.com](https://www.lexend.com/) ; [🔗 GitHub/Author page](https://github.com/ThomasJockin/readexpro) ; [🔗 Google Fonts](https://fonts.google.com/specimen/Readex+Pro)

| FONT NAME | WEIGHT-AXIS | WEIGHT-NAMES | 
|---|---|---|
| Lexend | 100 → 900 | Thin 100; ExtraLight 200; Light 300; <br>Regular 400 (default);<br>Medium 500; Semibold 600; Bold 700; Extrabold 800; Black 900 |
| ReadexPro | 160 → 700 | Extralight 200; Light 300; <br>Regular 400 (default); <br>Medium 500; Semibold 600; Bold 700 |

As for the width axis, Lexend uses the following naming convention: <br>
```
Deca  • HEXP 0
Exa   • HEXP 40
Giga  • HEXP 56
Mega  • HEXP 64
Peta  • HEXP 72
Tera  • HEXP 80
Zetta • HEXP 100
```
Dff fonts are based on the "deca" version, the one with the least amount of hyper-expansion. <br>

| Lexend and ReadexPro are both unconventional [sans-serif](https://en.wikipedia.org/wiki/Sans-serif) typefaces as they make an exception for the uppercase 'i', giving it a [serif](https://en.wikipedia.org/wiki/Serif). | ![Serif explanation](/DffAssets/images/serif-explanation.png) |
|---|---|

## Dff Font Families
### DffLentic & DffReef > Font info
[Dff**Le**ntic](https://github.com/horseDeveloper/DffLentic) is a fork of **Le**xend. [Dff**Re**ef](https://github.com/horseDeveloper/DffReef) is a fork of **Re**adexPro. <br>
Both forks are based on the originals, but 3* glyphs from the alternative set have been locked in as default. <br>
(*) _only 2 in Readex_

The three modifications:
| | |
|---|---|
| * Dotted `0`<br>* Alt `a`<br>* Alt `g` | ![Differences between Lexend and Dff](/DffAssets/images/Lexend-Readex-Dff-differences.png) |

Showcase & Comparison:
![Full comparison](/DffAssets/images/full-comparison.png)


# How to use Dff fonts
![Purple line](/DffAssets/imgs-for-docs/svg--900x05--c--ff5975.svg)<br>
## Install precompiled fonts
No requirements needed. <br>
Download your font here, open the file and and follow the installation wizard. <br>
_Note: It's provided a single file that installs all the different instances of the weight axis. Each instance is based on "**deca**" width axis._
  * Download DffLentic [📥 Download](https://github.com/horseDeveloper/DffLentic/tree/main/DffFonts) (recommended) <br>
  * Download DffReef [📥 Download](https://github.com/horseDeveloper/DffReef/tree/master/DffFonts) (if your script has been added to Readex)

Scripts added to ReadexPro (and DffReef consequently): 
```
Latin
Arabic
```

If you prefer, you can always install the original fonts:<br>
| | |
|---|---|
| Lexend | Multiple files, each installs a <ins>single</ins> instance of the weight axis: [📥 Download](https://github.com/googlefonts/lexend/tree/main/fonts) |
| Lexend | Single file that installs that installs <ins>all</ins> the different instances of the weight axis: [📥 Download](https://github.com/googlefonts/lexend/tree/main/fonts/lexend/variable) |
| ReadexPro | Single file that installs <ins>all</ins> the different instances of the weight axis: [📥 Download](https://github.com/ThomasJockin/readexpro/tree/master/fonts/variable) |

🎉 Enjoy!

## Alternatively, build your own fonts
This project is a simple modification of the original work done through editing precompiled fonts. Original source files are untouched. Editing source files is outside the scope of this project.

## Alternatively, edit on top of the original precompiled files
### With my python tools to automate the process
Requirements: Tools used for the manual process are still required.<br>
[📥 py-line-editor]
[📥 py-compare2lexend]

### Manually
Tools used:
* [github/twardoch/Opentype Feature Freezer](https://github.com/twardoch/fonttools-opentype-feature-freezer)
* [github/fonttools/FontTools](https://github.com/fonttools/fonttools)
* [github/fontforge/FontForge](https://github.com/fontforge/fontforge)

# Information for users
![Purple line](/DffAssets/imgs-for-docs/svg--900x05--c--ff5975.svg)<br>
✅ The Open Font License is a free software license, and as such permits the fonts to be used, modified, and distributed freely (so long as the resulting fonts remain under the Open Font License).<br>
✅ Fonts can be used for both personal or commercial use.<br>
More info on https://openfontlicense.org/ofl-faq/

# Disclaimer
![Purple line](/DffAssets/imgs-for-docs/svg--900x05--c--ff5975.svg)<br>
This project exists to improve compatibility and ease of use for software that doesn't support easily switching to alternative glyphs. DffLentic & DffReef are completely based on [Lexend](https://www.lexend.com/) and [Readex Pro](https://github.com/ThomasJockin/readexpro) but are in no way related to them. DffLentic & DffReef have different names as per [OFL Guidelines](https://openfontlicense.org/how-to-modify-ofl-fonts/) but I have done my best to maintain the references to the original products.

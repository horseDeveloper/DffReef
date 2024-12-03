[![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner2-direct.svg)](https://stand-with-ukraine.pp.ua)

# Quick introduction to the fonts
## Lexend & Readex Font Families
**Lexend** is a typeface with variable weight axis (Thin to Black) and width axis. It is designed to improve reading fluency. <br>
Read more: [🔗 Official website - Lexend.com](https://www.lexend.com/) ; [🔗 GitHub/GoogleFonts page](https://github.com/googlefonts/lexend) ; [🔗 Google Fonts](https://fonts.google.com/specimen/Lexend)

**Readex Pro** is the world-script expansion of Lexend. It's the same as Lexend, with the addition of more scripts (at this moment: Arabic) <br>
Read more: - [🔗 Official website - Lexend.com](https://www.lexend.com/) ; [🔗 GitHub/Author page](https://github.com/ThomasJockin/readexpro) ; [🔗 Google Fonts](https://fonts.google.com/specimen/Readex+Pro)

| FONT NAME | WEIGHT-AXIS | WEIGHT-NAMES | 
|---|---|---|
| Lexend | 100 → 900 | Thin; Extralight; Light; Medium; Semibold; Extrabold; Black |
| ReadexPro | 160 → 700 | Extralight; Light; Medium; Semibold |

Lexend and ReadexPro are both unconventional [sans-serif](https://en.wikipedia.org/wiki/Sans-serif) typefaces as they make an exception for the uppercase 'I', giving it a [serif](https://en.wikipedia.org/wiki/Serif).
**INSERT IMG HERE**

## dff Font Families
### dffLentic & dffReef > Font info
[dff**Le**ntic](https://github.com/horseDeveloper/dffLentic) is a fork of **Le**xend. [dff**Re**ef](https://github.com/horseDeveloper/dffReef) is a fork of **Re**adexPro. <br>
Both forks are based on the originals, but 3 glyphs from the alternative set have been locked in as default. 

The three modifications:
**insert image here**
* Dotted `0`
* Alt `g`
* Alt `a`

# How to use dff fonts
## Install precompiled fonts
No requirements needed. <br>
Download your font here, open the file and and follow the installation wizard. <br>
Note: It's provided a single file that installs all the different instances of the weight axis.
  * Download dffLentic [📥 Download] **link** (recommended) <br>
  * Download dffReef [📥 Download] **link** (if your script has been added to Readex)

Scripts added to ReadexPro (and dffReef consequently): 
```
Arabic
```

If you prefer, you can always install the original fonts:<br>
| | |
|---|---|
| Lexend | Multiple files, each install a single instance of the weight axis: [📥 Download](https://github.com/googlefonts/lexend/tree/main/fonts) |
| Lexend | Single file that installs that installs all the different instances of the weight axis: [📥 Download](https://github.com/googlefonts/lexend/tree/main/fonts/lexend/variable) |
| ReadexPro | Single file that installs all the different instances of the weight axis: [📥 Download](https://github.com/ThomasJockin/readexpro/tree/master/fonts/variable) |

Enjoy!

## Alternatively, build your own fonts
This project is a simple modification of the original work done through editing precompiled fonts. Original source files are untouched. Editing source files is outside the scope of this project.

## Alternatively, edit on top of the original precompiled files
### With my python tools to automate the process
Requirements: Tools used for the manual process are still required.
(📥 py line editor add link here)
(📥 py compare)

### Manually
Tools used:
* [Opentype Feature Freezer](https://github.com/twardoch/fonttools-opentype-feature-freezer)
* [FontTools](https://github.com/fonttools/fonttools)
* [FontForge](https://github.com/fontforge/fontforge)


# Disclaimer
This project exists only to improve compatibility and ease of use for software that doesn't support easily switching to alternative glyphs. dffLentic & dffReef are completely based on [Lexend](https://www.lexend.com/) and [Readex Pro](https://github.com/ThomasJockin/readexpro) but are in no way related to them. dffLentic & dffReef have different names as per [OFL Guidelines](https://openfontlicense.org/how-to-modify-ofl-fonts/) but I have done my best to maintain the references to the original products.

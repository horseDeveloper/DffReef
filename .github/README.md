# Quick introduction to the fonts
![svg--900x10--c--ff5975](https://github.com/user-attachments/assets/5d694255-3816-469f-abf0-eb09b4e5f7fa)<br>
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

| Lexend and ReadexPro are both unconventional [sans-serif](https://en.wikipedia.org/wiki/Sans-serif) typefaces as they make an exception for the uppercase 'i', giving it a [serif](https://en.wikipedia.org/wiki/Serif). | ![Lexend-IL](https://github.com/user-attachments/assets/be949aeb-5d45-4b8a-9423-7dc827bbf81c) |
|---|---|

## Dff Font Families
### DffLentic & DffReef > Font info
[Dff**Le**ntic](https://github.com/horseDeveloper/DffLentic) is a fork of **Le**xend. [Dff**Re**ef](https://github.com/horseDeveloper/DffReef) is a fork of **Re**adexPro. <br>
Both forks are based on the originals, but 3* glyphs from the alternative set have been locked in as default. <br>
*only 2 in Readex

The three modifications:
| | |
|---|---|
| * Dotted `0`<br>* Alt `a`<br>* Alt `g` | ![ddf2](https://github.com/user-attachments/assets/b4fe606e-76aa-456e-b573-5213b404655e) |

Showcase & Comparison:
![image](https://github.com/user-attachments/assets/93469e57-6b52-48c1-b37d-6f965c9b9ae5)


# How to use Dff fonts
![svg--900x10--c--ff5975](https://github.com/user-attachments/assets/5d694255-3816-469f-abf0-eb09b4e5f7fa)<br>
## Install precompiled fonts
No requirements needed. <br>
Download your font here, open the file and and follow the installation wizard. <br>
Note: It's provided a single file that installs all the different instances of the weight axis. Each instance is based on "deca" width axis.
  * Download DffLentic [📥 Download](https://github.com/horseDeveloper/DffLentic/tree/main/DffFonts) (recommended) <br>
  * Download DffReef [📥 Download](https://github.com/horseDeveloper/DffReef/tree/master/DffFonts) (if your script has been added to Readex)

Scripts added to ReadexPro (and DffReef consequently): 
```
Arabic
```

If you prefer, you can always install the original fonts:<br>
| | |
|---|---|
| Lexend | Multiple files, each installs a single instance of the weight axis: [📥 Download](https://github.com/googlefonts/lexend/tree/main/fonts) |
| Lexend | Single file that installs that installs all the different instances of the weight axis: [📥 Download](https://github.com/googlefonts/lexend/tree/main/fonts/lexend/variable) |
| ReadexPro | Single file that installs all the different instances of the weight axis: [📥 Download](https://github.com/ThomasJockin/readexpro/tree/master/fonts/variable) |

🎉 Enjoy!

## Alternatively, build your own fonts
This project is a simple modification of the original work done through editing precompiled fonts. Original source files are untouched. Editing source files is outside the scope of this project.

## Alternatively, edit on top of the original precompiled files
### With my python tools to automate the process
Requirements: Tools used for the manual process are still required.
[📥 py-line-editor]
[📥 py-compare2lexend]

### Manually
Tools used:
* [Opentype Feature Freezer](https://github.com/twardoch/fonttools-opentype-feature-freezer)
* [FontTools](https://github.com/fonttools/fonttools)
* [FontForge](https://github.com/fontforge/fontforge)


# Disclaimer
![svg--900x10--c--ff5975](https://github.com/user-attachments/assets/5d694255-3816-469f-abf0-eb09b4e5f7fa)<br>
This project exists only to improve compatibility and ease of use for software that doesn't support easily switching to alternative glyphs. DffLentic & DffReef are completely based on [Lexend](https://www.lexend.com/) and [Readex Pro](https://github.com/ThomasJockin/readexpro) but are in no way related to them. DffLentic & DffReef have different names as per [OFL Guidelines](https://openfontlicense.org/how-to-modify-ofl-fonts/) but I have done my best to maintain the references to the original products.

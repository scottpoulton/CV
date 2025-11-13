# CV

This repository contains the LaTeX source code and compiled PDF for my CV.

## Download

[**CV.pdf**](CV.pdf)

## Compiling

### Easy Method (Recommended)

1.  Create a new "Blank Project" on Overleaf.
2.  Click the "Upload" button.
3.  Upload all the files from this repository:
    * `CV.tex`
    * `Fontin.otf`
    * `Fontin-Bold.otf`
    * `Fontin-Italic.otf`
    * `Fontin-SmallCaps.otf`
4.  In the Overleaf "Menu", set the "Compiler" to **XeLaTeX**.
5.  Click "Recompile" and it will generate the PDF.

### Local Compilation

If you wish to compile this locally, you **must** use the **XeLaTeX** or **LuaLaTeX** compiler. This is required because the project uses the `fontspec` package and custom `.otf` fonts.


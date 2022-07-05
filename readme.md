# Curriculum-vitae

Curriculum vitae, formatted with Latex, output in PDF.

## Building

On Ubuntu (or WSL), install texlive-full. This includes all packages and takes about `5gb` to install.

```bash
sudo apt install texlive-full
```

Then build using latexmk, using the `-pvc` (PreView Continuously) option.

```bash
latexmk -pdf -xelatex -pvc paper.tex
```

Live update PDF vierwe built into Ubuntu.

```bash
zathura cv.pdf & 
```

## Required Packages
- geometry
- babel
- fontawesome
- hyperref
- fancyhdr
- resume (see resume.sty file)


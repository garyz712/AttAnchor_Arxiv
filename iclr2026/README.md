# GPS Paper - ICLR 2026 Format

This folder contains the GPS (Gumbel Permutation Sinkformer) paper converted from NeurIPS 2024 format to ICLR 2026 format.

## Files Created

- **`gps_iclr.tex`** - The main LaTeX file with your GPS paper content in ICLR 2026 format
- **`gps_iclr.bib`** - Bibliography file with all your references
- **All PNG images** - Copied from the original GPS-ICLR folder

## Key Changes Made

1. **Template Conversion**: Changed from `neurips_2024` to `iclr2026_conference` template
2. **Author Anonymization**: Changed authors to "Anonymous Authors" for submission (you can uncomment `\iclrfinalcopy` for camera-ready version)
3. **Bibliography Style**: Changed from `plainnat` to `iclr2026_conference`
4. **Package Updates**: Updated package imports to match ICLR requirements
5. **Formatting**: Adjusted to ICLR 2026 formatting standards

## How to Compile

### Option 1: Install LaTeX (Recommended)
```bash
# On macOS with Homebrew
brew install --cask mactex

# On Ubuntu/Debian
sudo apt-get install texlive-full

# Then compile
pdflatex gps_iclr.tex
bibtex gps_iclr
pdflatex gps_iclr.tex
pdflatex gps_iclr.tex
```

### Option 2: Use Online LaTeX Compiler
- Upload the files to [Overleaf](https://www.overleaf.com/)
- Or use [LaTeX Base](https://latexbase.com/)

### Option 3: Use VS Code with LaTeX Workshop Extension
- Install the LaTeX Workshop extension
- Open the `.tex` file and use the build commands

## Important Notes

1. **Page Limit**: ICLR 2026 has a strict 9-page limit for initial submissions
2. **Anonymous Submission**: The paper is set up for anonymous submission. For camera-ready version, uncomment `\iclrfinalcopy`
3. **Bibliography**: Make sure all references in `gps_iclr.bib` are properly formatted
4. **Images**: All images are included and should display correctly

## Content Summary

Your GPS paper includes:
- Introduction to multimodal token reordering problem
- Two proposed methods: Cosine Similarity reordering and GPS
- Experimental results and analysis
- Future work directions
- Comprehensive bibliography

The paper is now properly formatted for ICLR 2026 submission and should compile without issues once you have a LaTeX distribution installed.

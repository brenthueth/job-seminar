# Job Seminar Presentation

**Vertical Disintegration and the Shifting Boundary of the Farm Business: Implications for Agricultural Productivity**

Job seminar presentation for Iowa State University position in Economics of Cooperatives and Agricultural Supply Chains.

## Files

- `job_seminar.tex` - Main LaTeX Beamer source file
- `job_seminar.pdf` - Compiled presentation slides (39 slides + 2 appendix)
- `notes.pdf` - Speaker notes PDF for podium reference
- `figures/` - Figure files (PDF format for LaTeX inclusion)

## Compiling

The presentation uses LaTeX Beamer. To compile:

```bash
pdflatex job_seminar.tex
```

### Speaker Notes

To generate speaker notes PDF, uncomment line 11 in `job_seminar.tex`:
```latex
\setbeameroption{show only notes}
```

Then recompile. Comment it out again for projection slides.

Put multiple notes on a page
```bash
pdfjam --nup 1x3 job_seminar.pdf -o notes.pdf
```

## Presentation Structure

1. **Research Overview** (~10 min)
   - Past work: contracting, cooperatives, productivity
   - Future research: 3 cooperative themes + complementary supply chain work

2. **Paper Presentation** (~60 min)
   - Motivation: TFP puzzle and vertical disintegration trend
   - Data: LBD + Census of Agriculture
   - Results: Services-yield relationship
   - Discussion: Implications for productivity measurement

3. **Q&A** (~20 min)

## Navigation Features

- Footer links to table of contents (click subsection name)
- Hyperlinked appendix slides for Figure 3 panels (marginal effects)
- "Back to Results" buttons on appendix slides

## Author

Brent Hueth
USDA Economic Research Service
Joint work with Anton Babkin (UW-Madison) and Richard A. Dunn (Sandhill Consulting)

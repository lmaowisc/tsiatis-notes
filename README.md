# Tsiatis Notes and Solutions

An RStudio-ready Quarto Book framework for a companion to Anastasios A. Tsiatis's *Semiparametric Theory and Missing Data* (2006).

## Open in RStudio

1. Install current versions of R, RStudio, and Quarto.
2. Open `tsiatis-notes.Rproj` in RStudio.
3. Open any `.qmd` file and select **Render Book** in the Build pane.

Alternatively, run in the RStudio Terminal:

```bash
quarto preview
```

To render the complete book:

```bash
quarto render
```

HTML and PDF outputs are written to `_book/`. PDF rendering requires a TeX installation; TinyTeX is suitable.

## Project layout

- `_quarto.yml`: book structure and rendering options
- `index.qmd`, `preface.qmd`, `notation.qmd`: front matter
- `chapters/`: fourteen chapter files aligned with the source text
- `appendices/`: prerequisite and R-code references
- `references.bib`: bibliography database
- `styles.css`: HTML styling
- `apa.csl`: citation style

## Writing workflow

Use the common headings already included in every chapter. Cite the source rather than copying its prose, and identify exercises by chapter and number.


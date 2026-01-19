# Quarto Thesis Template (Linguistics)

This repository provides a Quarto template for a term paper, BA thesis, or MA thesis in linguistics with:

-   PDF output
-   figures, tables, and linguistic examples
-   cross-references (sections, figures, tables)
-   APA-style citations
-   IPA symbols (via Charis)

## Preview

![](thesisPreview.png)

## Requirements

-   R (≥ 4.1)

-   RStudio

-   Quarto

-   LaTeX distribution (TinyTeX); install TinyTeX in R: `tinytex::install_tinytex()`

-   Charis; download it from: <https://software.sil.org/charis/download/>

## How to use it

1.  Click "Code" and "Download ZIP"
2.  Unzip and open the folder
3.  Open `thesis.Rproj` in RStudio
4.  Open `thesis.qmd` and start writing

## Citations

-   Add your references in BibTeX format to the bibliography file: `references.bib`

-   Citation style: APA 7 (`apa_7th.csl`)

## Rendering the thesis

To render the thesis as a PDF click "Render" in RStudio or: `quarto::quarto_render("thesis.qmd")`

## License

This template is released under the CC0-1.0 license. You are free to modify and redistribute it.

## How to cite

DOI to be added.

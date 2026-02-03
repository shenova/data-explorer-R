# R-Project — Using DataExplorer in R

This repository is a small R/Quarto project focused on **teaching how to use the `DataExplorer` package in R** through written walkthroughs and rendered reports. :contentReference[oaicite:1]{index=1}

## What’s in this repo

Key files included in the project: :contentReference[oaicite:2]{index=2}

- `DoingItManually.qmd` — Quarto source document
- `DoingItManually.html` — rendered HTML version of the walkthrough
- `Final Project.qmd` — final report (Quarto)
- `project doc.qmd` — supporting project documentation (Quarto)
- `Technical Presentation of DataExplorer.html` — presentation-style HTML output
- `README.md` — project overview (this file)

## Quick start (view the outputs)

If you want to read the project outputs, open these files directly in your browser:

- `DoingItManually.html`
- `Technical Presentation of DataExplorer.html`

## Reproducing / Rendering the Quarto reports

### Requirements
- R (recent version recommended)
- Quarto
- (Optional) RStudio (makes rendering easier)

### Install packages
In R:

```r
install.packages(c(
  "DataExplorer",
  "tidyverse"
))

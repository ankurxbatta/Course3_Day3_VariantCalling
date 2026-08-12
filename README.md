# Variant calling — *Saccharomyces cerevisiae*

Bioinformatics coursework: finding where a sequenced yeast genome differs from
the reference, and visualising those variants along the genome.

## What it does

- Downloads the *S. cerevisiae* S288C reference annotation (GFF) from NCBI
- Loads variants and genome features with the Bioconductor stack
- Places variants in genomic context and plots them along the chromosome

## Tools

R / Quarto with `VariantAnnotation`, `GenomicFeatures`, `GenomicRanges` and
`Gviz` (Bioconductor).

## Running it

Open `Course3_Day3_VariantCalling.qmd` in RStudio and render, or:

```r
quarto::quarto_render("Course3_Day3_VariantCalling.qmd")
```

Part of the Genomics & Transcriptomics microcredential (Langara College).

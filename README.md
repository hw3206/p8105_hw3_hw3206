# P8105 Homework 3

Harrison Wei (hw3206), Fall 2026.

Read the [rendered homework](p8105_hw3_hw3206.md), or inspect the [R Markdown source](p8105_hw3_hw3206.Rmd).

The report includes New York NOAA weather exploration, NHANES activity comparisons, and Citi Bike ride summaries. Each section contains the data preparation, requested tables and figures, and interpretation.

To reproduce the report, open `p8105_hw3_hw3206.Rproj` in RStudio and knit `p8105_hw3_hw3206.Rmd`. Alternatively, run this from the project directory:

```r
rmarkdown::render("p8105_hw3_hw3206.Rmd")
```

The output format is `github_document`. The analysis uses `tidyverse`, `p8105.datasets`, and `patchwork`; `knitr` and `rmarkdown` are needed to render it. No packages are installed by the report. Input files are included in `data/` and accessed with relative paths; their sources and coding notes are listed in [data/README.md](data/README.md). As required, `ny_noaa` is loaded from the course package rather than stored in this repository.

The supplied Citi Bike files are 1% samples of rides shorter than four hours. Reported ride counts refer to the samples, and the comparisons are descriptive.

[Assignment instructions](https://p8105.com/homework_3.html)

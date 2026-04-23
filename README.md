# ProteinBatcher-Visualizer

## Dependencies

```r
install.packages(c("shiny", "bslib", "plotly", "DT", 
                   "ggplot2", "dplyr", "remotes", "yaml", "knitr", "rmarkdown",
                   "rsconnect", "BiocManager"))

BiocManager::install(c("SummarizedExperiment", "S4Vectors"), 
                     ask = FALSE)

# Install ProteinBatcher (GitHub repository or Bioconductor when available)
remotes::install_github("DataScienceRD-Almirall/ProteinBatcher", 
                        upgrade = "never")
``

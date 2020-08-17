# nHuSC: R Shiny App
The **nHuSC** R package and associated R shiny app was developed to visualise the single-cell RNA-seq expression profiles of 78,264 human cardiac cells from the left ventricle. The detailed vignette is available on: 

The R shiny applet enables the user to select a gene ID or symbol, and it generates a series of interactive plots (UMAP and Violin Plot) for data viusalisation and exploratory analysis.

The package can be installed on R after downloading the tar.gz file by the command:
```r
install.packages("nHuSC.1.0.tar.gz", repos = NULL, type = "source")
```

To run the R shiny applet after installation:
```r
library(nHuSC)
run_nHuSC()
```

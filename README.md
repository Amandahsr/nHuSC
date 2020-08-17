# nHuSC: R Shiny App
The **nHuSC** R package and associated R shiny app was developed to visualise the single-cell RNA-seq expression profiles of 78,264 human cardiac cells from the left ventricle. The detailed vignette is available on: https://github.com/Amandahsr/nHuSC/blob/master/vignette.pdf 

The R shiny applet enables the user to select a gene ID or symbol, and it generates a series of interactive plots (UMAP and Violin Plot) for data viusalisation and exploratory analysis.

![](https://github.com/Amandahsr/nHuSC/blob/master/nHuSC%20Home%20Screen%20Interface.png)
![](https://github.com/Amandahsr/nHuSC/blob/master/nHuSC%20Interactive%20Analysis%20Interface.png)


The package can be installed on R after downloading the tar.gz file using the command:
```r
install.packages("pathdirectory/nHuSC.1.0.tar.gz", repos = NULL, type = "source")
```

To run the R shiny app after installation:
```r
library(nHuSC)
run_nHuSC()
```

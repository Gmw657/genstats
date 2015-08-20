## Statistics for Genomic Data Science R package

This is the R package containing the code and lecture materials for the class Statistics for Genomic Data Science. You can get all of the code used in the class by installing the R package:

```{r}
source("http://bioconductor.org/biocLite.R")
biocLite("devtools")    # only if devtools not yet installed
biocLite("jtleek/genstats")
```

You can see the list of lecture notes and open them using the vignette command:

```{r}
vignette(package="genstats")
vignette("rmarkdown")
```

For more information check out: 

* Lecture Notes: http://jtleek.com/genstats_site
* Course: [Statistics for Genomic Data Science]()
* Specialization: [Genomic Data Science Specialization](https://www.coursera.org/specialization/genomics/41)
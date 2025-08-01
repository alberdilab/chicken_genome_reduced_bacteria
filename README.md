# chicken_genome_reduced_bacteria

Code repository of the genome-reduced bacteria in chickens project

The raw code used for data analysis is in the **Rmd** files stored in the root directory of this repository, while the bookdown-rendered webbook is available at:

[https://alberdilab.github.io/chicken_genome_reduced_bacteria/](https://alberdilab.github.io/chicken_genome_reduced_bacteria/docs/index.html)

While the webbook provides a user-friendly overview of the procedures, analyses can be directly reproduced using the Rmd documents. Note that the code chunks that require heavy computation have been tuned off using 'eval=FALSE'. To re-render the webbook, you can use the following code:

```r
library(bookdown)
library(htmlwidgets)
library(webshot)

render_book(input = ".", output_format = "bookdown::gitbook", output_dir = "docs")
```

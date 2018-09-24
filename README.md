# Basic Latex Template for RMarkdown

An adaptation of Steven Miller's excellent [RMarkdown manuscript template](http://svmiller.com/blog/2016/02/svm-r-markdown-manuscript/) for times when you need to look like a LaTeX user or times when you need the title and abstract on a separate title page. Retains most of the YAML options in Steven Miller's template. 

## Getting Started

Requires RStudio / RMarkdown etc. Find it [here](https://www.rstudio.com/products/rstudio/download/)

Requires `devtools` package for installation.

## Installation

Run this in your R console to download the template as an `R` Package. Remember to change the `template:` filepath in the YAML header to wherever you store the `manuscript.tex` downloadable from this repository.

```
devtools::install_github("milliff/Latex-Manuscript-for-RMarkdown")
```

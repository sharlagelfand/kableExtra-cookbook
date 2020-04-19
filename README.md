# kableExtra Cookbook

This repo is the home of a very bare bones [cookbook](https://sharlagelfand.github.io/kableExtra-cookbook/) that will contain snippets and examples of how to use the [kableExtra](https://haozhu233.github.io/kableExtra/) R package, which can create highly-customized tables in PDF and HTML.

The goal of this book is twofold: first, to show quick and self-contained examples of how to solve common table-formatting problems (e.g. making a table full width, adding captions, changing columns and alignment, etc). 

The second goal is to illustrate just how much customization is possible using kableExtra by taking wild-caught, complex tables with ~artisanal formatting and showing that these tables can be made easily, programatically, and reproducibly.

This repo is pretty empty, but it's up so it can be worked on at the Chicago R Collab (April 18-19)! Please see the [issues](https://github.com/sharlagelfand/kableExtra-cookbook/issues) for potential areas for contribution. 

# Building the book

In RStudio, press Cmd/Ctrl + Shift + B. Or run:

```r
# install.packages("bookdown")
bookdown::render_book("index.Rmd")
```


<!-- README.md is generated from README.Rmd. Please edit that file -->

# An R Markdown template for writing reports and academic papers

<!-- badges: start -->
<!-- badges: end -->

## Motivation

**zhuangreport** is a personalised .Rmd template that I use for writing
research reports and academic papers. This template is built based on
[lecturenotes](https://github.com/grantmcdermott/lecturenotes) by
**Grant McDermott **. It is intended for documents that are going to be
exported (i.e. “knitted”) to both HTML and PDF formats. In so doing, it
tries to take care of various annoyances and inconsistencies that arise
between these two formats.

## Installation and use

This bespoke package is mainly for personal use. However, you can easily
install it from GitHub:

``` r
# install.packages("devtools")
devtools::install_github("Zhuang-CHU/zhuangreport")
```

Note that I use several external packages in the template to demonstrate
functionality. See the “Suggests” list at the bottom of the
[DESCRIPTION](https://github.com/Zhuang-CHU/zhuangreport/blob/main/DESCRIPTION)
file. If you want to have these installed automatically, then you can
simply amend the above installation command to:

``` r
# install.packages("remotes")
remotes::install_github("Zhuang-CHU/zhuangreport", dependencies = TRUE)
```

Once the package is installed, open up the **zhuangreport** template in
RStudio by navigating to:

    File > New File > R Markdown > From Template > Research Report

(You can also select a “lean” template version that just provides the
scaffolding without any explanatory text or examples.)

## Limitations

This R Markdown template was mostly designed for my own use. As such, it
comes with no guarantees; although, please do let me know if you run
into problems. Some potential limitations and requirements perhaps worth
highlighting:

- It is change the font size and style in the PDF output is currently
  muted

## Acknowledgements

This template essentially pulls mainly from Grant McDermott. I’ve
accumulated over time to fit my own idiosyncratic writing and formatting
needs. Some of these I stumbled upon on myself, most of them I found the
old-fashioned way (i.e. searching on the Internet). Here is a
non-exhaustive list of helpful sources that I’ve drawn upon.

- <https://github.com/grantmcdermott/lecturenotes>
- <https://julianreif.com/guide/>
- <https://github.com/hollina/example_project>
- <https://github.com/skhiggins/R_guide>

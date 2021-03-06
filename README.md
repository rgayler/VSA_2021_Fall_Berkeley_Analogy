Analogical Reasoning
================
Ross Gayler
2021-10-06

<!-- README.md is generated from README.Rmd. Please edit only README.Rmd -->
<!-- badges: start -->

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5561007.svg)](https://doi.org/10.5281/zenodo.5561007)
[![License: CC BY
4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

<!-- badges: end -->

This repository contains the source code of the slides for the lecture
“Analogical Reasoning” given on 2021⁠-⁠10⁠-⁠06 as Module 6 of
[Neuroscience 299: Computing with High-Dimensional
Vectors](https://redwood.berkeley.edu/courses/computing-with-high-dimensional-vectors)
at the [Redwood Center for Theoretical
Neuroscience](https://redwood.berkeley.edu/), University of California,
Berkeley.

The purpose of this repository is to archive the source code for
creating the presentation.

## Related materials

All the materials related to this lecture have been archived on
[Zenodo](https://zenodo.org/):

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5560797.svg)](https://doi.org/10.5281/zenodo.5560797)
Video recording of lecture

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5552219.svg)](https://doi.org/10.5281/zenodo.5552219)
Slides (PDF)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5561007.svg)](https://doi.org/10.5281/zenodo.5561007)
Source code of slides (this repository)

## Project structure

This code is structured as an [RStudio
project](https://support.rstudio.com/hc/en-us/articles/200526207-Using-Projects)
using the [R programming language](https://www.r-project.org/) and
[Rmarkdown](https://rmarkdown.rstudio.com/).

I assume you know how to run an R project, so won’t go through all the
details of installation.

This project relies on the
[`renv`](https://rstudio.github.io/renv/articles/renv.html) package to
record the versions of all the packages used by the project. You will
need to have `renv` installed. Call `renv::restore()` from within the
project to install all the versions of the packages used in this
project.

The `assets/` directory contains the images used in the slides. These
images are copied from various papers and these sources are acknowledged
in the slides.

## Files

`lecture.Rmd` -
[Rmarkdown](https://rmarkdown.rstudio.com/authoring_basics.html) source
code for the slides as an
[ioslides](https://bookdown.org/yihui/rmarkdown/ioslides-presentation.html)
presentation.

`lecture.html` - The slides rendered as an HTML document. Open the file
with a web browser to give the presentation. The aspect ratio is 16:9.

`lecture.pdf` - The slides rendered as a PDF document. This was created
by printing the presentation to PDF from the web browser. The aspect
ratio is 4:3.

---
title: "Resources"
permalink: /resources/
author_profile: true
redirect_from:
  - /resources
---

{% include base_path %}

## R Package: `kctools`
The `kctools` package contains a suite of helper functions that I've written to address data manipulation and analysis tasks I frequently encounter in my work. I have turned this into an R package for myself and for those who would be interested in incorporating them in their workflow. The package includes functions for:
- Creating a data frame of summary statistics
- Constructing a data frame of one-way or two-way tabulations with counts and relative frequencies
- Generating various indicators of duplicated observations in a dataset
- Producing a data frame with pairwise distances of two `sf` objects     

You can find the [latest version](https://github.com/kennchua/kctools) of `kctools` in my Github. To install:

```r
devtools::install_github("kennchua/kctools")
```

## Resources for Learning R
During my [#rstats](https://twitter.com/search?q=%23rstats&src=typed_query) journey, I've relied on several resources that have proven invaluable in getting more accustomed to and proficient at using `R`. The following is a curated list that I hope will be useful for begginning and intermediate users who want to improve on their knowledge of the programming language.

1. Introduction to R
    - Hadley Wickham and Garret Grolemund's [R for Data Science](https://r4ds.had.co.nz/)
    - Steve Haroz's [A Succint Introduction to R](http://r-guide.steveharoz.com/)
2. Data Visualization in R
    - Yan Holtz's [R Graph Gallery](https://www.r-graph-gallery.com/)
    - Kieran Healy's [Data Visualization: A Practical Introduction](https://kieranhealy.org/publications/dataviz/)
3. Spatial Analysis in R
    - Robin Lovelace, Jakub Nowosad, and Jannes Muenchow's [Geocomputation with R](https://geocompr.robinlovelace.net/)
    - Manuel Gimond's [Intro to GIS and Spatial Analysis](https://mgimond.github.io/Spatial/)
4. Other Resources
    - Grant McDermott's [Data Science for Economists](https://github.com/uo-ec607/lectures) lecture notes
    - Andrew Heiss's [Data Visualization](https://datavizs21.classes.andrewheiss.com/) course materials

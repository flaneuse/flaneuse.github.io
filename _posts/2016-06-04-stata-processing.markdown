---
layout: post
title:  "Stata Cheat Sheets: analysis and visualization"
date:   2016-06-04 23:00:00
categories: Stata cheatsheet
img: "/img/StataCheatsheet_processing_June_2016_Processing.png"
icon: "/img/stata_processing_icon.png"
co-authors: Tim Essam
link: "http://geocenter.github.io/StataTraining/pdf/StataCheatsheet_processing.pdf"
---

Cheat sheets on data wrangling, analysis, and visualization in [Stata 14](http://www.stata.com).  Includes:

<br>

### Data Processing

* basic Stata syntax for all functions
* basic math and logic operations
* setting up working directories and log files
* importing data
  * `use`
  * `import excel`
* converting between data types
* exploring data files
  * `codebook`
  * `summarize`
* summarizing and collapsing data in tables
  * `tabulate`
  * `collapse`
* creating new variables
  * `generate`
  * `egen`

<br>

### Data Transformation

  * subsetting data
    * `drop`
    * `keep`
  * replacing data
    * `rename`
    * `replace`
    * `recode`
  * using variable and value labels
    * `label define`
    * `label list`
  * reshaping data (melting and casting)
    * `reshape`
  * merging and appending
    * `append`
    * `merge`
    * fuzzy-matching
  * string transformations
  * saving and exporting data
    * `save`
    * `export excel`

<br>

### Data Visualization
* small multiples
* one variable visualizations
  * `histogram`
  * `kdensity`: smoothed histogram
  * `graph bar`: bar plot
  * `graph dot`: dot plot
  * `graph hbox`: box and whiskers
* two variable visualizations
  * `tw scatter`: scatter plot
  * `tw connected`: line plot
  * `tw area`: area plot
  * `two pcspike`: parallel coordinates plot
  * `tw pccapsym`: slope/bump chart
* three variable visualizations
  * `plotmatrix`: heatmap
* plotting with summarization or fitting
  * `binscatter`: plot summary value
  * `tw lfitci`: linear fit
  * `tw lowess`: lowess smoothing
* plotting regression results
  * `coefplot`: regression coefficients
  * `marginsplot`: marginal effects
* Changing marks
    * symbology
    * lines
    * text
* Changing channels
    * size
    * color
    * shape
    * position
* Using themes
* Saving plots

<br>

### Data Analysis

* declaring data as a special type
  * time series
  * survival analysis
  * longitudinal/panel
  * survey
* summarizing data, correlations, point estimates, etc.
  * `summarize`
  * `pwcorr`
* statistical tests
  * t-tests, ANOVAs, proportions, distributions, etc.
* estimating models
  * `regress`
  * `logit`
  * delaring interactions within model
* evaluating models
* postestimation calculations (use model for something)
  * `predict`

<br>


### Programming

* fundamental data types
  * scalars
  * matrices
  * macros
* accessing stored results
  * `return`: r-class objects
  * `e-return`: e-class objects
* loops
  * `foreach`
  * `forvalues`
* additional programming resources: using [github](http://github.com) in Stata

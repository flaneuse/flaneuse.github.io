---
layout: post
title:  "Stata cheat sheets"
subtitle: "analysis and visualization"
summary: "Cheat sheets on data wrangling, analysis, and visualization in <a href='http://www.stata.com' target='_blank'>Stata 14</a>"
order: 5
tag: Stata
img: "/img/cheatsheets/"
icon: "/img/stata_processing_icon.png"
co-authors: Tim Essam
---

## Background
When teaching an [intro class on Stata]({{ site.baseurl }}/resources/stata-intro), we realized that there were no good reference materials on Stata. What started off as a "let's make a quick cheat sheet for the basic functions" quickly evolved into a comprehensive set of 6 cheat sheets on the common data wrangling and analysis functions within Stata.

<br>

## Solution
After cataloguing the most common functions, we organized them into six basic functional areas: basic data processing, data manipulation, data visualization, visualization customization, basic analysis, and basic programming. Then came the tricky part: how are all these functions related? What's the underlying logical and organizational framework? After sketching out these relationships, we created the layouts in Adobe Illustrator, heavily inspired by [Rstudio's amazing R cheat sheets](https://www.rstudio.com/resources/cheatsheets/).

<br>

#### [Data Processing](http://geocenter.github.io/StataTraining/pdf/StataCheatsheet_processing.pdf)

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

#### [Data Transformation](http://geocenter.github.io/StataTraining/pdf/StataCheatsheet_transformation.pdf)

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

#### [Data Visualization](http://geocenter.github.io/StataTraining/pdf/StataCheatsheet_visualization1.pdf)
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

#### [Data Analysis](http://geocenter.github.io/StataTraining/pdf/StataCheatSheet_Analysis.pdf)

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


#### [Programming](http://geocenter.github.io/StataTraining/pdf/StataCheatSheet_programming_2016_June.pdf)

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

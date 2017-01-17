---
layout: post
title:  "Custom R scripts"
subtitle: "reusable functions and snippets"
summary: "Customized functions in the R programming language for data analysis and visualization"
order: 1
tag: R
img: "/img/llamar"
icon: "/img/llamar_icon.png"
co-authors:
---

### Background:
Often, I have to do the same tasks in R, especially when it comes to data visualization. Rather than re-write the same things over and over again, I built reusable functions in R.

<br>

### Solution:
I've built out two R packages for use by myself and my colleagues: one focusing primarily on analysis of survey data and associated plotting using ggplot2 ([`llamar`](http://lauradhughes.com/llamar/)), and the other focused on mapping within R ([`geocenter`]().

<br>

View available functions at http://lauradhughes.com/llamar/.

<br>

These packages can be downloaded from github using the [`devtools`](https://www.rstudio.com/products/rpackages/devtools/) library:

`install.packages('devtools')`
`library(devtools)`
`install_github('flaneuse/llamar')`
`library(llamar)`

<br>

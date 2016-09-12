---
layout: page
title: Computing FAQ
order: 3
---

This page includes information on selected frequently asked questions relevant to setting up software and program files to follow along during the workshop. This is not a statistical consulting service; we do not respond to unsolicited inquiries. This page is updated as needed per the discretion of the workshop coordinators and presenters.

***

**Install [R]**

- Download R for free from [here](http://www.r-project.org/)
- Download Rstudio for free from [here](https://www.rstudio.com/products/rstudio/download3/)

**How do I install packages in [R]?**

Given a package named `"PACKAGE_NAME"` run the following code.

```r
install.packages("PACKAGE_NAME", dependencies=TRUE)
```

Then to load the package, run:

```r
library("PACKAGE_NAME")
```

**How do I execute code from an external program file?**

You might want to execute code form another [R] program file (e.g., code defining a custom function). Let this external file be named `filename.R` and reside in your working directory. Then the code you use to run the code in the file is:

```r
source("filename.R")
```
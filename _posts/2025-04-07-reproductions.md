---
title: "Reproducing a Study"
categories:
  - Blog
tags:
  - Reproducibility
  - GIScience
---

I have recently started a [project](https://github.com/jorredahl/RPr-Chakraborty-2021) in my Open GIScience class involving trying to reproduce the work by Jayajit Chakraborty studying Social inequities in the distribution of COVID-19: An intra-categorical analysis of people with disabilities in the U.S.[10.1016/j.dhjo.2020.101007](https://www.sciencedirect.com/science/article/pii/S1936657420301394?via%3Dihub). The study used early COVID-19 Data to find correlation between rates of disability and COVID-19 infection rate in US counties during the early stages of the pandemic. In my reproduction, I found similar but not identical results. In the end, my repreoduction found the same significant predictions that COVID-19 rates were higher in areas where there were high rates of disability among marginalized groups (black, hispanic, below poverty level, and female). However, there were discrepancies in the final results, notably: in the categories of black, non-hispanic non-white, below-poverty, and female disability rates, the coefficient values were higher in my study than the original.

This reproduction study was difficult for many reasons. For one, the proprietary software SATScan used by Chakraborty could not be used by me in order to fully open-source the project. Although some of the key formulas in my R script by SpatialEpi, the overall GEE clustering method should be the same. However, because of differeces in parameters between the two functions, I ended up with different reults.

If you want to see an html summary of this project, click this [link](https://jorredahl.github.io/RPr-Chakraborty-2021/01-R-markdown.html).
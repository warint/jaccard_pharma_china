
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Innovation in the Pharmaceutical Industry in China: A Jaccard Similarity Perspective

<!-- badges: start -->

<!-- badges: end -->

## Overview

The dataset is about innovation dynamics in the pharmaceutical industry
in China. Innovation dynamics is interpreted as knowledge transfer
across technologies and through time (velocity). The dataset provides
access to 143,916 Jaccard similarity indices. They proxy relatedness
across technologies (classes) and through time (velocity). They are the
result of a Natural Language Processing treatment of 69,923 patents in
the pharmaceutical industry in China from 1990 to 2017.

### Value of the Data

  - The Jaccard similarity indices computed in this dataset allow us to
    map patents’ relatedness in the Chinese pharmaceutical industry. The
    Jaccard similarity provides a cross-section relatedness and
    longitudinal cartography.

  - Researchers can benefit from these data to capture the actual
    dynamics of innovation, with a particular interest in knowledge
    creation and relatedness in China’s pharmaceutical industry. The
    data can also benefit policymakers and firms for the same reason.

  - Researchers in innovation can use the similarity indices as either a
    feature or a target variable in their models. As a feature variable,
    the similarity indices can help describe the success of some public
    policies, firms, or innovation ecosystems. As a target variable,
    they may help find the source of innovation dynamics in the Chinese
    pharmaceutical industry.

## Installation

You can install ipcR from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("warint/innovation_pharma_china")
```

## How-To

### Step 1: Getting the data

``` r
myData <- ipcr_data()
```

### Step 2: Creating visuals

The ipcr\_visual() function allows you to create four types of visual :
line, point, box and point charts.

``` r
ipcr_visual(chart = "line_1")
```

<img src="man/figures/README-unnamed-chunk-4-1.png" width="100%" />

# Mastering Data Visualisation: From Data to Art

## Description

This is a hands-on tutorial in which the data and code will be distributed to participants who wish to follow along. All tutorial lessons and materials will be provided and freely accessed. Participants will be required to have R and RStudio downloaded and installed on their personal computers, in addition to any required R packages. This tutorial assumes an intermediate level of R knowledge.

## Expected Goals

* Learn how to determine the type of plots that are best for your data
* Appreciate the power and flexibility of ggplot2 to create custom plots
* Know how to use custom functions and palettes to create figures with consistent themes, styles and colors
* Understand how to use R packages, such as cowplot and ggpubr, to easily add layouts and labels often required in published figures 
* Know how to save plots in a variety of formats

## Learning Objectives

* Determine the plot types best for visualizing a given dataset
* Define the syntax for creating a plot using ggplot2
* Generate plots for various data types using ggplot2
* Explain how to create multiple plots using the same themes, styles, and colors
* Discuss how to quickly alter figures to meet a different set of requirements (different journal or conference)

## Target Audience

Doctors/Researchers/Scientists with an intermediate background in R who interested in using R to create publication-ready figures. 

## Resources

* [ggplot2 free online book](https://ggplot2-book.org/index.html)
* [From Data to Viz online resource](https://www.data-to-viz.com)
* [Tidyverse ggplot2 online reference](https://ggplot2.tidyverse.org/reference/index.html)

### Dataset

Download the R project and data for this workshop [here](https://github.com/hbctraining/Training-modules/raw/master/data/publication_perfect.zip). Decompress and move the folder to the location on your computer where you would like to perform the analysis.

### Installation Requirements

Download the most recent versions of R and RStudio for your computer.
Please check the [Setup](https://monahton.github.io/emerald-berlin-2024/setup/) page for further information.

 - [R](http://lib.stat.cmu.edu/R/CRAN/) (Version 4.0 or higher)
 - [RStudio](https://www.rstudio.com/products/rstudio/download/#download)
 
Install the required R packages by running the following code in RStudio:

```r
# Install CRAN packages
install.packages("tidyverse")
install.packages("cowplot")
install.packages("ggpubr")
install.packages("RColorBrewer")
install.packages("viridis")
install.packages("scales")
install.packages("VennDiagram")
install.packages("pheatmap")
install.packages("png")
install.packages("ggrepel")
install.packages("ggplotify")
install.packages("magick")
install.packages("ggvenn")
```

Load the libraries to make sure the packages installed properly:

```r
# Load R libraries
library(cowplot)
library(ggpubr)
library(RColorBrewer)
library(viridis)
library(scales)
library(tidyverse)
library(VennDiagram)
library(ggvenn)
library(pheatmap)
library(png)
library(ggrepel)
library(ggplotify)
library(magick)
```


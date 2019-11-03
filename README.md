![](/visuals/iris_compound.jpg)

# R Graphics

This workshop will provide an introduction to graphics in R with ggplot2. Participants will learn how to construct, customize, and export a variety of plot types in order to visualize relationships in data. We will also explore the basic grammar of graphics, including the aesthetics and geometry layers, adding statistics, transforming scales, and coloring or panelling by groups. You will learn how to make histograms, boxplots, scatterplots, lineplots, heatmaps, and geographic maps using the Google Maps API. You will also learn how to facet plots and create compound figures. 

**Prior experience with R is assumed such as R-Fundamentals Parts 1 through 4 or equivalent knowledge.**

## Setup

1. [Download R](https://cloud.r-project.org/)  
2. [Download RStudio Desktop Open Source License FREE](https://rstudio.com/products/rstudio/download/#download)  
3. [Download the workshop materiasl](https://github.com/dlab-berkeley/R-graphics)  
4. Install the necessary packages by running the below code: 

```
install.packages(c("ggplot2", "cowplot", "dplyr", "ggmap"))

library(ggplot2)
library(cowplot)
library(dplyr)
library(ggmap)
```

Credit: Thanks to [Software Carpentry](http://software-carpentry.org/workshops/), Chris Paciorek, Rochelle Terman, Josh Quan, and the [R-bootcamp](https://dlab.berkeley.edu/training/r-bootcamp-3) for inspiration.

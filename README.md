![](/visuals/iris_compound.jpg)

# R Data Visualization with ggplot

This workshop will provide an introduction to graphics in R with ggplot2. Participants will learn how to construct, customize, and export a variety of plot types in order to visualize relationships in data. We will also explore the basic grammar of graphics, including the aesthetics and geometry layers, adding statistics, transforming scales, and coloring or panelling by groups. You will learn how to make histograms, boxplots, scatterplots, lineplots, and heatmaps. You will also learn how to facet plots and create compound figures. 

**Prior experience with R is assumed such as R-Fundamentals Parts 1 through 4 or equivalent knowledge.**

### Setup

1. [Download R](https://cloud.r-project.org/)  
2. [Download RStudio Desktop Open Source License FREE](https://rstudio.com/products/rstudio/download/#download)  
3. [Download these workshop materials](https://github.com/dlab-berkeley/R-graphics)  

**How to download the workshop materials**

* Click the green “Clone or download” button  
* Click “Download Zip”  
* Extract the files some place convenient (i.e., Desktop)  
  * if you are a Git user, simply clone this repository  by typing `git clone https://github.com/dlab-berkeley/R-graphics.git`

4. Install the necessary packages by running the below code: 

```
install.packages(c("ggplot2", "cowplot", "dplyr"))

library(ggplot2)
library(cowplot)
library(dplyr)
```

### Getting started

* Open the file "R-graphics-tutorial.Rmd". This contains the code walkthrough. Run a chunk of code by clicking the green "play" button in the upper right hand corner of each code chunk. Alternatively, place your cursor on a given line and press "command + Enter" (Mac) or "control + Enter" (PC) to run an individual line of code. 
* The file "ggplot2_challenges.Rmd" contains space for you to work on five challenge problems. 
* "ggplot2_challenges_solutions.Rmd" contains solutions to these challenges. 
* The "html" folder contains .html files of the rendered R Markdown files. 

Contributions by:
* [Evan Muzzall](https://dlab.berkeley.edu/people/evan-muzzall)
* [Lawrence Yin Tello](https://dlab.berkeley.edu/people/lawrence-yin-tello)
* [Josh Quan](https://dlab.berkeley.edu/people/josh-quan-0)

Credit: Thanks to [Software Carpentry](http://software-carpentry.org/workshops/), Chris Paciorek, Rochelle Terman, and the [R-bootcamp](https://dlab.berkeley.edu/training/r-bootcamp-3) for inspiration.

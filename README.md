# D-Lab's R Data Visualization Workshop

This repository contains the materials for D-Lab's R Data Visualization workshop. Prior experience with [R Fundamentals](https://github.com/dlab-berkeley/R-Fundamentals) is assumed.

## Workshop Goals

In this workshop, we provide an introduction to data visualization in R. First, we'll cover some basics of visualization theory. Then, we'll explore how to plot data in R using base R functions as well as `ggplot2`. We aim to cover the following types of plots:

* line plots
* bar plots
* scatter plots
* boxplots
* heat maps

We will also explore the basic grammar of graphics, including the aesthetics and geometry layers, adding statistics, transforming scales, and coloring or paneling by groups. Throughout the workshop, we'll discuss the plot types best suited for particular types of data. 

Basic familiarity with R *is* assumed. If you are not familiar with material in [R Fundamentals](https://github.com/dlab-berkeley/R-Fundamentals), we recommend attending that workshop first.

## Installation Instructions

We will use RStudio to go through the workshop materials, which requires installation of both the R language and the RStudio software. Complete the following steps:

1. [Download R](https://cloud.r-project.org/): Follow the links according to the operating system that you are running. Download the package, and install R onto your compute. You should install the most recent version (at least version 4.0).
2. [Download RStudio](https://rstudio.com/products/rstudio/download/#download): Install RStudio Desktop. This should be free. Do this after you have already installed R.
3. [Download these workshop materials](https://github.com/dlab-berkeley/R-Data-Visualization): 

* Click the green "Code" button in the top right of the repository information.
* Click "Download Zip".
* Extract this file to a folder on your computer where you can easily access it (we recommend Desktop).

4. Optional: if you're familiar with `git`, you can instead clone this repository by opening a terminal and entering `git clone git@github.com:dlab-berkeley/R-Data-Visualization.git`.

## Run the code

Now that you have all the required software and materials, you need to run the code:

1. Launch the RStudio software.

2. Use the file navigator to find the `R-Data-Visualization` folder that you downloaded from Github.

3. Double click on the `R-Data-Visualization.Rproj` file, and click "yes" when RStudio asks you to confirm whether you want to open up the project.

4. Open up the `R-Data-Visualization.Rmd` file, located in the `lessons` folder.

5. If you do not have the `cowplot`, `dplyr`, `ggplot2`, and `here` packages installed, be sure to install them using the `install.packages()` function in the first code block of the `R-Data-Visualization.Rmd` file.

6. Run a chunk of code by clicking the green "play" button in the upper right hand corner of each code chunk. Alternatively, place your cursor on a given line and press "Command + Enter" (Mac) or "Control + Enter" (PC) to run an individual line of code. 

7. The file `R-Data-Visualization-Challenges.Rmd` contains space for you to work on five challenge problems. The file `R-Data-Visualization-Challenges-Solutions.Rmd` contains the solutions to these challenges. 

## Is R not working on your laptop?

If you do not have R installed and the materials loaded on your workshop by the time it starts, we *strongly* recommend using the UC Berkeley Datahub to run the materials for these lessons. You can access the DataHub by clicking [this link](https://datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FR-Data-Visualization&urlpath=rstudio%2F&branch=main).

The DataHub downloads this repository, along with any necessary packages, and allows you to run the materials in an RStudio instance on UC Berkeley's servers. No installation is necessary from your end - you only need an internet browser and a CalNet ID to log in. By using the DataHub, you can save your work and come back to it at any time. When you want to return to your saved work, just go straight to [DataHub](https://datahub.berkeley.edu), sign in, and you click on the `R-Data-Visualization` folder.

If you don't have a Berkeley CalNet ID, you can still run these lessons in the cloud, by clicking this button:

[![Binder](http://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/dlab-berkeley/Python-Data-Visualization/HEAD)

By using this button, however, you cannot save your work.

# Additional Resources

Check out the following resources to learn more about data visualization and R:

* [R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/)  
* [The tidyverse style guide](http://style.tidyverse.org/)  
* [Software Carpentry](https://swcarpentry.github.io/) 
* [Quick-R](http://statmethods.net/)  
* [UCLA idre](https://stats.idre.ucla.edu/r/)  
* [R-bloggers](https://www.r-bloggers.com/)  
* [Stack Overflow - R](http://stackoverflow.com/questions/tagged/r)  

# About the UC Berkeley D-Lab

D-Lab works with Berkeley faculty, research staff, and students to advance data-intensive social science and humanities research. Our goal at D-Lab is to provide practical training, staff support, resources, and space to enable you to use R for your own research applications. Our services cater to all skill levels and no programming, statistical, or computer science backgrounds are necessary. We offer these services in the form of workshops, one-to-one consulting, and working groups that cover a variety of research topics, digital tools, and programming languages.  

Visit the [D-Lab homepage](https://dlab.berkeley.edu/) to learn more about us. You can view our [calendar](https://dlab.berkeley.edu/events/calendar) for upcoming events, learn about how to utilize our [consulting](https://dlab.berkeley.edu/consulting) and [data](https://dlab.berkeley.edu/data) services, and check out upcoming [workshops](https://dlab.berkeley.edu/events/workshops).

# Other D-Lab R Workshops

Here are other R workshops offered by the D-Lab:

## Basic Competency

* [Fast-R](https://github.com/dlab-berkeley/Fast-R)
* [R Data Wrangling](https://github.com/dlab-berkeley/R-wrang)
* [R Functional Programming](https://github.com/dlab-berkeley/R-functional-programming)
* [Geospatial Fundamentals in R with sf](https://github.com/dlab-berkeley/Geospatial-Fundamentals-in-R-with-sf)
* [Census Data in R](https://github.com/dlab-berkeley/Census-Data-in-R)

## Intermediate/Advanced Competency

* [Advanced Data Wrangling in R](https://github.com/dlab-berkeley/advanced-data-wrangling-in-R)
* [Unsupervised Learning in R](https://github.com/dlab-berkeley/Unsupervised-Learning-in-R)
* [R Machine Learning with tidymodels](https://github.com/dlab-berkeley/Machine-Learning-with-tidymodels)
* [Introduction to Deep Learning in R](https://github.com/dlab-berkeley/Deep-Learning-in-R)
* [R Package Development](https://github.com/dlab-berkeley/R-package-development)

# Contributors
* [Alexander Stephenson](https://dlab.berkeley.edu/people/alex-stephenson)
* [Pratik Sachdeva](https://dlab.berkeley.edu/people/pratik-sachdeva)
* [Evan Muzzall](https://dlab.berkeley.edu/people/evan-muzzall)
* Lawrence Yin Tello
* Josh Quan

Thanks to [Software Carpentry](http://software-carpentry.org/workshops/), Chris Paciorek, Rochelle Terman, and the [R-bootcamp](https://dlab.berkeley.edu/training/r-bootcamp-3) for inspiration.

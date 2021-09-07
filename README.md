# Introduction

This workshop shows how you can use and analyze the *Child Language Data Exchange System* (CHILDES) data base using R. All the files that are needed for this tutorial can be downloaded [here](https://github.com/AcqVALab/RCHILDES). 

## Aims

The aim of this workshop will be to introduce you to the Child Language Data Exchange System (CHILDES) data base and to show you how you can use it in your own studies.

The workshop consists of 2 parts:

1. **Introduction** on September 8:  this part shows how you can access and work with CHILDES data using R.

2. **Practical issues** on September 15: this part is a practical Q&A about your own studies and things that you want me to explain so that you can do your own research.

## Prerequisites

In order to follow the content of this workshop, you should already be familiar with R/Rstudio. If you are not familiar with R/RStudio, please go through [this introduction to R/RStudio](https://slcladal.github.io/intror.html). In addition, it is recommended to be familiar with regular expressions ([this tutorials](https://slcladal.github.io/regex.html) contains an overview of regular expressions that are used in this tutorial). 

You should also have downloaded  and installed R and RStudio. [This tutorial](https://slcladal.github.io/intror.html) contains links to detailed how-tos on how to download and install R and RStudio.

## Aims of the workshop

After this workshop, you should be able to 

* load files from the CHILDES data base into R/RStudio

* process and extract metadata from CHILDES files in R/RStudio

* search for words and phrases in CHILDES data using R/RStudio

* visualize and tabulate results in R/RStudio.  

## Why R?

You can analyze CHILDES data with a variety of tools, for instance with AntConc or CLAN. 


If you simply want to extract examples from CHILDES data, then I highly recommend you use AntConc - it is a very user-friendly, quick and intuitive concordancing program. However, if you want to perform analyses, then you need to combine AntConc with other software tools which renders such analyses more complex and cumbersome. As using different software tools to analyze CHILDES data is also complex, it makes sense to use R instead.

If you only ever want to analyze CHILDES data, then I strongly recommend you use CLAN (Computerized Language Analysis) as this tool was specifically designed to analyze CHILDES data. However, it is not a useful tool for other analyses of language data.

R is free, open-source, and a fully fledged and thus extremely powerful and flexible programming language. Once you have mastered R, you will be able to perform very complex and sophisticated tasks. As such, learning R is a very handy skill to have. In addition, the ability to write share-able scrips enables you to make your work flow 100% transparent and reproducible. Furthermore, once you have a script to perform certain task, you can re-use, copy, and edit it over and over again. 

## How to get started

1. On your computer, create a folder called *RCHILDES* (this will be our workshop folder). In that folder, create three sub-folders called:

* *data*
* *images*
* *tables*

2. Please download and install R and RStudio ([here](https://slcladal.github.io/intror.html#Installing_R_and_RStudio) is a more detailed description on how to download R and RStudio with links to additional document that will help you in case you encounter issues)

* R (just Google *download R* click on the top most website and follow the instructions)

* the Open Source License Free Desktop version of RStudio ([here is a link](https://www.rstudio.com/products/rstudio/download/) where you can download this version of RStudio).

## Working in RStudio

Once you have installed R and RStudio, open RStudio, click on `New Project`, then click on *Existing directory*, and then navigate to the *CHILDES_workshop* folder that you have just created and click *Enter*.

Then, download the file `childes_workshop.Rmd` from www. and store it in your workshop folder. Once you have stored the file in your workshop folder, you should see it in the lower right pane in RStudio. Double click that file. This should lead to the file opening in the upper left pane in RStudio.

All you have to do from here is to click on the *Knit* command which is located at the top-left edge of the upper left pane in RStudio. When you click on *Knit*, the rendered tutorial should appear in a new window.

To run code chunks, simply simply click on the green play button which is located at the top-right edge of code chunk. When you click on that play button, the code in the chunk will be executed and the result of the code chunk  may appear if the code has a visible output.

# The HSLLD

This section provides some info on the data that we will analyze in this workshop. In this workshop, we will use data from the *Home-School Study of Language and Literacy Development* (HSLLD) corpus which part of the CHILDES data base. The HSLLD is described in more detail below so that you have a more detailed understanding of the data we are dealing with in this workshop.

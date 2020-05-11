# FinalProject---
title: "Final Project"
output: html_document
author: "Group Member Names"
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = FALSE, comment="")
library(tidyverse)
#include other packages needed here
```

```{r, eval=FALSE, include=FALSE}
#include data cleaning code here, with comments on what each step is doing the indicators above eval=FALSE and include=FALSE will stop the code from running again when you knit the document while still keeping the code in the document
#use write_csv() to write your tidy data into a new csv file
```

```{r}
library (readr)

urlfile="https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2018/2018-12-18/allCetaceanData.csv"

mydata<-read_csv(url(urlfile))

#use read_csv() to import your new tidy data include any variable specifications here as needed
```

## Introduction
Description of data and problem(s) you are solving.  Include data source(s) here, either through citation or link to webpage.


## Graphic 1
Provide a brief description of your goal with your created graphic and what it demonstrates
```{r}
#include code for any data manipulation and variable creation used to create teh graphic as well as the code for the graph creation - be sure to comment all code with description of steps being completed with each line of code
```

## Graphic 2 - if two people in group
Provide a brief description of your goal with your created graphic and what it demonstrates
```{r}
#include code for any data manipulation and variable creation used to create teh graphic as well as the code for the graph creation - be sure to comment all code with description of steps being completed with each line of code
```


## Graphic 3 - if three people in group
Provide a brief description of your goal with your created graphic and what it demonstrates
```{r}
#include code for any data manipulation and variable creation used to create teh graphic as well as the code for the graph creation - be sure to comment all code with description of steps being completed with each line of code
```

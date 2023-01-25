# myrepo
Repository for testing my Git/GitHub setup

pacman::p_load(here)
pacman::p_load(readr)
pacman::p_load(jpeg)

install.packages("here")
library(here)
wcgs <- read_csv("CSV Files/wcgs.csv")
wcgs <- read_csv(here("CSV Files", "wcgs.csv"))
View(wcgs)
wcgs

library(jpeg)
image <- readJPEG(here("Images","Calculating-Confidence-Intervals.jpg"))
image <-
View(image)

str(wcgs)
head(wcgs)

image <- readJPEG(here("Images","Calculating-Confidence-Intervals.jpg"))

# Base R Dataset import
library(datasets)
datasets::iris
View(iris)

# Tibble Dataset import
library(tibble)
iris_t <- as_tibble(iris)
iris_t

library(tidyverse)
wcgs
colnames(wcgs)
rownames(wcgs)
(n=3154)
class(n)

# SPSS Dataset import
library(haven)
class <- read_sav("class.sav")
View(class)
class

# Stata Dataset import
library(haven)
ielts <- read_dta("ielts.dta")
View(ielts)
ielts

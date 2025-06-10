# ENVS-193DS_spring-2025_final

Spring 2025

## General Information

This dataset is from: Kui, L. (2024). Daily sea surface temperature in Santa Barbara channel between 1982 and 2023 ver 3. Environmental Data Initiative. [Dataset]. SBC - SST_update2023.csv https://doi.org/10.6073/pasta/e930954949b2635928b8be6824630f84

This dataset is from Stojanovic, Dejan; Owens, Giselle; Young, Catherine; Alves, Fernanda; Heinsohn, Robert (2021). Do nest boxes breed the target species or its competitor? A case study of a critically endangered bird. [Dataset]. Drydad - occdist.csv
https://doi.org/10.5061/dryad.83bk3j9sb

This repository includes all the data and code for my Final Assignment. 

### Packages
```{r message=FALSE, warning=FALSE} 
## Packages
library(tidyverse) # general use
library(here) # file organization
library(gt) # creating summary tables
library(flextable) # creating summary tables
library(janitor) # cleaning data frames
library(lubridate) # organize dates and time
library(DHARMa) # run diagnostics
library(MuMIn)  # model selection
library(ggeffects) # getting model predictions
```

## Data and File Overview

File Structure:

```
├── README.md
├── .gitignore
├── code                                          # code folder
│   ├── ENVS-193DS_spring-2025_final.Rproj          # R project    
│   ├── Final_files                                 # final files
│   ├── Final.html                                  # website files
│   ├── Final.qmd                                   # quarto document 
└── data                                          # data folder
│   ├── occdist.csv                                 # nesting data
│   ├── SST_update2023.csv                          # sea surface temperature data
``` 

All code is in the `code` folder. The code runs models, generates model predictions, and visualizes data.

## Rendered Output

The rendered website is [here](). 




# Examining The Roots of Environmental Injustice in Minneapolis

By Na Nguyen and Charles Batsaikhan.

In the 1920s, Minneapolis introduced racial covenants to prevent non-white people from occupying and owning land. As Minnesota witnessed the wave of the First Great Migration, it also legitimized housing discrimination via restrictive clauses inserted into property documents since the presence of non-White, but especially Black people, was regarded to decrease property value. This racist real estate practice paved the way to redlining in the 1940s to decrease home-ownership rates of African American, contributing to their generational dispossession and displacement ([Source 1](https://www.sciencedirect.com/science/article/pii/S0169204624000197)
[Source 2](https://www.proquest.com/openview/7b2c258bfcf31cbb48629dce3a226693/1?pq-origsite=gscholar&cbl=18750&diss=y)).

There has been extensive research that definitively proves disproportionate effects and exposure to pollution is linked to geographically disadvantaged and vulnerable communities. However, these research tend to merely provide a snapshot of this picture at a moment in time. Therefore, we would like to contextualize these single portraits of inequality by investigating the relationship between modern day environmental inequality in Minneapolis and 1920’s racial covenants practice.

The research question we would like to explore is as follows: Looking at historically racially covenanted neighborhoods in Minneapolis and present day environmental data, can we still see its impact in the disparity of climate change effects? In other words, *did the introduction of racial covenants in the 1920s cause air pollution inequality in the city of Minneapolis that we see today?*

## Navigating this code repository

### data
This `data` folder holds all of our utilized data, raw and clean. Our data cleaning process is captured in `data_cleaning.qmd`

## index
The `index.qmd` holds all of our causal inference code work and analysis. The `index.html` is a rendered version of this file.

## Code Dependencies 
The following packages should be installed into RStudio before running our files:

```
library(dplyr)
library(tidyverse)
library(sf)
library(tidycensus)
library(tigris)
library(readr)
library(dagitty)
library(EValue)
library(MatchIt)
library(broom)
library(leaflet)
library(marginaleffects)
library(scales)
library(RColorBrewer)
library(spdep)
library(spatialreg)
```

## Related work
This work is part of a larger project that can be found in this [repo](https://github.com/gnguyen87/ds456_nrmc) and is also published on this [website](https://gnguyen87.github.io/ds456_nrmc_website/).

## Acknowledgments
We extend our gratitude to Professor Leslie Myint (Macalester College, MN) for her invaluable guidance and input throughout this project.

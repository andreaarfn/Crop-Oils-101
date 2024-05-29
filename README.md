# Crop Oil Yield Dashboard

This repository contains the code and data for the Crop Oil Yield Dashboard. The dashboard visualizes various crop oil yields across different countries and regions, based on FAOSTAT data retrieved in May 2024.

https://www.fao.org/faostat/en/#data/QCL

## Project Contents

- `cropoil.csv`: Contains the dataset used in the project. 
- `project.Rmd`: Contains the R scripts for the dashboard.


## Required Libraries

Download the following libraries in R-Studio by copying these lines in Console:
- install.packages(shiny)
- install.packages(plotly)
- install.packages(dplyr)
- install.packages(readr)
- install.packages(leaflet)
- install.packages(tidyr)
- install.packages(rnaturalearth)
- install.packages(rnaturalearthdata)
- install.packages(sf)


## How to Run

1. Download this repository.
2. Open RStudio.
3. Download the required libraries by copying the lines in Required Libraries in Console.
4. Import `cropoil.csv` in the RStudio environment 
5. Open the `project.Rmd` R Markdown file and run it to generate the dashboard.



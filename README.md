# Cyclistic-Data-Analysis-Google-Case-Study
This project is the capstone for the "Google Data Analytics Professional Certificate" on Coursera.  
The dataset and business context were provided by the course, but all analysis and conclusions are my own work.

## Project Context

The fictional bike-share company "Cyclistic" (based in Chicago) wants to revise its marketing strategy.
As a junior data analyst on the marketing team, my task is to analyze user behavior and provide insights to support a data-driven decision.

Initial situation : the marketing director wants to change the marketing strategy. She believes that the future success of the company depends on the number of annual subscriptions. Until now, the target audience has been the general public, but she now thinks it's a good idea to focus on occasional users and get them to sign up for an annual subscription.

## Project Structure

```bash

├── data/       # Excel datasets (2019 & 2020)
│   ├── cyclistic_2019.xlsx
│   └── cyclistic_2020.xlsx
├── raw_data/       # Raw data files as originally provided
│    ├── Divvy_Trips_2019.xlsx
│    └── Divvy_Trips_2020.xlsx           
├──    cyclistic-notebook.ipynb     # Analysis notebook (R)
└── README.md       # Project documentation
```

## How to Run

This project is written in **R** and runs in a Jupyter Notebook environment (.ipynb) using the R kernel.
To run the analysis, make sure the following packages are installed:

```R
install.packages("readxl")
install.packages("here")
install.packages("tidyverse")
install.packages("ggplot2")
install.packages("lubridate")
```

You also need the IRkernel to run R in Jupyter. If not already installed:

```R
install.packages("IRkernel")
IRkernel::installspec()
```



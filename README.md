# Bayesian Prediction of High-magnitude Earthquake Timing

A Bayesian framework for modeling the time between major earthquakes and estimating when the next event is likely to occur. 
Because it conditions on the time since the last quake, its estimates stay current until the next global M8+ (currently on 2025-07-29 Kamchatka earthquake).

## Rean Du, Oliver Chu, Daniel Ernesto Santos, Keerthana Girish

## Repository Structure


```
├── finalProject.Rproj
├── model
├── data
    ├── earthquake.csv
    ├── earthquakePrior.csv
├── analysis.Rmd
├── presentation.qmd
├── pic
    ├── recentGlobalM8.png
└── README.md
```


## Data

All data files live in the `data/` folder: global M8+ earthquakes from the USGS earthquake catalog.

- `data/earthquakePrior.csv`: [1900-1950](https://earthquake.usgs.gov/earthquakes/map/?extent=-88.99557,-273.51563&extent=88.99557,634.21875&range=search&search=%7B%22name%22:%22Search%20Results%22,%22params%22:%7B%22starttime%22:%221900-01-01%2000:00:00%22,%22endtime%22:%221950-01-01%2000:00:00%22,%22minmagnitude%22:8,%22orderby%22:%22time%22%7D%7D) earthquakes for prior
- `data/earthquakes.csv`: [post-1950](https://earthquake.usgs.gov/earthquakes/map/?extent=-88.99557,-273.51563&extent=88.99557,634.21875&range=search&search=%7B%22name%22:%22Search%20Results%22,%22params%22:%7B%22starttime%22:%221950-01-01%2000:00:00%22,%22endtime%22:%222026-08-08%2023:59:59%22,%22minmagnitude%22:8,%22orderby%22:%22time%22%7D%7D) earthquakes for analysis

##  Documents

- `model.qmd`: theoretical model structure
- `analysis.Rmd`: data analysis and model fitting
- `presentation.qmd`: project slides



# Bayesian prediction of High-magnitude Earthquake Timing

A Bayesian framework for modeling the time between major earthquakes and
estimating when the next event is likely to occur.

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

All data files live in the `data/` folder: global M8+ earthquakes from the USGS earthquake catalog [link].

- `data/earthquakePrior.csv`: pre-1950 earthquakes for prior
- `data/earthquakes.csv`: post-1950 earthquakes for analysis

##  Documents

- `model.qmd`: theoretical model structure
- `analysis.Rmd`: data analysis and model fitting
- `presentation.qmd`: project slides



## 512 Project

This repository is for the final project of DATA 512 for Fall 2022. 

## Part 1 Analysis
Part one analysis can be found in part1.ipynb. The data comes from 3 different sources 
    - [Johns Hopkins University COVID-19 Data](https://www.kaggle.com/datasets/antgoldbloom/covid19-data-from-john-hopkins-university)
    - [masking mandatas by county](https://data.cdc.gov/Policy-Surveillance/U-S-State-and-Territorial-Public-Mask-Mandates-Fro/62d6-pm5i)
    - [masking compliance survey](https://github.com/nytimes/covid-19-data/tree/master/mask-use)

The county in question is Baltimore county, Maryland. The goal of this analysis is to see how masking policy and adherence impacts the spread of COVID-19. To explore this question I analyzed case data as well as policy data to see if there were any timepoints of interest in the time series data that aligned with policy changes.

## Part 1 Results
![Part 1 Results](./graphs/changepoint.png)

This graph shows the results from using the Pelt changepoint algorithm on percentage change in daily case data. Overlaid are the dates of all of the policy changes that Baltimore county instated. The red regions are candidates for changepoints in the timeseries. Using these three, I was able to identify a couple of specific policies that  were of interest with respect to percentage change in daily cases.
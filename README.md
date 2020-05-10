# covid19-analysis

## Overview
Python notebook [covid2.ipynb](https://github.com/danlaw/covid19-analysis/blob/master/covid2.ipynb) builds basic country-based charts on the spread of COVID19 based on JHU CSSE's https://github.com/CSSEGISandData/COVID-19, and state-based charts based on data from New York Times' https://github.com/nytimes/covid-19-data, and US county-based charts based on data from ![USAFACTS](https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/)

Note: [covid.ipynb](https://github.com/danlaw/covid19-analysis/blob/master/covid.ipynb) builds charts on data from JHU CSSE's older and now depracated COVID19 data files.

## How to use
Just open the notebook covid2.ipynb in a tool like JupyterLab. Must have basic python libraries installed (pandas, numpy, matplotlib, seaborn).

You can change variables like ``MovingAveDays`` to adjust the number of days in the moving average.

## Latest chart
![Latest chart](charts/20200509-covid19-chart.png)

## New chart comparing new cases per day vs deaths per day (x 20 for visible comparison)
![Comparison chart](charts/20200509-comparison-chart.png)

## New chart comparing new cases per day vs recoveries per day
![Recovery chart](charts/20200509-comparison-recovery-chart.png)

## New chart comparing all US territories (cases and deaths x 20)
![Territories chart](charts/20200509-compare-US-territories.png)

## New chart comparing ratio of new cases urban vs rural (adjusted per capita)
![Urban rural per capita chart](charts/20200509-US-counties-urban-vs-rural-per-capita.png)
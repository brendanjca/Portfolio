# Portfolio

## Table of Contents

- [About](#about)
- [My Background - How I Became a Data Analyst](#my-background---how-i-became-a-data-analyst)
- [Juno Projects](#juno-projects)
  * [Investigating Customer Retention](#investigating-customer-retention)
  * [Testing a Trading Strategy on a Major US Index](#testing-a-trading-strategy-on-a-major-us-index)
  * [Forecasting Future Sales in Walmart Stores](#forecasting-future-sales-in-walmart-stores)
  * [Predicting Days On the Market for Condos in Richmond BC](#predicting-days-on-the-market-for-condos-in-richmond-bc)

## About

This is a repository that I've created to track my progress in data analysis/AI/data science-related topics. The main purposes are for self-motivation, open-source material for others, a portfolio, and a to-do list.

Check out my Tableau Public [here](https://public.tableau.com/app/profile/brendanjca#!/?newProfile=&activeTab=0).

## My Background - How I Became a Data Analyst

In September 2021, I enrolled in the Juno College Data Analysis Bootcamp. Throughout my time there, I have gained a solid understanding of the **ETL** (Extract, Load, Transform) process and multiple industry-standard technologies.

The tech that I learned at Juno: **Sheets/Excel**, **SQL**, **Tableau**, **Python**.

## Juno Projects

Below is a list of projects that I completed while I was attending Juno.

### Investigating Customer Retention
The objective of this project was to investigate retention for players of a mobile app by using a relational database and writing queries to aggregate data for the purposes of reporting and visualization.

The main things we wanted to figure out where determining the **30-day rolling retention rate**, the age of the players, the location of the players, and individual spending in the app.

Tech used: **SQL** (for querying databases and performing calculations), **Sheets** (for visualizations).

[Click here to view the project](https://github.com/brendanjca/Portfolio/tree/main/Customer%20Retention%20Project)

### Testing a Trading Strategy on a Major US Index
I tested a trading strategy found on SeekingAlpha.com to see how it performed compared to buy-and-hold, and then I tried to tweak it to see if I could make any further improvements.

By adding a simple regime filter (only taking buy signals when price closed above the 200 exponential moving average), I was not able to improve the overall return, but I was able to significantly improve the risk-adjusted returns by lowering drawdown and decreasing the net exposure.

Tech used: Sheets (cleaning, feature engineering and backtesting the strategy), Tableau (visualizing results).

[Click here to view the Google Sheet](https://docs.google.com/spreadsheets/d/1R3bi2yO4T7jkQPyNRhOs1266X0roEEDxPwvCgRSsFyo/edit?usp=sharing)

[Click here to view the Tableau viz of the results](https://public.tableau.com/app/profile/brendanjca/viz/Project2_16364032426860/Story1)

### Forecasting Future Sales in Walmart Stores
Using [this dataset](https://www.kaggle.com/divyajeetthakur/walmart-sales-prediction) found on Kaggle, I ran a linear regression model to try to predict future sales. The model was able to achieve a +95% accuracy rate.

Tech used: Python (feature engineering, pre-processing, modelling and visualization).

[Click here to view the Jupyter Notebook for this project](https://github.com/brendanjca/Portfolio/blob/main/Walmart%20Sales%20Forecast%20Project/Walmart%20Data%20Project.ipynb)

### Predicting Days On the Market for Condos in Richmond BC
Using a proprietary dataset containing all the condo listings that have been sold in Richmond, BC since 2008, I analyzed trends in the condo market and tried to develop a model that is able to predict how long a given condo would take to sell. This information would be useful for both buyers and sellers to determine how liquid and in-demand a listing is.

In the end I was able to develop a random forest classification model that was able to predict DOM within 2.59 weeks.

Tech used: Tableau (visualization, basic analysis of trends), Python (cleaning, pre-processing, modelling).

[Click here to view the Tableau viz](https://public.tableau.com/app/profile/brendanjca/viz/TableauRichmondCondo/Story1?publish=yes)

[Click here to view the Jupyter notebook for this project](https://github.com/brendanjca/Portfolio/blob/main/Richmond%20Condo%20Project.ipynb)

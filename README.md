# Project Overview

This project is for Machine Learning practice. I will learn how to predict the winner of football matches in the English Premier League (EPL).

**Project Steps**

-   [x] Scrape match data using request, BeautifulSoup, and pandas.
-   [x] Clean the data and get it ready for machine learning using pandas.
-   [x] Make predictions about who will win a match using scikit-learn.
-   [x] Measure error and improve our predictions.
-   [ ] Add comments on code

## Code

The code will be in two files:

-   `matches.ipynb` - a Jupyter notebook that scrapes our data.
-   `predictions.ipynb` - a Jupyter notebook that makes predictions.

# Local Setup

## Installation

To follow this project, this is needed locally:

-   JupyterLab
-   Python 3.8+
-   Python packages
    -   pandas
    -   requests
    -   BeautifulSoup
    -   scikit-learn
    -   html5lib

## Data

I will be scraping [FBref](https://fbref.com/en/) to get the data first.

For the predictions, I will be using the CSV file with all the data scrapped.

## Disclaimer

After running the code I found a couple of issues:

-   FBref does not kicks me out of the server regarless of fulfilling the 3 seconds minimun rest betweent requests.
-   To have a better dataset I manually set each link of the season I wanted to scrape.

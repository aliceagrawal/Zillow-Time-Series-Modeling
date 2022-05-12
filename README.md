# Zillow-Time-Series-Modeling

## Phase 4 Project

### Authors

- Alice Agrawal: 
[LinkedIn](https://www.linkedin.com/in/alice-agrawal/) | 
[GitHub](https://github.com/aliceagrawal) | 
[Email](mailto:alice.agrawal30@gmail.com)

- Hanis Zulmuthi: 
[LinkedIn](https://www.linkedin.com/in/hanis-zulmuthi/) | 
[GitHub](https://github.com/hanis-z) | 
[Email](mailto:haniszulaikha96@gmail.com)

- Jordan Kominsky: 
[LinkedIn](https://www.linkedin.com/in/jordan-kominsky/) | 
[GitHub](https://github.com/jskominsky) | 
[Email](mailto:jskominsky@gmail.com)

- Kyongmin So: 
[LinkedIn](https://www.linkedin.com/in/kyongminso/) | 
[GitHub](https://github.com/kyongminso) | 
[Email](mailto:kyongminso@gmail.com)

- Tyler Wood: 
[LinkedIn](https://www.linkedin.com/in/tyler-wood-08a036216/) | 
[GitHub](https://github.com/twood2015) | 
[Email](mailto:T.wood20151996@gmail.com)


## Overview

Our stakeholder is the biggest real estate investment firm in the United States, Keller Williams Realty, and they have hired our team at AM to determine which cities with big tech companies’ presence in the country represent good potential investment opportunities. We will use time series forecasting to analyze the median sale price for 10 cities in the countries to determine the 5 cities with the highest predicted return.


## Business Problem

Our team was hired by Keller Williams Realty, a real estate investment firm, to use time series forcasting to predict the best cities to make real estate investments in.  The cities we chose were from a list of the top 10 cities for technology jobs.  


## Data

We obtained the data used in our time series analysis from a Zillow API. It measured the average home price in about 15,000 different zip codes from the year 1996 to 2018. We aggregated the zip codes together into 10 of the most prominent tech cities based on an article from Indeed. 


## Methods

We used an ARIMA model to forecast the average house price in 10 cities. WE used ACF and PACF to build the model. We score the model predictions using explained variance and root mean squared error. 

## Next Steps

For our next steps, we would dig deeper into the years that were affected by COVID-19 and analyze how the pandemic affected the housing market. We would also make a model that includes outside variables, such as the school district, housing density, or the income of the residents.  We would try running our data through a Long-Short Term Memory neural network that could find patterns hidden to our current model. 


## Repository Structure
```
 ├── Data
 ├── Images
 ├── gitignore
 ├── Individual Notebooks
 ├── Final_Notebook.ipynb
 └── README.md
 └── Presentation.pdf
 ├──LICENCE
```

# demand-forecasting-avocados
What is the predicted demand for avocados over the next 6 months?

After preliminary data exploration to explore the relationship between the demand and other crucial factors like pricing strategy, product type, and geographic region of sale, I attempted the following models to predict the demand: 

1. **Simple linear regression**
2. **Time series regression** (which allows for fourier terms to capture seasonality)
3. **ARIMA forecasting without regressors** along with the **naive forecast**, which will serve as *benchmark metrics*
4. **ARIMA forecasting with regressors**
5. **Seemingly Unrelated Regression** (SUR) to capture the correlation of errors across region-specific linear models
6. An **ensemble** of SUR and ARIMA models, which is a simple average over the two

As we will learn later, the ensemble model performs the best on an aggregate level.

**I also explored the price elasticity of demand for different regions.**

The pdf file in this repository contains my detailed approach to explore this project. 

The rmd file contains the entire code I used for this project. 

<h1>Time Series Analysis of Ames Housing Data</h1>

<h2>Description</h2>

This project is a group output for my junior-year mathematics class on Time Series and Forecasting. For this project, we were tasked with building and evaluating a time series model using real-world data.

Below is the abstract from our final project paper:

<i>
This project explores the Ames Housing dataset as a high-quality alternative to the Boston Housing data. Focusing on three-bedroom houses sold in Ames, Iowa between 2006 and 2010, a time series model was constructed based on the average monthly sale price in order to forecast the average sale price for the next two months. The time series was tested for stationarity using the augmented Dickey-Fuller test, which revealed non-stationarity. This was addressed through differencing. Subsequent augmented Dickey-Fuller and Ljung-Box tests revealed stationarity and autocorrelation, respectively. Analysis of the autocorrelation and partial autocorrelation functions, as well as the Akaike information criterion (AIC) and parsimony, suggested that an ARMA(1,1) model best fit the time series for the differenced data. The chosen model was found to be both causal and invertible. Forecasting using this model predicted a sharp increase in average monthly sale price for three-bedroom houses in the next two months.
</i>
<br />

<h2>Documents</h2>

- [Paper (with R code)](https://github.com/andreazialcita/Time-Series/blob/main/MATH-62.2-Project-Paper.pdf)

- [Presentation](https://github.com/andreazialcita/Time-Series/blob/main/MATH-62.2-Project-Presentation.pdf)

<h2>Concepts Used</h2>

- <b>Stationarity Testing</b> (Augmented Dickey-Fuller Test)

- <b>Differencing</b>

- <b>Model Identification</b> (using ACF, PACF, and AIC)

- <b>ARMA Modeling</b>

- <b>Forecasting</b>

- <b>Model Diagnostics</b> (Ljung-Box test, causality, invertibility)

<h2>Software Used</h2>

- <b>R</b> 

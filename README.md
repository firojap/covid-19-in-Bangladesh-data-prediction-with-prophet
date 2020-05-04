# 'Analyze and Prediction of COVID-19 Data of Bangladesh by Using Prophet.'

### Introduction
This is the very first time after the second world war people have facing a massive hindrance of their daily life in terms of health and economic due to COVID-19 outbreak. It's almost 212 countries, more than 35 lac people affected and near about 2.5 lac deaths by COVID-19 by today. Bangladesh is one of the victim countries of COVID-19. It's 9455 confirmed cases and 177 deaths in Bangladesh due to corona virus. Bangladesh prime minister has already declared a country lock down up to 15 May. It would play a massive effect in the country's economy. In this project, I have tried to predict the next 7 days corona affected cases in Bangladesh by using Facebook prophet library.
### Aim of the Project
The aim of this project is to predict the effect of corona virus for upcoming days in Bangladesh. By using Machine Learning I have tried to identified the trend of spread the corona virus over Bangladesh and what maybe the number of infection in next 7 days.
### Data Source
To do this project I used the data from Institute of Epidemiology, Disease Control and Research (IEDCR) of Bangladesh. (www.iedcr.gov.bd). Beside this, I also followed WorldOmeter (www.worldometers.info/coronavirus/) and John Hopkins University (coronavirus.jhu.edu/map.html) websites.
### Machine Learning Tools and Packages
To predict the trend of spread the corona virus for upcoming days, obviously we have to choose a time series forecasting technique. There has a lot of time series forecasting technique like as SIR model, Fuzzy Time Series Forecasting Technique, Facebook Prophet Library and so on.
Among all those well established techniques, I choose Facebook Prophet Library due to its comprehensiveness and easy to understand. Time series prediction are difficult and always require a very specialized data scientist to implement it. But Prophet is very easy to understand and anybody can implement it who has a little knowledge in time series.

### Predicting the COVID-19 Cases Using Prophet
As we know Prophet can only take a certain format of data and that's why I made my data in two columns: 'Date' and 'Confirmed cases'. I made a .xlsx format data file from the very first confirmed cases 8 March, 2020 to 1 May, 2020. Here I took 55 days of historical COVID-19 data.
I did everything of analysis in Google Colab and at first I install 'pystan', because Prophet made with this package. Then I installed 'fbprophet' and call 'prophet' from it. Also I imported 'numpy', 'pandas' and 'matplotlib' library. After import data file I made some visualization of data and finally went in forecasting. Here I didn't take seasonality because COVID-19 isn't seasonal. I made 7 days forecasting and found an exponentially increasing trend. That means corona will infecting increasingly for upcoming days.
### Conclusion
This prediction indicate an alarming spread of corona for upcoming days in Bangladesh. Government should take more proper steps to protect the spread of virus.

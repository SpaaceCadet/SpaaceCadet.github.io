---
title: "<b>FBprophet forecasting with anomalies detection
</b>"
excerpt: "<i>Modeling seasonal time series Data using Fbprophet and anomalies Detecting anomalies using Isolation Forest</i>
<br/><a href='https://github.com/SpaaceCadet/FBprophet_seasonal_time_series'><img  width='500' height='300' src='/images/prophet.png'></a>"
collection: portfolio

---
- FBprophet gained so much popularity in modeling seasonal time series data , it has many robust tools to handle : 
   - Time series withs known gaps .
   - Complex Periodic phenomenons such as conditional seasons.
   - Robust methods to handle outliers changes in trends changes in seasonal components , holidays and special events.
- It's a framework based on bayesian statistics , and Fourier decompositions concepts , using  smoothing techniques to estimates important patterns in the data .
- This Jupyter notebook represent a gentle presentation of the general concepts of FBprophet .
- We used the Nyc passengers dataset which can be found on this link : "https://github.com/numenta/NAB/tree/master/data/realKnownCause" , which is affected by some holiday and special events, which we will handle using Fbprophet methods to handle these special cases .
- We used Isolation forest algorithme to catch anomalies in the data and show the strength of their effect .
- The fine tuning was done by Optuna which is a bayesian optimization algorithme , to add some regularization effect . and get the right hyperparameters for our holidays effects .
<br>
<a><img src='/images/prophet.png'></a>
<br>

<a href='https://github.com/SpaaceCadet/FBprophet_seasonal_time_series'>For more details</a>


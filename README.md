# Time-Series-Analysis-Assesment
TECHNICAL REPORT FOR TIME SERIES ANALYSIS.

TASK-1: KEY INSIGHTS OF THE DATA
Insight 1:  
Checked the given Time series data is stationary data or non stationary data 
Used Test : ADF Test ( Augmented Dickey Fuller Test) using library -statsmodels.tsa.stattools form that import adfuller module
Goal: Finding the data has Unit-Root or not
Set the hypothesis ,Run test statistic by  Calculating p-value , based on comparison with significance result will be shown.

Insight 2: 
 Using Time decomposition EDA concept . I analyzed the data with Time decomposition components for Identifying patterns and understand the trend .
Used Library: statsmodels.tsa.seasonal library is used to find Trends and seasonality components of Time decomposition. Module- Seasonal Decompose

Insight 3:
Executed residual component analysis by removing the Trend and seasonal component . Module:statsmodels.tsa.seasonal 
Executed Autocorrelation to identify Lags for the Arima model.

Goal: Looked for the random left-over noise to make sure there is no unpredictable fluctuations. Autocorrelation to understand how past values relate to current values, providing insights for accurate forecasting and analysis.

 Insight 4:
The analysis of monthly  usage trends of services provides valuable insights into the performance and patterns of various public transport services over time.

TASK-2 : FORECASTING
Used Arima model (Auto regressive Integrated Moving Average) to forecast the        data for next seven days.
Executed Autocorrelation to determine the Lags and relationship between past values.
Why Arima : By using ADF test we determine given dataset consists of stationary data . Arima is one of the  best model for stationary data .
Incase the data is Non stationary . We execute different technique to make it stationary . for instance :Techniques like Differencing and  Log transformations can be used.
	


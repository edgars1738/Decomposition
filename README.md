# Decomposition

## This assignment performs different types of decomposition, such as STL, Seasonally Adjusted, and Classical Decomposition

### Below is what was done on this assignment:
- Loading the required packages, importing the data set and converting into monthly time series.
- Separating the data into trend, seasonal, and remainder components using STL assuming the seasonal pattern stays consistent over time.
- Removing the seasonal component using STL to highlight underlying data patterns. Since the original data set is already seasonally adjusted, the STL-adjusted series may differ from the original because STL estimates its own seasonal component.
- Forecasting the next 15 monthly periods using STL decomposition, displaying predicted values and prediction intervals, and plotting the forecast against historical data.
- Using classical decomposition to separate the data into trend, seasonal, and remainder components and plotting the results.
- Removing the estimated seasonal component using classical decomposition and plotting the adjusted data to highlight underlying patterns. 

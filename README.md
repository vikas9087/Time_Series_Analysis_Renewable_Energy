# Time Series Analysis of Wind Speed & Solar Energy
In 2019, the solar power (in MW) available for renewable energy generation was recorded every five minutes at a location in California. The wind’s speed (in MPH) was also recorded at the same location every 10 minutes. The data is available in `Energy.xlsx`.

Since the data is collected at an interval of 5 & 10 minutes, we first prepared the daily maximum solar energy required & maximum wind speed. This way have have 365 observations for both the series. Then data visualization graphs such as time series plot, box plot prepared to understand the data. Then ACF & PACF of both series is plotted. We also checked the [Augmented Dickey–Fuller test](https://en.wikipedia.org/wiki/Augmented_Dickey%E2%80%93Fuller_test) for checking whether the series is stationary or not.

Once basic data cleaning and visualization is completed, then a user defined function is created for searching the best [SARIMA](https://online.stat.psu.edu/stat510/lesson/4/4.1) model. We used the AIC, BIC, & MSE statistics to select the best models. Then for the selected best models, 30 days ahead forecast is plotted with 95% confidence interval.



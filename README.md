# Forecasting-Snow-and-Ice-Depth-the-Summit-of-Mt-Washington-NH

This project used Facebook Prophet to perform time series forecasting of Snow/Ice Depth on the summit of Mt. Washington. As a hiker, I have found that the inability to accurately forecast the snow/ice depth on mountain summits is one of the most difficult challenges in planning a hiking trip, as this effects the footwear, clothing, and gear you need to bring. This has implications for hiker safety.

I scraped the weather data from the Mt Washington Observatory website, converting the pdf data tables to csvs using Tabula. I performed the cleaning and analysis in Python.

Next steps for this project are improving the accuracy of the model by including addtional regressors such as lag regressors and highly correlated variables such as temperature, wind, and precipitation.

Ultimately, I would like to use this machine learning model to accurately predict short-term snow/ice depths on the summit of Mt. Washington by integrating weather forecast information from mountain-forecast.com, which forecasts correlates of snow/ice depth such as max temp, min temp, snowfall, rainfall, and wind 6-days into the future. This would to allow someone to get an accurate projection of the depth of snow/ice on the summit up to 6 days in advance, allowing for proper planning on hiking trips.

# Sales Forecasting Project Using Linear Regression
<h2>Description</h2>

Demonstrated understanding of machine learning by creating a brief sales forecasting model by leveraging linear regression to forecast sales 1 year into the future based on historical data. 
1. I first cleaned and prepared the dataset for model training.
2. Then I split the data into training and testing sets based on date (training set was 2013 to end of 2016 and testing set was 2017).
3. I modeled and measured the fit of the test set of 2017 to the actual sales of 2017.
4. After I had determined the model to be quite accurate when comparing it to the actual data, I added future dates (up to the end of 2018) onto the model to begin my forecast.
5. I went on to create a forecast for the next year of sales using the last 12 months of actual sales from the dataset.

<h2>Results</h2>

Measured fit of model to actual data. 
* R-squared Score: 0.990615
* Mean Absolute Error: 12433.184
* Mean Squared Error: 263129677.801
* Root Mean Squared Error: 16221.272
* Correlation Coefficient: 0.99594063

Overall, the model has a very close fit to the actual data, also shown below.

![image](https://github.com/javamesql/Sales-Forecasting_LR/assets/141413672/66ba3740-190e-46de-bf50-efc45b0607b2)

------------------------------------------------------------------------------------------------------------------------------------------------

With our model having a highly accurate fit to the actual data. We'll continue to develop the sales forecasting model for 1 year into the future of the dataset. The linear regression model shows us that sales are going to follow close to the trends of previous years but will also overall increase.

* R-squared Score: 0.951730
* Mean Absolute Error: 33725.811
* Mean Squared Error: 1367965454.322
* Root Mean Squared Error: 36986.017
* Correlation Coefficient: 0.9959254

![image](https://github.com/javamesql/Sales-Forecasting_LR/assets/141413672/00429783-7c7f-4160-a11a-a2125da1d9b0)


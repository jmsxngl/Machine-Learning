# Saudi Arabia Used Cars - `Price Prediction`

![saudiarabiausedcars](https://user-images.githubusercontent.com/94034809/171673094-f2128be3-e725-4ee6-8bc4-ab036fe55320.jpg)

**Business Understanding**


**Context**

Saudi used cars are data about used cars in Saudi Arabia complete with various kinds of information such as brands, models, year of manufacture, vehicle origin, distance traveled and of course price. several variants of the car exist from 1963 to 2021.

**Problem**

The challenge of this problem is where the price of the car is negotiable, the price is not listed in this data or 0. So it is difficult for us to determine the appropriate price.

**Goals**

Therefore, using the capabilities of the computer, we can predict the price of car "0" according to the features available in this dataset.

**Analytics**

we need to analyze the data to get the pattern according to the existing features by making a regression model in order to predict the price as accurately as possible.

**Metrics**

The metrics that will be used in this process are RMSE / Root Mean Square error, MAE / Mean Absolute Error and MAPE / Mean Absolute Precentage Error. By finding the smallest value in these metrics, the data can be predicted as accurately as possible.


**Data Understanding**

Used Cars Prices in Saudi Arabia and Spec Scraped From Syarah Website

[Saudi Used Cars](https://drive.google.com/file/d/1Tr4YT5dmgwTrXLvIqZ4diBf5z8K6JjrR/view)

Attributes Information

- `Model`           : Name of a car product
- `Region`          : The region in which the used car was offered for sale 
- `Brand`           : Name of the car company
- `Transmission`    : Automatic / Manual 
- `Origin`          : Country of importer (Gulf/Saudi/Other) 
- `Options`         : Full Options/Semi-Full/Standard 
- `Year`            : Year of Manufacturing 
- `Engine`          : The engine size 
- `Mileage`         : The average distance that a vehicle can travel on (in km) 
- `Negotiable`      : If True, the price is 0. This means the price is negotiable (not set) 
- `Price`           : Price of the used car (in SAR) 


**Conclusion**

Based on the results of the modeling process, it can be seen that the `Brand`, `Engine` and `Year` features have a very significant influence on the `Price` feature.
And it can be concluded that this model can predict the price of a used car in a maximum price range of 182500 Riyal with an average estimate of 18388.76 Riyal miss the average price. Due to the high bias, the possibility of missing is also quite high. maybe with some other features that might be very helpful.


**Recommendation**

- By increasing the number of datasets it may help in modeling results, the lack of variation in the data may lead to decreased accuracy in making predictions
- Adding new features such as fit conditions and engine health may have a positive impact on the model
- Maybe every prediction result of this model can be directly confirmed its accuracy against the actual price in order to increase the precision in prediction.

Thank You  - James Nainggolan

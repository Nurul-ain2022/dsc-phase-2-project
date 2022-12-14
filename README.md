# King County  Housing Market Trends

##### Author : Nurulain Abdi

## Overview

The kc_house_data is a dataset containing information about houses sold in the King County area of Washington state. 
The data includes various features of the houses, such as the number of bedrooms and bathrooms, the square footage, and the sale price.


## Business Problem

We want to use the data to build a predictive model that could help real estate agents and developers estimate the sale price of a property based on its characteristics.

This dataset could be useful for a variety of business applications, such as real estate market analysis or pricing prediction for new construction. By exploring the relationships between the different features, it may be possible to identify trends or patterns that can be used to inform business decisions. 


## Data

Data is from kc_house_data.csv


## Methods

Regression modeling is used to analyze house sales in a northwestern county.

I used a regression analysis tool, such as the LinearRegression class in Python's scikit-learn library, to build a model that predicts the sale price of a house based on its features. 
I then used this model to analyze the house sales data and generate insights such as the average sale price, the factors that most influence sale price, and the overall trend of house prices in the area.


## Results

The most correlated feature is footage of the home.
![download (1)](https://user-images.githubusercontent.com/116640061/207713921-7231132b-dad9-4e0e-b549-ffd7f374ae39.png)

Checking for Multicollinearity of Features

![download (3)](https://user-images.githubusercontent.com/116640061/207714170-dc3f77b8-21cc-405a-a248-c916ff7d5aad.png)


I then checked for outliers in the data set 

![download (2)](https://user-images.githubusercontent.com/116640061/207714375-2d2e9a2b-9b60-41eb-be91-cfe3992295c0.png)

Most of the features have a lot of outliers in this data set



## Conclusions

- Based on the analysed data and the prediction model built, Our final R-squared:	0.618 indicating that the model is not performing very well, and may be overfitting or underfitting the data.

- The data violates the homoscedasticity assumption, as shown below by the residuals clustering around certain values of the independent variable

![image](https://user-images.githubusercontent.com/116640061/207717232-9901c0d1-870f-4145-abd0-6796f0a5ba8c.png)

## Recommendation

- I would not recommend using an algorithm to review and adjust prices of housing because there are alot of factors to be considered such as preference and affordability which varies from person to person.


## Next Steps

- It is possible that the model could be improved by tuning its parameters or using a different model altogether. It is also possible that the data itself is not well-suited to the task at hand, and that no model will be able to achieve good performance on it!


## For more information

See the full analysis in the [Jupyter Notebook](https://github.com/Nurul-ain2022/dsc-phase-2-project/blob/main/student.ipynb) or review this [presentation](https://github.com/Nurul-ain2022/dsc-phase-2-project/blob/main/Presentation.pdf). 

[Click here for the descrition of the column names](https://github.com/Nurul-ain2022/dsc-phase-2-project/blob/main/data/column_names.md)

For additional info, contact Nurulain Abdi at Nurulain.maalim@student.moringaschool.com



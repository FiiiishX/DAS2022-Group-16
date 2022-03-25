# Properties which Influence Wine Score
## Background
Based on a dataset from WineEnthusiast, we will analyze various attributes (origin, price, rating, etc.) of a bottle of wine appearing in the dataset and try to find out the variables that have an impact on whether a wine's rating is greater than 90. GLM models will be used to compare the influence of each feature on the rating score.
Given a data set from the WineEnthusiast, analyise which properties of wine influence whether the number of points awarded is greater than 90.

## Group information
Group 16
|Work|Member|Timeline|
----|---|-----|
|Build model and write RMD file|Xiaoyu Xu; Mingran Jia; Ciara Richmond|3.14-3.20|
|Write the Slide|Zhaohan Wang;Ciara Richmond|3.20-3.25|
|Presentation|Zhaohan Wang; Mingran Jia|3.25|

## Main structure 

![image](https://user-images.githubusercontent.com/68211426/160034727-cf2e4532-d77d-4617-b3df-290852048026.png)

## Model Building
Our response variable is above 90 points or not, this is the binary response.So, we can build the following model. 
1. Y~area to determine whether and how the area influence the response
2. Y~year to determine whether and how the year of grape harvest influence the response
3. Y~ variety to determine whether and how the type of grape influence the response
4. Y~ winery to determine whether and how the winery influence the response
5. Y~. and use stepwise regression to select the variable
6. the final model is![image](https://user-images.githubusercontent.com/68211426/160033731-f8401f99-ce18-4779-8b44-0ac113a3d088.png)![image](https://user-images.githubusercontent.com/68211426/160034404-518437e6-a928-469e-9ffa-be34736a5a82.png)


## Document description
- Group_16_Analysis.Rmd is our code of the project
- dataset16.csv is the data set of our project

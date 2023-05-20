# Bike-sharing-demand-prediction
<h3>Problem Description</h3>
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis on rent. A rental bike provider wants to come up with a mindful business plan to be able to accelerate its revenue.

The company wants to find out the key driving factors for the demand for shared bikes. These will help them to construct the business strategy to meet the demand levels and meet the customer’s expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
Aim of this project is to build a model that predicts the demand for rental bikes using supervised learning algorithms (regression and classification).

<h3>Algorithms Used:</h3>
    1. Linear regression
    
    2. Lasso regression
    
    3. Ridge regression
    
    4. Elastic net regression
    
    5. Random Forest
    
    6. Gradient Boosting
    

<h3>Summary:</h3>
    
<h4>EDA insights:</h4>

1. There is very less or no demand of bikes on non-functioning days as compared with functioning days.


2.The demand for rented bikes is highest in the middle of the year or summer season , moderately high in spring and autumn seasons and lowest in winters.

There is no notable difference in total bike demand on weekdays and weekends.


3.Count of bikes is very less for low temperatures and increases as the temperature increases but we see a drop after it touches certain temperature which range between (27 -33)degree celsius.

Demand of bikes increases between 6 to 10 in morning on weekdays ,is constant uptill 3 and again increases from 4 in evening till 7 in evening and decreases constantly afterwards. On weekends bike demand constantly increases from 6 in morning and is at peak in evening.

<h4>Results from ML models:</h4>

1.Random Forest and grid search gradient boosting is the best performing model with an r2 score of 0.99 and 0.93 and r2 score of 0.96 and 0.93 for training and testing set respectively.


2.All other regression models (Linear Regression, Lasso Regression, Ridge Regression, Elastic net Regression)gave almost the same results having r2 score 0.65 and 0.66 for training and testing sets .


3.Random Forest Regression and grid search gradient boosting Models have been explained using LIME.


4.Temperature AND Hour are the most important features that affects the y variable the most followed by Functioning day and Humidity .

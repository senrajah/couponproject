# couponproject
===============
Module 5
========
Project link : https://github.com/senrajah/couponproject/blob/main/Will_Customer_Accept_coupon.ipynb

Problem Statement:
==================

The goal of this project was to predict "Will the customer accept the coupon?" We used our knowledge of visualizations and probability
distributions to distinguish between whether if the customer would aceept the coupon or not.

Data Used:
=========

This data comes to us from the UCI Machine Learning repository and was collected via a survey by the Amazon Mechanical Turk. 


Summary of Observations:
======================== 

The total % amount of the number of people who accepted the coupon is 56.93%.

Bar Coupons:
===========
The total % amount of drivers who acdcepted bar coupons is 41.19%. 

 1.Drivers who have visited the bar more have a higher rate of accepting the bar coupon. 
 2.Drivers older than 25 and went to the bar more than once also have a high chance of accepting a bar coupon.
 3.Drivers with no kids as passenger and not work in "Farming, Fishing & Forestry industry" tend to have a high chance of accepting the 
 coupon.
 4.Drivers with no kids as passenger and are not widowed have a high acceptance rate.
 5. Drivers below 30 and go to the bar have a high acceptance rate. 

Coffee House Coupons:
=====================
The total % amount of drivers who accepted Coffee House coupons are 49.63%.

 1. Drivers that are students or unemployed have a higher acceptance rate than others. 
 2. Gender also does not seem to have much of an impact on the acceptance rate.
 3. The weather also does not seem to make much of a difference, but drivers have a slightly higher chance of accepting in sunny 
 weather rather than in snowy or rainy weather. 

Next Steps and Conclusion:
==========================
We can dig deeper into the data and explore other features and bring in more insights for other coupons like Restaurant, Carry-out etc 
and see whether we can predict the acceptance rate with more accuracy. 
We can do more feature engineering and then feed the features to a logistic regression model and train with the training dataset
and test them using the testing dataset. 
Once the above step is done, we can feed in new dataset to the model and predict the result and evaluate the accuracy of the model. 





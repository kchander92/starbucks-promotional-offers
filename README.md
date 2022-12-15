# Data Science Capstone Project: Starbucks Promotional Offers

## Motivation
Through its mobile app, Starbucks collects data on customers' demographics, spending behavior, and how they respond to promotional offers that give rewards in the form of buy-one-get-one (BOGO) or discounts. The goal of this project is to develop machine learning models that can predict how much users spend on average as well as how they respond to these promotional offers, so that the company can best determine based on spending behavior and demographic information who would be the best target audience for sending those offers as a means of expanding their customer base.

## Libraries
JSON is utilized for reading the data files into tables that will be manipulated using the Pandas v1.3 library. Numpy is required for some list creation and manipulation, and Matplotlib Pyplot and Seaborn are used for data visualization.

## Files Description
- portfolio.json - collection of all promotional offers with their type, reward, duration, and minimum amount needed to spend to complete the offer
- profile.json - list of all Starbucks mobile app users along with their age, income, gender, and when they joined
- transcript.json - full record of all transactions made by users through the app as well as all offers sent to these users and whether they were viewed and completed

## Results Summary
We have developed a linear regression model that can predict how much someone spends on average based on their income and gender, as well as binary classification models using the AdaBoost algorithm that determine based on demographic features and spending behavior whether or not a user who views a BOGO/discount offer completes it. View the full write-up [here](https://medium.com/@krishnan.chander/modeling-spending-behavior-and-interest-in-promotional-offers-from-demographics-of-starbucks-3bb0c40c8a89).

## Acknowledgments
Source on ensemble methods for binary classification:  
Kumar, A. (2022, April 17). *Differences between Random Forest vs AdaBoost*. Data Differences between Random Forest vs AdaBoost. Retrieved December 14, 2022, from https://vitalflux.com/differences-between-random-forest-vs-adaboost/

Thanks to Udacity and Starbucks for providing the simulated datasets.

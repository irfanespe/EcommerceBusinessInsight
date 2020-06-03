# Women Clothing E-Commerce Business Insight
## by Irfan Septiyana Putra

## Project motivation

This project is performed to gain new insight for company development. I focused on these topics below :
1. Finding present customers age range 
2. Inspecting correlation between products rating and boguht frequency
3. Analyze features that give imapct on recommended indicator.

## Medium Link : https://medium.com/@irfanespe/from-e-commerce-data-to-business-insight-5254b73caf06

## Programming Language

This excercise is based on python programming language.

## Used Libraries

- numpy 1.18.1
- matplotlib 3.1.1
- Pandas 0.25.3
- Scikit-Learn 0.22.1
- Seaborn 0.9.0

## Dataset

> This dataset contains data of women E-commerce clothing. This dataset contains 11 parameters that consists of 5 string column and 6 integer column and 23486 data. This dataset can be downloaded via : https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews .  

## Summary of Findings

> There are three main topics that is wanted to explore through this data exploration. The first is age range of present customers. Found that  around 71.89% users in range between 24-60 years old. In the First, I assume that the more often one type of product bought the more high its rating is. After exploring the data, I found that there are no relation between bought frequency and rating. Even those features do not have correlation, rating has strong correlation with recommendation indicator. Correlation value between reccomendation indicator and rating is 0.79. From this condition, I made model to predict recommendation indicator with rating as input. Trained model is valid enough to make prediction due to its F1 score test value (0.93). All information can be good insight for e-commerce stakeholder to develop their business in future.

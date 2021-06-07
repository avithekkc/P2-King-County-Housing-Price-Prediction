# King County House Price Prediction
![Realtor Logo](https://github.com/avithekkc/P2-King-County-Housing-Price-Prediction/blob/main/images/header.jpg?raw=true)
## Overview
Be Realty is a Real Estate company looking to adopt a data-driven approach in choosing the best house and giving the best price estimate to their client based on location and features of the house they are looking for.



## Business Problems
People at Be Realty are really good at getting the best deal possible for their client but they are not good at giving the best estimate on the price as per the client's requirement so they need a predicting model which can help them and their client to have an idea before purchasing a house.

## Data
Data was obtained from [Kaggle ](https://www.kaggle.com/harlfoxem/housesalesprediction)

## Process

 1. Obtaining Data
 2. Data Cleaning
 3. Exploratory Data Analysis
 4. Modeling
 5. Interpretion

## FINDINGS
### Which Zipcodes (Location) has the Highest Average Home Price ?
Plot below shows that the price around waterfront and house that are near to downtown seattle have High Average Price.
![Lat Long Vs Price](https://github.com/avithekkc/P2-King-County-Housing-Price-Prediction/blob/main/images/lat_long_price.jpg?raw=true)
![Zipcode vs location](https://github.com/avithekkc/P2-King-County-Housing-Price-Prediction/blob/main/images/zip_location.jpg?raw=true)
Plot Below shows that the top 20 zipcodes with high average price are the same location where the price was seen high in the above image.
![Zipcode vs Price](https://github.com/avithekkc/P2-King-County-Housing-Price-Prediction/blob/main/images/zip_price.jpg?raw=true)
### Does having good Grade Impact Average Price ?
As the Grade increase price increase as well. Price starts to move significantly if the grade of the house in from 7 to 11.
![Grade Vs Price](https://github.com/avithekkc/P2-King-County-Housing-Price-Prediction/blob/main/images/grade_price.jpg?raw=true)
### Does Condition of house Impact Average Price ?
Price does seems to depend on how the condition of the house is, below plot shows that the Avearge price of the house is high when the condition of the house is very good.
![Condition Vs Price](https://github.com/avithekkc/P2-King-County-Housing-Price-Prediction/blob/main/images/condition_price.jpg?raw=true)

##  Conclusions
All the above plot shows that Location, Grade and Condition impact the most on the price. This makes sense as a house with good condition and having good grade ( Grading is based on the quality of workmanship and builds ) and A good location will always have High price.

## Next Steps
In order to improve the model to give much better results on house price prediction the following next steps should be considered -

 - Obtaining Grades of Cost of Living, Crime Rates and Jobs from  [Niche.com](https://www.niche.com/) so see how these factors affect the price.
 - Adding distance of nearby school from the home.
 - Exploring more on square footage data.



##   Repository Structure
```
├── data                                <- data used for the analysis.
├── images                              <- All images used throughout the project.
├── data-cleaning.ipynb                 <- Cleaning of data to create final dataset.
├── baseline-model.ipynb                <- Initial fit of the model.
├── eda.ipynb                           <- EDA and Modeling.
├── presentation.pdf                    <- PDF version of project presentation.
└── readme.md                           <- README file for Quick overview on project.
```

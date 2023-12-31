# Arabic Peninsula Car Analysis
This is the repo for the statistical learning individual project. The aim is to understand which are the variables that most influence car prices in the Arabic peninsula's countries and if we can make some interesting inference 📈

The analysis is divided in two main parts: 
- In the first, I subsetted the dataset into six, creating one dataset for each country. In this way I was able to analyse the prices country-per-country, which would have allowed me to see any difference between countries, namely if in certain nations there are variables that have a greater weight in the determination of the price. For instance this analysis may generate results like: "Saudis value more speed than Omani", thus fast cars will be sold at a higher price in Saudi Arabia compared with the one of Oman.
- In the second, I analysed the original dataset to see whether the variable country was - or not - a crucial factor in the determination of the price. This analysis can generate results like: "given a specific car, its price in Qatar is higher than in Bahrain just because it is sold in Qatar".

To conduct the afore mentioned analyses, I implemented robust regression, regression trees and random forest on both the original dataset and on the dimensionality reduced one obtained by applying the Principal Component Analysis (PCA).

Feel free to look at the R code and to give me any feedback. It is also available an html version of the code with all the results attached together with some comments. It is also available a report in which I deeply explain what I did and interpret the result 💻

The data is taken from the Kaggle dataset "Cars in the middle east": https://www.kaggle.com/datasets/bushnag/cars-in-the-middle-east.

Enjoy!

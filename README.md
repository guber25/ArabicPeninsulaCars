# Car Prices in the Arabic Peninsula
This is the repo for the statistical learning individual project. This research aims to understand which are the variables that most influence car prices in the Arabic peninsula and if we can obtain some interesting insights 📈

The study is divided in two main parts: 
- In the first one, I subsetted the dataset into six, creating one dataset for each country - namely Bahrain, Kuwait, Qatar, Oman, Saudi Arabia and United Arab Emirates. In this way I was able to analyse the prices country-per-country, which allowed me to see differences between countries. In other words, we can see if in certain nations there are variables that have a greater weight in the determination of the price. For instance we may notice that, say, the variable "speed" \[of the car\] is more important to Saudis rather than to Omani. This makes us conclude that fast cars in Saudi Arabia will cost more than in Oman. 
- In the second one, I analysed the original dataset to see whether the variable country was -- or not -- a crucial one in the determination of the price. This analysis can generate results like: "given a specific car, its price in Qatar is higher than in Bahrain just because that car is sold in Qatar".

To conduct the afore mentioned analyses, I implemented robust regressions, regression trees and random forests on both the original dataset and on the dimensionality reduced one obtained by applying the Principal Component Analysis (PCA).

Feel free to look at the R code and to give me any feedback. It is also available an html version of the code with all the results attached together with some comments. Moreover, there is the official report that I presented to my Professor in which I deeply explained what I did and interpreted the results 💻

The data is taken from the Kaggle dataset "Cars in the middle east": https://www.kaggle.com/datasets/bushnag/cars-in-the-middle-east.

Enjoy!

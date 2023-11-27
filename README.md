# shopping-behavior

This project aims to understand the shopping behaviour of American consumers for the company FlashFash. We are interested in discovering the "seasonality" of shoppers, which demographics buy the most, and which market outreach strategies we can apply to maximize purchases.

Technologies:
    Python
    Jupyter
    Matplotlib
    Seaborn
    Numpy
    Scipy

1. Source, Load and Explore

First step on this analysis was to source and load the data. The curent data is a sample dataset of American consumers. Next step was to explore the data by visualizing columns and its values through histograms, bar graphs, boxplots and grided diagrams.

2. Clean and Transform 

The second step was to clean and transform the data. The "Frequency of Purchases" had 65% of the data missing which led us to drop this column from the analysis. The Review Rating was also transformed to indicate clients that left a review of not. The Costumer ID column was excluded from the analysis as it was not relevant for our study. We also dropped rows that had missing values. 

3. Analysis

Finally we began our analysis by creating pivot tables that detected the most popular colors and most popular items purchased for each season. We created two variables with two data frames that enabled us to discover the mean value of purchases for promo code users and non promo code users. Through those two variables we calculated a t-test and tested the relation of promo code using and the amount of dollars in purchases. Finally we devided the Review Rating column into Low and High ratings and visualised the difference between the number of lower scored reviews and highly scored reviews. 

4.Conclusions

After all steps were taken we discovered that the American consumer highly prefers utilizing credit cards and tends to be younger around the age of 30. California demonstrated to be the US state that contains the biggest amount of shoppers while Hawaii was the state with the least amount. American consumers highly prefer to buy through standard shipping. 

Through all the four seasons Winter is the season that Americans consume the most. The most popular colors in Winter are Black, Burnt orange and Aubergine. For Fall it is Brown, Burnt Orange and Terra Cota. While for Spring it is Baby Blue, White and Lavender. For Summer it is Lavender, Lemon Yellow and Baby Blue. 

The most popular clothing in Winter is leggings. For Fall it is backpacks. For Summer it is shorts. For Spring it is running shoes.

There are slightly more Male consumers than Female consumers.

We also observed that promo code users tend to purchase bigger amounts in USD. 


## Observations 

The typical amount of purchase done by the American consumer varies around 30 dollars and 50 dollars in a bivariate graphic visualization. Our current theory is that this variation appears due to promo code using. The use of t-test indicated that there is a high chance of purchase amount variating with promo code using. 

We also observed that consumers tend to leave more negative reviews and we would like to further investigate if negative reviewers tend to be more willing to sit down and write to advert other costumers against certain products; if satisfied costumers solely are less willing to write reviews or if the quality of the products that American consumers buy are of lower quality. 

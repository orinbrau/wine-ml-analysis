# Wine Origin Prediction Modeling
Predicting country of origin for wines using only the descriptive language in wine reviews using R

**Kaggle data set:**
https://www.kaggle.com/datasets/zynicide/wine-reviews

**Methods:**
 - Tokenizing review text & filtering out stop words and any other words that don't directly pertain to tasting notes
 - Determine which countries have enough data to make predictions, randomly sample an equal subset of each to prevent overfitting
 - Developing a random forest ML model with common 'descriptor' words as variables
 - Visualizing results using ggplot, including confusion matrix and descriptor word choropleth maps

**Results:**
 - Achieved **50.4% accuracy!**
 - Much higher than 10% floor of random classification, indicating significant regional difference in taste descriptors
 - Visualizations confirm this with high variance in regional frequency when looking at specific descriptor words

**Future Work:**
 - Examine what makes certain countries' wines more difficult/easy to classify
 - Analyze which descriptors are most influential in making classifications
 - Incorporate other variables into the model for potentially increased accuracy, such as price, review score, year, etc.
 - Look at regional differences within countries, especially those with high sample sizes, such as French regions or U.S. states

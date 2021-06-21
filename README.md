# Sentiment Analysis of Tweets

For this project I got access to the tweets related to the 2019 Canadian Election, the dataset for tweets was rather small so the main job was to use a generic tweets sentiment dataset `sentimenti.csv` and then train on this generic-tweet dataset and see how well it performs on the election related tweets. 


## Encoding
This is my first NLP project which is why I have not used tokenizer (used for tranformers) and more involved approaches like using trained word embeddings. For this project I have used `work-freuqncy` and `Tf-idf`, to encode tweets into numbers. 


## Modelling
For modelling a grid search is performed on the common machine-learning models like,
- kNN 
- Naive Bayes
- Logistic Regression 
- Random Forest
- Decision Tree

For each algorithm a **5-fold** cross validation is performed to tune the *hyperparameters*. More approaches like **light-GBM** and **XG-Boost** will be added later.


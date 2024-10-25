# Airbnb-superhost-analysis

This project classifies Airbnb hosts as Superhosts or non-Superhosts using the [Inside Airbnb USA dataset]([url](https://www.kaggle.com/datasets/konradb/inside-airbnb-usa)) from Kaggle. At the time of this analysis, limited research had been conducted on the determinants of Superhost status, providing an opportunity to delve deeper into this area.

Project Overview:
The analysis involved extensive data cleaning, including stopword removal, text lemmatization, and imputation using Lasso Regression. Text columns were vectorized into bag-of-words and TFIDF formats to enhance model input. After data preparation, we undertook feature engineering by generating new attributes and applying dimensionality reduction techniques.

A range of classification models was applied, with Random Forest ultimately outperforming other methods in predictive accuracy. While Airbnb had previously identified four factors influencing Superhost status, our analysis highlights additional influential features, providing valuable insights into the characteristics that contribute to achieving Superhost designation.

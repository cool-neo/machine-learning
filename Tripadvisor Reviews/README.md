# Tripadvisor Reviews: 


## Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [Matplotlib](http://matplotlib.org/)
- [Scikit-learn](http://scikit-learn.org/stable/)
- [Seaborn](https://seaborn.pydata.org/)
- [Xgboost](https://xgboost.readthedocs.io/en/stable/)


## Summary
- Link to kaggle notebook:  https://www.kaggle.com/ruchibhadauria/hotel-reviews-from-tripadvisor
- Cleaned the using pandas python library.
- Use natural language processing techniques to preprocess the data.
- Used seaborn for data visualizations.
- Applied TfIdf vectorizer to make input and output features.
- Trained a xgboost model on training dataset. 


## Data Collection
- **Scraped** data using selenium from Tripadvisor.com
- Link to dataset on kaggle: https://www.kaggle.com/ruchibhadauria/hotel-reviews-from-tripadvisor


## Result
- Xgboost gave the best F1-score of 0.59 for negative reviews.

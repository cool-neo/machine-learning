# Drug Prescription Using Reviews

## Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [Matplotlib](http://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [NLTK](https://www.nltk.org/)
- [IPyWidgets](https://ipywidgets.readthedocs.io/en/latest)


## Summary
- Got the dataset from UCI Machine Learning Repository
- Did data exploration 
- Cleaned the reviews of any punctuations, numbers, stopwords, etc
- Calculating the Sentiments from cleaned reviews
- Calculated the effectiveness using the ratings column 
- Calculated usefulness of drugs 


## Data 
- Link to the dataset: https://archive.ics.uci.edu/ml/datasets/Drug+Review+Dataset+%28Drugs.com%29
- The dataset provides patient reviews on specific drugs along with related conditions and a 10 star patient rating reflecting overall patient satisfaction. 


## Attribute Information:

1. drugName (categorical): name of drug
2. condition (categorical): name of condition
3. review (text): patient review
4. rating (numerical): 10 star patient rating
5. date (date): date of review entry
6. usefulCount (numerical): number of users who found review useful

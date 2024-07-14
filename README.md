# Reddit users classification

The goal of this project is to predict the gender of certain Reddit users using a dataset containing several thousand posts written by 5000 different authors. 

## Machine Learning Models
To achieve this, various classification models were trained on the training set, utilizing both the subreddits and the posts written by the authors. The final prediction was made by performing linear regression on the ensemble set of predictions obtained from the various models.

### Models Used
We employed several machine learning algorithms for classification:
- Naive Bayes
- Support Vector Machine (SVM)
- Logistic Regression
- Random Forest
- Multi-Layer Perceptron (MLP)

The results from these models were then combined using an ensemble model to improve the prediction accuracy.

### Data Download
Download the dataset from the Kaggle competition [here](https://www.kaggle.com/competitions/datamining2023/data). This dataset is part of the Kaggle competition where my team secured the third position.

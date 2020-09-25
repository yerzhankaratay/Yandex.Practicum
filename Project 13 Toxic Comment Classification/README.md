# Yandex.Practicum
Training Projects

## Project 13 (Machine Learning with Texts) - Toxic Comment Classification (NLP Project)


### Description
An online store has enabled its customers to write article descriptions and comment the changes, now there is a number of toxic comments among 160 thousand written ones, and there will be new ones, so I built a machine learning model that predicts toxicity of new comments by learning from the written and marked ones and it should assist the moderators.

### Overview

Being provided 2 column data having almost 160.000 rows with each row having a comment and a marked target variable (toxic: 1, not toxic: 0) I preprocessed the comments to prepare them for modeling by tokenizing and lemmatizing them, considering stop words, or basically put, making them machine-friendly. 

In order to train and test the model, I split the dataframe in train (85% of data), validation and test datasets (each 7.5% of data)

In the course of the project I created and compared several models (Logistic Regression, Decision Tree Classifier, and LightGBM Classifier) that determine their toxicity, and chose LightGBM (which turned out to show the best score) with an F1 metric of 0.779 that surpassed the initially required score of 0.75, however it comes in the middle of the two other models if we compare them by the time it takes to run predictions. I made several suggestions that may have improved the model but may or should also take a lot more time to calculate.

### Applied Tools and Concepts
**Tokenization** (WhiteSpaceTokenizer) chops up sentences into pieces (for example, word combinations and/or single words), called tokens. \
**Lemmatization** (WordNetLemmatizer) produces root forms of words. \
**Stop words** are commonly used words (such as “the”, “a”, “an”, “in”) that a machine should be programmed to ignore cause they don't bring semantic values to the text. \
**RegEx** operations are string-searching algorithms for "find" or "find and replace" operations on strings.

scikit-learn (TF-IDF Vectorizer, GridSearchCV, LogisticRegression, DecisionTreeClassifier), LGBMClassifier, and vstack from scipy to concatenate the TF-IDF features from training and validation sets the right way.

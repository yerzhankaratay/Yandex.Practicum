# Yandex.Practicum
Training Projects

## Project 13 (Machine Learning with Texts) - Toxic Comment Classification (NLP Project)


### Description
An online store has enabled its customers to write article descriptions and comment the changes, now there is a number of toxic comments among 160 thousand written ones, and there will be new ones, so I built a machine learning model that is supposed to predict toxicity of new comments by learning from the marked up ones and it should assist the moderators.

### A Sneak Peek at Data Preprocessing

Being marked target variable (toxic: 1, not toxic: 0), I preprocessed the comments for modeling by tokenizing<sup>1</sup> and lemmatizing<sup>2</sup> them, considering stop words<sup>3</sup>, or basically put, made them machine-friendly. 

### Conclusion

In the course of the project I created and compared several models (Logistic Regression, Decision Tree Classifier, and LightGBM Classifier) that determine their toxicity, and chose LightGBM (which turned out to show the best score) with an F1 score of 0.779 that surpassed the initially required score of 0.75, however it comes in the middle of the two other models if we compare them by the time it takes to train. \
I made several suggestions that may have improved the model but may or should also take a lot more time for calculations.

### Applied Tools and Concepts

**libraries**: 
- scikit-learn (TF-IDF Vectorizer, GridSearchCV, LogisticRegression, DecisionTreeClassifier)
- LightGBM (LGBMClassifier)
- nltk (WhiteSpaceTokenizer, WordNetLemmatizer, stopwords)
- re (RegEx)<sup>4</sup>
- scipy<sup>5</sup>

<sup>1</sup> **Tokenization** chops up sentences into pieces (for example, word combinations and/or single words), called tokens. \
<sup>2</sup> **Lemmatization** produces root forms of words. \
<sup>3</sup> **Stop words** are commonly used words (such as “the”, “a”, “an”, “in”) that a machine should be programmed to ignore cause they don't bring a semantic value to the text. \
<sup>4</sup> **RegEx** operations are string-searching algorithms for "find" or "find and replace" operations on strings. \
<sup>5</sup> **vstack** from *scipy* to concatenate the TF-IDF features from training and validation sets the right way for testing.

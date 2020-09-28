# Yandex.Practicum
Training Projects

## Project 07 (Supervised Learning) - Bank Client Churn


### Description
A considerable number of clients started leaving the bank that provided the data and it's best to retain them because as it turns out it's more cost-efficient than running a new advertising campaign to grow the client base anew. I developed a predictive model to detect them and assist the bank to prevent the churn.

### Conclusion
Having cleaned the data, I proved the class imbalance<sup>1</sup> in the given dataset (10000 rows) and handled it with upsampling and downsampling approaches to improve the overall scores and decrease the randomness of predictions afterward.

### Applied Tools and Concepts
<sup>1</sup> Class imbalance is a common problem in machine learning classification where there are a disproportionate ratio of observations in each class. \

**libraries**: pandas, numpy, sklearn \
**modeling approaches**: sklearn: DecisionTreeClassifier, LogisticRegression, RandomForestClassifier \
**metrics**: Accuracy, F1, ROC-AUC

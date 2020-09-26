# Yandex.Practicum
Training Projects

## Project 07 (Supervised Learning) - Bank Client Churn


### Description
A considerable number of clients started leaving the bank that provided the data and it's best to retain them because as it turns out it's more cost-efficient than running a new advertising campaign to grow the client base anew. I developed a predictive model to detect them and assist the bank to prevent the churn.

### Overview
### Project Structure
#### 1. Overview
- Dataframe size: 10000 rows x 14 columns
- Identifying the odd columns
#### 2. Data Preparation
- One Hot Encoding to avoid dummy variable trap<sup>1</sup>
- Filling missing data
#### 3. Exploring the Task
- Splitting in datasets for Machine Learning<sup>2</sup>
- Identifying the class imbalance<sup>3</sup>
#### 4. Fighting Imbalanced Classes
- Upsampling and Downsampling
- Shuffling<sup>4</sup>
- Hyperparameter Tuning
#### 5. Test

### Applied Tools and Concepts
<sup>1</sup> Dummy Variable Trap is a scenario in which two or more variables are highly correlated; in simple terms one variable can be predicted from the others. (pandas: `get_dummies`) \
<sup>2</sup> Splitting arrays into random train and test subsets. (sklearn: `train_test_split`) \
<sup>3</sup> Class imbalance is a common problem in machine learning classification where there are a disproportionate ratio of observations in each class. \
<sup>4</sup> Shuffling is used to mix data randomly (sklearn: `shuffle`)

**libraries**: pandas, numpy, sklearn \
**modeling approaches**: sklearn: DecisionTreeClassifier, LogisticRegression, RandomForestClassifier \
**metrics**: Accuracy Score, F1 Score, ROC-AUC Score

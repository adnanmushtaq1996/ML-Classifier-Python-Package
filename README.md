# Machine Learning Classification Python Package
                
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />  
<img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />

# Functionality of the Package

1. Performs Classification using the following algorithms with the default parameters:
   - LogisticRegression
   - KNeighborsClassifier
   - DecisionTreeClassifier
   - RandomForestClassifier
   - GradientBoostingClassifier
   - SVC
   - GaussianNB
   - BernoulliNB
   - MultinomialNB

2. Returns a results dataframe that has information of the model name, accuracy and F1-score on the test data.

3. The package takes the following parameters as input:
   - dataset_path: Path to the csv or excel dataset.
   - output_column: Name of the output column which contains the target variable.
   - train_test_ratio: Ratio in which the dataset is to be divided in train and test splits.


# Usage

- Make sure you have Python installed in your system.
- Run Following command in the CMD.
    ```
    pip install classifier_agent
  ```
  
# Example

 ```
from classifier_agent import classifier_agent

dataset_path = "diabetes.csv"
output_column = "Outcome"
train_test_ratio = 0.25

results = classifier_agent(dataset_path, output_column, train_test_ratio)
print(results)
  ```

# Note 
- The package is currently in a very elementary stage and work is in progress.
- The whole project is developed with python version `Python 3.7.7` and pip version `pip 19.2.3`.
- In case of error, feel free to contact me over Linkedin at [Adnan](https://www.linkedin.com/in/adnan-karol-aa1666179/).


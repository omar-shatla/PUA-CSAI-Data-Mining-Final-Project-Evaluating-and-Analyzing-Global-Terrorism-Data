# PUA-CSAI-Data-Mining-Final-Project-Evaluating-and-Analyzing-Global-Terrorism-Data
Analyzing global terrorism data to detect and evaluate terrorist activities. This project helps in flagging and analyzing unstructured data promoting terrorism found on the internet. Stop the spread of terrorism through data mining and human review.

---

## Description

This project focuses on performing classification using a Random Forest algorithm on a dataset related to global terrorism. The goal is to predict the success of terrorist incidents based on the number of wounded and killed individuals. The code implements data cleaning, model training, evaluation, and visualization of results.


## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required dependencies: pandas, scikit-learn, matplotlib, and seaborn.

```bash
pip install pandas scikit-learn matplotlib seaborn
```

Downloading the dataset is necessary and it can be done by downloading it from [Kaggle](https://www.kaggle.com/datasets/START-UMD/gtd).


## Usage

1. Ensure that the dataset file `globalterrorismdb_0718dist.zip` is available in the same directory as the code file.

2. Extract the dataset by running the code. The extracted file should be named `globalterrorismdb_0718dist.csv`.

3. Run the code to perform the following steps:
   - Drop rows with missing values for the features 'nwound', 'nkill', and the target variable 'success'.
   - Split the dataset into training and testing sets.
   - Train a Random Forest classifier with 100 estimators.
   - Make predictions on the test set.
   - Calculate and display the accuracy of the model.
   - Visualize the confusion matrix to evaluate the classification performance.
   - Create a correlation heatmap to explore the relationships between the variables.
   - Plot the feature importances to understand the contribution of each feature to the classification.


## License

This project is not licensed, and all rights are reserved. You are not permitted to use, modify, or distribute the code without explicit permission.


## Contributors

This project was developed by the following students:

- Omar Shatla
- Rewan Noor
- Arwa Mekawy

# Lesson_13
# Primary application file

Produce a jupyter lab file along with an analysis of the jupyter lab file based on credit worthiness of clients based on lending_data.csv.


---

## Technologies

The following Technologies were used to develop this program:

Python 
    Version 3.9.7

Terminal
    Version 2.12.5 (444)

Visual Studio Code
    Version: 1.66.2 (Universal)
    Commit: dfd34e8260c270da74b5c2d86d61aee4b6d56977
    Date: 2022-04-11T07:49:20.994Z
    Electron: 17.2.0
    Chromium: 98.0.4758.109
    Node.js: 16.13.0
    V8: 9.8.177.11-electron.0
    OS: Darwin x64 21.4.0
    
Jupyter Lab 
    Version 3.2.9
    


---

## General information about analysis.

First you need to split the data into training and testing sets.

Then you create a logistic regression model with the original data.

After that you predict the logistic regression medel with resampled training data using over sampling.

Finally you write a credit risk analysis report on your findings.



---

## Information about datasets

Data frame for lending data:

lending_data_df

Data for X and y:

y = lending_data_df["loan_status"]

X = lending_data_df.drop(columns=["loan_status"])

Split the dat using train test spilt function:

X_train, X_test, y_train, y_test = train_test_split(X, y, random_state=1)

Create Logistic Regression mode:

logistic_regression_model

Make predictions:

predictions

Combiner both predictions and targets:

results_df

Create an accuracy score:

balanced_accuracy_score

Create a confusion matrix:

training_matrix

Create a classification report for the model:

training_report

Ininiate the random over sampler model:

random_oversampler




---

## Libraries used in analysis

pandas

numpy

Path

balanced_accuracy_score

confusion_matrix

classification_report_imbalanced

Prophet

filterwarnings (ignore)

train_test_split

LogisticRegression

RandomOverSampler

---

## Contributors


**Chris Miskovich**

Contact Information:

Email: cmiskovich@verizon.net

[LinkedIn](https://www.linkedin.com/in/christopher-miskovich-9a61b0234/) 

---

## License

[MIT](/license.txt)

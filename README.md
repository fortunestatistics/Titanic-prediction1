### Titanic Passenger Survival Prediction
This project aims to build a machine learning model to predict whether a passenger on the Titanic survived or not based on their attributes like gender, age, class, etc.

The dataset contains information about the passengers on the Titanic and whether they survived or not. It has the following attributes for each passenger:

. PassengerId: Passenger's ID

. Survived: Survival (0 = No, 1 = Yes)

.  Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)

. Name: Name

. Sex: Gender

. Age: Age

. SibSp: Number of siblings / spouses aboard
. Parch: Number of parents / children aboard
. Ticket: Ticket number
. Fare: Passenger fare
. Cabin: Cabin
. Embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

The dataset is in CSV format and contains 891 rows and 12 columns.

Next, let's describe the data preprocessing steps, including handling missing values, encoding categorical variables, and feature selection. The data preprocessing steps for this project include:

Handling missing values: The dataset contained missing values in some columns. These missing values were handled by dropping the rows with missing values. This is a simple and effective strategy when the number of rows with missing values is relatively small.

Encoding categorical variables: The 'Sex' column, which is a categorical variable, was converted to numerical values. This was done by mapping 'male' to 0 and 'female' to 1. This is necessary because machine learning algorithms require numerical input.

Feature selection: The features used to train the machine learning model were 'Pclass', 'Sex', 'Age', 'SibSp', 'Parch', and 'Fare'. These features were chosen based on their relevance to the target variable 'Survived'.




This case study is based on the very famous dataset in machine learning. The titanic survival data. The data contains information about 891 passengers. It also indicates whether the passenger survived the titanic crash or not?

<u>The goal is to create a predictive model which can predict the survival of a given person</u>, if they were to board the titanic and the ship sinks.

**The flow of the case study is as below:**

- Reading the data

- Defining the problem statement

- Identifying the target variable

- Looking at the distribution of target variable

- Basic data exploration

- Rejecting useless columns

- Missing values treatment

- Visual exploratory data analysis

- Feature selection based on data distribution

- Outlier treatment

- Visual correlation analysis

- Statistical correlation analysis \(Feature Selection\)

- Converting data to numeric for ML

- Data Pre-processing

- Trying multiple classification algorithms

- Selecting the best model

- Deploying the best model in production

## Reading the Data

The data has one file "TitanicSurvivalData.csv". This file contains 891 passenger details.

### Data Description

The business meaning of each column in the data is as below:

- **PassengerId**: The id for each passenger
- **Survived**: Whether the passenger survived or not? 1=Survived, 0=Died
- **Pclass**: The travel class of the passenger
- **Name**: Name of the passenger
- **Sex**: The genger of the passenger
- **Age**: The Age of the passenger
- **SibSp**: Number of Siblings/Spouses Aboard
- **Parch**: Number of Parents/Children Aboard
- **Ticket**: The ticket number of the passenger
- **Fare**: The amount of fare paid by the passenger
- **Cabin**: The cabin number allotted
- **Embarked**: Port of Embarkation \(C = Cherbourg; Q = Queenstown; S = Southampton\)

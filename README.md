# Logistic regression using XLMiner
## Project description
Create logistic regression model to predict whether the patient has 10-year risk of future coronary heart disease (CHD).

[What is coronary heart disease, symptoms, diagnosis, causes]( https://www.nhlbi.nih.gov/health/coronary-heart-disease) 

## About the dataset

The dataset contains 16 columns and 4238 rows.

**Variables description**

| Field name | Description | Type |
|---------------|-----------|-------|
|Sex | male or female | Nominal |
| Age | Age of the patient | Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous |
| Education | level of education | Ordinal |
| Current Smoker | whether or not the patient is a current smoker | Nominal| 
| Cigs Per Day | the number of cigarettes that the person smoked on average in one day | can be considered continuous as one can have any number of cigarettes, even half a cigarette |
| BP Meds | whether or not the patient was on blood pressure medication | Nominal |
| Prevalent Stroke | whether or not the patient had previously had a stroke | Nominal |
| Prevalent Hyp | whether or not the patient was hypertensive | Nominal |
| Diabetes | whether or not the patient had diabetes | Nominal |
| Tot Chol | total cholesterol level | Continuous |
| Sys BP | systolic blood pressure | Continuous |
| Dia BP | diastolic blood pressure | Continuous |
| BMI | Body Mass Index | Continuous |
| Heart Rate | heart rate  | Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values |
| Glucose | glucose level | Continuous |
| Predict variable | desired target |
| 10 year risk of coronary heart disease CHD | binary: “1”, means “Yes”, “0” means “No”|

## Steps applied
- Exploring and evaluating quality of the data set
- Detecting outliers
- Handling outliers
- Assessment of possible significant class imbalance
- Imputing missing values
- Detecting possible multicollinearity
- Preparing training and testing set for training and testing models
- Selecting statistical tool for running logistic regression
- Predictors selection technique
- Training "Trimmed outliers" set models and testing each model on testing set
- Training "Replaced outliers" set models and testing each model on testing set
- Evaluation of models performance
- Models comparison
- Additional cross testing
- Verifying possible impact of imbalanced data on logistic regression - Training undersampling model
- Identifying potential impact of outliers for regression - training a model with outliers

## How to review the project
The project is presented in the uploaded Excel file. The file contains an overview of the project in the first tab. The project overview includes information about: steps taken, description of each step, solutions applied and summary of results, the name of the tab or tabs with details of each step (tables, calculations, statistics, models etc.). 

Suggested approach to review the project: go to the Project Overview tab, review each step, if necessary go to the tab(s) with details for that step. Note: Due to the large amount of data used in some charts, it may take several seconds for the chart to load after opening the tab. I suggest navigating between tabs using the sheet list (in Excel, right-click the arrows in the lower left corner to open the tab list).

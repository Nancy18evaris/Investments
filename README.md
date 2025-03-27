This project analyzes investment preferences using a supervised machine learning. The dataset, sourced from Kaggle, was collected via Google Forms during the COVID-19 lockdown. It includes demographic details, investment choices, ranking preferences, and decision-making factors to predict whether an individual invests in financial avenues.
From this dataset i understood there are many categorical comumns, and if we assgn the Investment as the target column, the remaining will be the independent column; from this i understood this is a supervised machine learning, classification.
There are 7 Investment choices.
They have ranked the investments according to their preferences or priority from 1 to 7 by which I assumed 1 is their first preference and the last number 7 is their last preference. 

Here are the column names given to give more information about the data:
'GENDER',
'AGE',
Investment Avenues - 'Do you invest in Investment Avenues?', Yes/No,
'What do you think are the best options for investing your money? (Rank in order of preference) [Mutual Funds]',
'What do you think are the best options for investing your money? (Rank in order of preference) [Equity Market]',
'What do you think are the best options for investing your money? (Rank in order of preference) [Debentures]',
'What do you think are the best options for investing your money? (Rank in order of preference) [Government Bonds]',
'What do you think are the best options for investing your money? (Rank in order of preference) [Fixed Deposits]',
'What do you think are the best options for investing your money? (Rank in order of preference) [Public Provident Fund]',
'What do you think are the best options for investing your money? (Rank in order of preference) [Gold]',
'Do you invest in Stock Market'? Yes/No
'What are the factors considered by you while investing in any instrument?', ('Returns', 'Locking period', 'Risk')
'What is your investment objective?', ('Capital Appreciation', 'income', 'Growth')
'What is your purpose behind the investment?', ('Return', 'Savings for future', 'Wealth Creation')
'How long do you prefer to keep your money in any investment instrument?', ('1-3 years', 'More than 5 years', '3 to 5 Years', 'Less than one year')
'How often do you monitor your investment?', ('Monthly', 'weekly', 'Daily')
'How much return do you expect from any investment instrument?', (10%-20%, 20%-30%, 30%-40%) 
'Which investment avenue do you mostly invest in?',( [Mutual Funds]', [Equity Market]', [Debentures]'[Government Bonds]',[Fixed Deposits]',[Public Provident Fund]',[Gold]'),
'What are your savings objectives?', ('Retirement', 'Health Care', 'Education') 
'Reasons for investing in Equity Market', ('Capital Appreciation', 'Liquidity', 'Dividend')
'Reasons for investing in Mutual Funds', ('Better returns', 'Tax benefits', 'Funds Diversification')
'Reasons for investing in Government Bonds', ('Safe investments', 'assured returns' 'Tax incentives')
'Reasons for investing in Fixed Deposits ', ('Risk free', 'Fixed returns', 'High Interest rates')
'Your sources of information for investments is ' ('Newspaper and Magazines', 'Financial Consultants', 'Television', 'Internet')

DATASET DESCRIPTION
Target Variable: "Do you invest in Investment Avenues?" (Yes/No)

KEY FEATURES

Demographics: Age, Gender
Investment Preferences: Ranked choices (Mutual Funds, Equity, Gold, etc.)
Investment Behavior: Frequency of monitoring, expected returns, objectives
Decision Factors: Risk, returns, locking period

MACHINE LEARNING APPROACH

Data Preprocessing: Encoding categorical variables, handling rankings, missing value imputation
EDA: Analyzing investment patterns across demographics, correlation analysis
Modeling: Logistic Regression, Decision Trees, Random Forest, XGBoost
Evaluation Metrics: Accuracy, Precision, Recall, ROC-AUC

KEY INSIGHTS AND APPLICATIONS

Identifying top-ranked investments across different investor segments
Understanding key factors influencing financial decisions
Developing personalized investment recommendations


# My_Project_Website
Femi's Data Science Projects
# [Project 1: Predicting Employee Attrition](https://github.com/fobembe/People-Analytics) 
This project analyzed factors that causes employee attrition with the aim of recommending solutions to corporate organizations in managing their human resource aseets. Three algorithms were considered for this project i.e. Logistic Regression, KNN and Random Foreset Classifier.  Using the GridSearchCV, the RF classifier was selected and used for the modelinig. The top ten most important factors causing employee attrition include;
* monthly income. 
* age.
* total working years. 
* years working with the company. 
* years working with current manager. 
* years in current role, etc.
Hence, to reduce employee attrition, the above-identified factors should be looked into by management of corporate organizations.

[Visualizing the factors](https://github.com/fobembe/My_Project_Website/blob/main/images/employee.png)

# [Project 2: Predicting Customers' Churn in Telecom](https://github.com/fobembe/Telecom_Churn_Prediction)

The aim of any business enterprise is to maximize profits through the provision of quality goods and services. Profit maximization is very essential for a business to fufill its various obligations in the society. For instance, businesses provides employment opportunities to the people, pays taxes to the government which are used to provide amenities, and other responsibilities to the wider society. However, this objective can be threatened if customers keep churning the business. The major objective of this project is to examine a telecommunication's company's data and try to infer why customers churn the business. The dataset is obtained from Kaggle and has so many features of the customers. Churn in this dataset is a dichotomous variable which is denoted as "Yes" or "No".  Using KNN classifier, the model was able to record 74% accuracy in classifying customers that churn.

# [Project 3: Predicting Success of Bank's Term-Deposit Campaign](https://github.com/fobembe/Bank-Telemarketing-Campaign)
This project seeks to understand the most important factors influencing the success of a Telemarketing campaign among its customers. The importance of this project is to guide the bank in targeting customers that are most likely going to subscribe to their term-deposit product. Analyzing the past purchase behaviors of existing customers can go a long way in mapping out existing customers that can be targeted by the marketing department. This way, advertising expenditure is optimized.  Picking Logistic Regression Model out of other 3 algorithms through GridSearchCV, our model was able to identify top factors that influence the success of the campaign.  These factors are:
* Duration of last contact in minutes with customers
* Number of days that passed after the last campaign client was contacted 
* The month of the year client was contacted--May, Nov, Oct and Sept were the top months respectively
* Success of the previous campaign
* Blue collar job

[Visualize the factors](https://github.com/fobembe/My_Project_Website/blob/main/images/Telemarketing.png)

# [Project 4: Predicting Graduation Rates From Amereican Universities](https://github.com/fobembe/College-Performance-Analytics)
This project utilized ExtraTreeRegressor to analyze important factors predicting graduation rate from colleges.  I utilized the LazyPredict package to test all the candidate algorithms which return ExtraTree as the most efficient. Building a pipeline and GridSearchCV to tune the algorithm, the following factors were found to be important in predicting graduation rate.

AGE_ENTRY = Average Age of Entry
DEP_STAT_PCT = Percentage of students who are financially Independent
PCTPELL = Percentage of undergraduate who receive a Pell Grant
DEP_INC_AVG = Average family income of dependent students in real 2015 dollars
PELL_EVER = Share of Students who receive Pell Grants while in School
INC_PCT_LO = Percentage of aided students whose family income is between 0-30,000 dollars
PREDDEG_Bachelors granting = Predominantly bachelors-degree granting institution
UGDS_UNKN = Total Share of undergraduate degre-seeking whose race is unknown
MAIN = Flag for Main campus
Control_private for-profit = Private for-Profit Institution

[Predicting Factors](https://github.com/fobembe/My_Project_Website/blob/main/images/graduation.png)

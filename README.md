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

[Employee attrition dashboard](https://github.com/fobembe/My_Project_Website/blob/main/images/attrition.png)

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

* AGE_ENTRY = Average Age of Entry
* DEP_STAT_PCT = Percentage of students who are financially Independent
* PCTPELL = Percentage of undergraduate who receive a Pell Grant
* DEP_INC_AVG = Average family income of dependent students in real 2015 dollars
* PELL_EVER = Share of Students who receive Pell Grants while in School
* INC_PCT_LO = Percentage of aided students whose family income is between 0-30,000 dollars
* PREDDEG_Bachelors granting = Predominantly bachelors-degree granting institution
* UGDS_UNKN = Total Share of undergraduate degre-seeking whose race is unknown
* MAIN = Flag for Main campus
* Control_private for-profit = Private for-Profit Institution

[Predictive Factors](https://github.com/fobembe/My_Project_Website/blob/main/images/graduation.png)


# [Project 5: Predicting determinants of crimes in US Communities](https://github.com/fobembe/Community_Crime_Analytics)
This project uses the communities' dataset from UCI learning repository to explain factors responsible for crimes in many US communities. The data contains 2215 instances with 147 records. We selected 20 variables after dropping correlated ones. For instance, reporting number of people under poverty and percentage of people living under poverty essentially are quantifying thesame thing, in such situations, we stick to only 1 of the variables, preferably percentage measures.  The following factors were predicted as causing crimes.

* Total Percentage of People divorced 
* Proportion of the population living below poverty line. 
* The proportion of kids born to never married parents.
* Population density.
* Percent of persons in dense housing (more than 1 person per room).
* proprotion of people between age 12 and 29 living in the neighborhood respectively.

[Crime Predictive Factors](https://github.com/fobembe/My_Project_Website/blob/main/images/crimes.png)

# [Project 6: Forecating Gross National Income](https://github.com/fobembe/Time-Series-Analysis)
This project demonstrated the importance of including exogenous variable(s) in a time series forecast.  Two forecast were made, the first one used the Autoregressive model without exogenous variables while the second model incorporated an exogenous variable--consumption.  The second model performed relatively much better than the first one.

[First Model Result](https://github.com/fobembe/My_Project_Website/blob/main/images/sarima.png)

[Second Model](https://github.com/fobembe/My_Project_Website/blob/main/images/sarimax.png)

[Diagnostics](https://github.com/fobembe/My_Project_Website/blob/main/images/diagnostics.png)


# [Project 7: Clustering](https://github.com/fobembe/Clustering)
This project utilizes kmeans clustering and silhoette scores to determine the number of clusters in a given dataset.  The result shows that there are 2 clusters that have no clear distinction between them according to the siloette score.

[clusters](https://github.com/fobembe/My_Project_Website/blob/main/images/clustering.png)

# [Project 8: Claims Analysis Dashboard](https://github.com/fobembe/Healthcare-claims-visual-analytics)
This project presents a visual analytics of claims using a synthetic data obtained from the CMS website.  The visual analytics is provided as follows:

[Claims dashboard](https://github.com/fobembe/My_Project_Website/blob/main/images/claims.png)

# [Project 9: Enrollment Dashboard in the State of New York](https://github.com/fobembe/Students-Enrollments-in-New-York-State)
This project presents a visual analytics of enrollment in the state of New York for students in elementary to high school.

[NY State School Enrollment](https://github.com/fobembe/My_Project_Website/blob/main/images/Enrollment.png)


# [Project 10:  Enrollment in University of Carlifornia](https://github.com/fobembe/College-Performance-Analytics)
This project provides a visual analytics of the trends and composition of enrollments in University of Carlifornia.  The visuals is presented in the link below.

[Enrollment in University of Carlifornia](https://github.com/fobembe/My_Project_Website/blob/main/images/Carlifornia.png)

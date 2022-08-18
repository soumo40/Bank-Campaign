# Bank Telemarketing Campaign </br>

This code contains all the code as a part of Winter in Data Science. The data has been obtained from https://www.kaggle.com/yufengsui/portuguese-bank-marketing-data-set. </br> </br>

The details of the input variables are as follows: </br>

1. **age (Age):** Indicates th age of the person </br>
2. **job (Job):** Indicates the profession of the person </br>
3. **marital (Marital Status):** Indicates if the person is married. </br>
4. **education (Educational Level):** Indicates the educational qualification of the person </br>
5. **default (Default status):** Indicates if the person has credit in default. </br>
6. **balance (Balance):** Indicates the bank balance </br>
7. **housing (Housing Loan Status):** Indicates if the person has a housing loan </br>
8. **loan (Personal Loan Status):** Indicates if the person has a personal loan </br>
9. **contact (Mode of contact):** Indicates the mode of contact </br>
10. **day (Last contact day):** Indicates the last contact day of the week </br>
11. **month (Last contact month):** Indicates the last contact month of the year </br>
12. **duration (Last contact duration):** Indicates the duration of the last contact in seconds </br>
13. **campaign (Number of contacts):** Indicates the number of contacts performed during this campaign and for this client </br>
14. **pdays** (Number of days that passed by after the client was last contacted from a previous campaign) </br>
15. **previous** (Number of contacts performed before this campaign and for this client) </br>
16. **poutcome** (Outcome of the previous marketing campaign) </br>

The target variable is y. </br>

The project has been divided into the following sections: 1. Preprocessing the data   2. Exploratory Data Analysis  3. Data Visualization  4. Machine Learning  5. Boosting Models  6. Conclusion and Recommendations </br> </br>

Accuarcy obtained from using different machine learning models include: </br>
1. **Logistic Regression:** 88.7% </br>
2. **KNN** : 87.63% </br>
3. **Decision Tree** : 83.34% </br> </br>

Following this, **XGBoost** was used to boost the model performance. Final F1 score obtained from XGBoost was **0.94**.



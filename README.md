# Predict-Term-Deposit-Sale-for-potential-
Identify potential customers who like to subscribe term deposit and thus increase their hit ratio for help the marketing team using the collected from existing customers
Goal
Using the collected from existing customers, build a model that will help the marketing team
identify potential customers who are relatively more likely to subscribe term deposit and thus
increase their hit ratio.
Resources Available
The historical data for this project is available in file
https://archive.ics.uci.edu/ml/datasets/Bank+Marketing

Attribute information
Input variables:
# bank client data:
1 - age (numeric)
2 - job : type of job (categorical: 'admin.','blue
collar','entrepreneur','housemaid','management','retired','selfemployed','services','student','technician','unemployed','unknown')
3 - marital : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced'
means divorced or widowed)
4 - education (categorical:
'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','u
nknown')
5 - default: has credit in default? (categorical: 'no','yes','unknown')
6 - housing: has housing loan? (categorical: 'no','yes','unknown')
7 - loan: has personal loan? (categorical: 'no','yes','unknown')
# related with the last contact of the current campaign:
8 - contact: contact communication type (categorical: 'cellular','telephone')
9 - month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
10 - day_of_week: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')
11 - duration: last contact duration, in seconds (numeric). Important note: this attribute highly
affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known
before a call is performed. Also, after the end of the call y is obviously known. Thus, this
input should only be included for benchmark purposes and should be discarded if the
intention is to have a realistic predictive model.
# other attributes:
12 - campaign: number of contacts performed during this campaign and for this client
(numeric, includes last contact)
13 - pdays: number of days that passed by after the client was last contacted from a previous
campaign (numeric; 999 means client was not previously contacted)
14 - previous: number of contacts performed before this campaign and for this client
(numeric)
15 - poutcome: outcome of the previous marketing campaign (categorical:
'failure','nonexistent','success')
# social and economic context attributes
16 - emp.var.rate: employment variation rate - quarterly indicator (numeric)
17 - cons.price.idx: consumer price index - monthly indicator (numeric)
18 - cons.conf.idx: consumer confidence index - monthly indicator (numeric)
19 - euribor3m: euribor 3 month rate - daily indicator (numeric)
20 - nr.employed: number of employees - quarterly indicator (numeric)
Output variable (desired target):
21 - y - has the client subscribed a term deposit? (binary: 'yes','no')
Project details:
1. Explodatory Ddata Anaysis: Providing inferences usiong Bi-variate and Uni-Variate analysis. 
Studying the data distribution of each variable along with providing required inferences. 
2. Model Building: Using Model hyper parameters very well during Model building on Decision Tree,Random Forest and Gradient Boosting algorithms respectively. 
3. Model Regularization: Using Regularization techniques to check if the overfitting can be minimized.

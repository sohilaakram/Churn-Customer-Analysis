Telecom Users (Kaggle/datasets)

This dataset has 22 columns with 5986 entries.
Most of the features are nominal, except for tenure, Monthly Charges and Total Charges that are numeric values.
Columns:
customerID - customer id
gender - client gender (male / female)
SeniorCitizen - is the client retired (1, 0)
Partner - is the client married (Yes, No)
tenure - how many months a person has been a client of the company
PhoneService - is the telephone service connected (Yes, No)
MultipleLines - are multiple phone lines connected (Yes, No, No phone service)
InternetService - client's Internet service provider (DSL, Fiber optic, No)
OnlineSecurity - is the online security service connected (Yes, No, No internet service)
OnlineBackup - is the online backup service activated (Yes, No, No internet service)
DeviceProtection - does the client have equipment insurance (Yes, No, No internet service)
TechSupport - is the technical support service connected (Yes, No, No internet service)
StreamingTV - is the streaming TV service connected (Yes, No, No internet service)
StreamingMovies - is the streaming cinema service activated (Yes, No, No internet service)
Contract - type of customer contract (Month-to-month, One year, Two year)
PaperlessBilling - whether the client uses paperless billing (Yes, No)
PaymentMethod - payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
MonthlyCharges - current monthly payment
TotalCharges - the total amount that the client paid for the services for the entire time
Churn - whether there was a churn (Yes or No)



Any Company aims to keep existing customers rather than attracting new ones.
 In this project we will analyze and visulaize which customers are more likely churn to help the telecom company keep them.

Churn is the main feature. we will analyze the effect of each other independent feature on churn.
I think Contract, InternetService, TechSupport, TotalCharges, MonthlyCharges and tenure(how many months a person has been a client of the company) will have the most effect.

Insights:
There are about 1300 customer that pays average 20 per month.
Most customers tend to pay less than 90 per month.
Only Few ones pay higher.
The higher total charges,The less customers.
Month-to-month contract customers churn the most, but one/two year contract didn't easily which was excpected.
Alot of customers leave after only one month. (Maybe due to high charges)
I think it is good to convince more customers of long-term contracts.
The company should take care of new customers and provide them with offers to keep them existing and get thier loyality.
Customers left paid higher monthly charges.
Customers with nearly 20 dollar Monthly Charge are more likely to stay.
There should be more care about low-price packages.
Monthly Charges remains the same over months! Customers rarley change their packages.
There was a strong relation between charges and the desicion of a customer to churn. It turns out that less charges gurantee customer satisfication. Also there was an inversely proportional relation between long term contracts and churn rate.
There are strong relationships between different features that together affect the main feature of interest like protection,security and social status.
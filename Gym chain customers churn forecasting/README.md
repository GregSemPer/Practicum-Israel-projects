# Goal

This project depicts the situation, where the gym chain Model Fitness is developing a customer interaction strategy based on analytical data. In order to fight churn, Model Fitness has digitized a number of its customer profiles. The task is to analyze them and come up with a customer retention strategy.

2 machine learning approaches will be used: supervised binary classification (**Logistic regression** and **Random forest** algorythms) and unsupervised clusterization (**K-means** algorythm). 

# Data description

* `Churn` — the fact of churn for the month in question

User data for the preceding month:
* `gender`
* `Near_Location`— whether the user lives or works in the neighborhood where the gym is located
* `Partner`— whether the user is an employee of a partner company (the gym has partner companies whose employees get discounts; in those cases the gym stores information on customers' employers)
* `Promo_friends` — whether the user originally signed up through a "bring a friend" offer (they used a friend's promo code when paying for their first membership)
* `Phone` — whether the user provided their phone number
* `Age`
* `Lifetime` — the time (in months) since the customer first came to the gym

Data from the log of visits and purchases and data on current membership status:
* `Contract_period` — 1 month, 3 months, 6 months, or 1 year
* `Month_to_end_contract` — the months remaining until the contract expires
* `Group_visits`— whether the user takes part in group sessions
* `Avg_class_frequency_total` — average frequency of visits per week over the customer's lifetime
* `Avg_class_frequency_current_month`— average frequency of visits per week over the preceding month
* `Avg_additional_charges_total`— the total amount of money spent on other gym services: cafe, athletic goods, cosmetics and etc.


# Libraries used

pandas, seaborn, numpy, mathplotlib, sklearn

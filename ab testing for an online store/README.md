# Goal
This project recreates analysis for a big online store. First part of the project is hypotheses prioritizing (using ICE and RICE frameworks). The second one is analyzing the results of the conducted experiment with A/B testing approach, finding out if enough data was collected, if B group shows greater conversion and average order size.



# Data description 
### Hypotheses dataset:

`Hypotheses` — brief descriptions of the hypotheses

`Reach` — user reach, on a scale of one to ten

`Impact` — impact on users, on a scale of one to ten

`Confidence` — confidence in the hypothesis, on a scale of one to ten

`Effort` — the resources required to test a hypothesis, on a scale of one to ten. The higher the Effort value, the more resource-intensive the test.

### Orders dataset:

`transactionId` — order identifier

`visitorId` — identifier of the user who placed the order

`date` — of the order

`revenue` — from the order

`group` — the A/B test group that the user belongs to

### Visits dataset:

`date` — date

`group` — A/B test group

`visits` — the number of visits on the date specified in the A/B test group specified


# Libraries used

pandas, seaborn, numpy, matplotlib, scipy

    CASE STUDY:
# DATA EXPLORATORY ANALYSIS AND HYPOTHESIS TESTING FOR INSURANCE CLAIMS DATA

1. Import claims_data.csv and cust_data.csv which is provided to you and combine the two datasets appropriately to create a 360-degree view of the data. Use the same for the subsequent questions.
2. Perform a data audit for the datatypes and find out if there are any mismatch within the current datatypes of the columns and their business significance.
3. Convert the column claim_amount to numeric. Use the appropriate modules/attributes to remove the $ sign.
4. Of all the injury claims, some of them have gone unreported with the police. Create an alert flag (1,0) for all such claims.
5. One customer can claim for insurance more than once and in each claim, multiple categories of claims can be involved. However, customer ID should remain unique.
Retain the most recent observation and delete any duplicated records in the data based on the customer ID column.
6. Check for missing values and impute the missing values with an appropriate value. (mean for continuous and mode for categorical)
7. Calculate the age of customers in years. Based on the age, categorize the customers according to the below criteria
Children Youth Adult Senior
< 18 18-30 30-60 > 60
8. What is the average amount claimed by the customers from various segments?
9. What is the total claim amount based on incident cause for all the claims that have been done at least 20 days prior to 1st of October, 2018.
10. How many adults from TX, DE and AK claimed insurance for driver
related issues and causes?
11. Drawapiechartbetweentheaggregatedvalueofclaimamountbased
on gender and segment. Represent the claim amount as a percentage on the pie chart.
12.Amongmalesandfemales,whichgenderhadclaimedthemostforany type of driver related issues? E.g. This metric can be compared using a bar chart
13.Whichagegrouphadthemaximumfraudulentpolicyclaims?Visualize it on a bar chart.
14. Visualizethemonthlytrendofthetotalamountthathasbeenclaimed by the customers. Ensure that on the “month” axis, the month is in a chronological order not alphabetical order.
15. Whatistheaverageclaimamountforgenderandagecategoriesand suitably represent the above using a facetted bar chart, one facet that represents fraudulent claims and the other for non-fraudulent claims.
16. Based on the conclusions from exploratory analysis as well as suitable statistical tests, answer the below questions. Please include a detailed write-up on the parameters taken into consideration, the Hypothesis testing steps, conclusion from the p-values
17. Is there any difference between age groups and insurance claims?
18. Is there any relationship between total number of policy claims and the claimed amount?
   

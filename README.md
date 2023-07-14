# Bank_Term_Deposit_Analysis


### Situation

- The main objective of this project was to determine the factors that might have led customers to cancel their credit card accounts and to predict if a customer would cancel their accounts in the future.
- In the past couple of years, the bank has experienced a record number of customers who have closed their credit card accounts and this has led to a decline in revenue. The bank's motive is to increase the number of credit lines to increase profitability.

### Task

- My role in the project was to improve the ability to detect the customers who were at risk of having their accounts closed because of which the bank's financial loss would be minimized.
- Moreover, I had to give recommendations to the bank on how to reduce the number of customers closing their credit card accounts.

### Action

- I have performed my analysis with the help of R Programming. I have performed data analysis on the dataset to understand the key relations between the variables. For that, I used libraries like dplyr which is used for data manipulation, and performed various visualizations like bar plots, histograms, and box charts with the help of ggplot library in R.
- I have also performed classification on the data using different machine learning algorithms such as random forest, logistics regression, and KNN model, from that it is found that random forest gives the best performance in predicting this data. Important measures like ROC, F-measure, Recall, and accuracy were used to conclude which is the best classification model. Random forest gives a high F-measure and accuracy of 0.95 and recall of 0.96 which is high than the rest of the models.

### Result

- Key Findings:
    - From the bar plot, it is observed that customers with Part-time employment status have the maximum number of customers closing their credit card accounts. Uncertainty about job/income might be the reason that they can't afford a credit card and thus have closed their account. Full-time employees have the maximum count who has active credit card account, stable job, and income might be the reason for active customer status.
    - Customers with divorced marital status are the least number who have active credit card accounts in comparison to single and married customers. It is also seen that customers with divorced marital status are the least in the number who have closed their credit card accounts. Customers who are single and married are found to be the highest who have active and closed account status. Hence, I found that there is no relation between marital status and customer status.
    - From the observation of the histogram, we find that active customers have a higher utilization percentage than those who have closed their accounts. This could mean that customers who don't pay using a credit card are willing to close their accounts.
    - People having education as associates and masters are the highest who have closed credit card accounts among all others. Similarly, associates and masters are also the highest among all who have the maximum active account status. Hence we can infer that education does not have a significant effect on customer status.
    - According to the Box plot, the median of active customers is slightly higher than the median of customers who have closed their accounts. Thus we can't conclude that customers with high salaries have active credit accounts because the difference is very small.
    
- Recommendations:
    - I would recommend the bank to provide more appealing offers like cashback on online shopping, dining, and grocery stores. By this, people might be tempted to use credit cards more. This would help the bank to retain the customers by not closing their accounts.
    - I would also recommend the bank to provide special schemes for customers with marital status as single and married. Because these are the customers who have the highest active and closed credit accounts. The bank should implement special policies to retain these customers so that it will enhance the bank's profit and customer base.

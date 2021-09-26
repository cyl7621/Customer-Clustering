# Sales Order & End Customers Outlier Detection
This project aims to use past sales transaction data to identify
  -  which sales order is more likely to have an abnormal discount 
  -  which end customer is more likely to receive an abnormal discount (abnormal high discount)

The processdure for this project divides into two parts.
  1. Utilze K-mean clustering algorithm to divide exising customers and sales orders into different groups separately. 
  2. Performed linear regression analysis to generate a upper and lower bound for the predicted discount 
  
Clustering Results:
  - K-mean clustering (end customers)
Variables: average discount for each end customer & total revenue that each end customer have been purchased in the past year
![alt text](https://github.com/cyl7621/Customer-Clustering/blob/main/K-MeanClustering_EndCustomer.PNG)
Based on the analysis, K=5 is the best. End customers get to divided into 5 groups.

- K-mean clustering (sales orders)
Variables: average discount for each sale order, total revenue that each sale order worth
![alt text](https://github.com/cyl7621/Customer-Clustering/blob/main/K-MeanClustering_SalesOrder.PNG)
Based on the analysis, k=5 is the best. Sales order get to divided into 5 groups.


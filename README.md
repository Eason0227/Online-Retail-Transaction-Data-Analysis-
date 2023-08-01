# Online-retail-data-analysis
This project includes transactional data from online retail stores registered in the UK from 2009 to 2011, comprising a total of 525,282 transactions. We utilized this dataset to perform Basket Analysis, wherein we grouped products together to devise marketing strategies. Additionally, we employed the RFM analysis from Customer Relationship Management (CRM) to segment customers into four groups based on their three consumption behaviors. We analyzed these segments and took different actions tailored to their specific characteristics. Finally, the results of the RFM analysis were presented using Power BI. The analytical process is as follows: 

## Basket Analysis:

* Basket Analysis is performed using association rules to identify the relationships between different products. We utilize five indicators to express their associations, including support, confidence, lift, leverage, and conviction.

* Taking an example with a confidence of 0.8, it means that if a customer purchases "PACK OF 6 SKULL PAPER CUPS," there is an 80% probability that they will also buy "PACK OF 6 SKULL PAPER PLATES." Thus, we can combine these two products as a recommendation.

* For each product combination, we can propose discount promotions to increase the chances of customers purchasing these items together.

## RFM Analysis:

* RFM Analysis involves calculating the Recency (R), Frequency (F), and Monetary (M) metrics for each customer.
Recency: How long it has been since the last purchase.
Frequency: How often the customer makes purchases.
Monetary: The total amount spent by the customer.

* We apply the unsupervised learning technique, K-means clustering algorithm, to group customers into four segments based on their three consumption behaviors (Recency, Frequency, Monetary). The determination of the number of clusters is done using the Elbow method and Silhouette score.

* The four customer segments are defined as follows:
  1. Best Customers: Customers with high Recency, Frequency, and Monetary values. They are the most valuable and active customers.
  2. Loyal Customers: Customers with high Frequency and Monetary values but relatively recent purchases. They are loyal and frequent buyers.
  3. Occasional Customers: Customers with low Frequency and Monetary values. They make occasional purchases.
  4. Almost Lost Customers: Customers with low Recency, Frequency, and Monetary values. They have not made a purchase recently and are at risk of being lost.

* To enhance customer engagement, we can launch more promotional activities for Occasional Customers to encourage them to shop more frequently. Loyal Customers can be rewarded with special benefits to maintain their loyalty. While for Almost Lost Customers, targeted offers can be introduced to win them back.

* The results of the RFM analysis are presented through a Power BI dashboard, providing a visual representation of customer segments and actionable insights for marketing strategies.

## Power BI dashboard
![image](https://github.com/Eason0227/Online-retail-data-analysis/assets/102510341/0e9dfdc9-c580-47dc-bd51-443eacbf5683)

# Online Retail - Calcutating CLV and Churn Rate of Customers

In this project, we will calculate CLV ( Customer Lifetime Value) and the Churn Rate of customers. The main concept of the two aspects are discussed below.

### Customer Lifetime Value (CLV): 

The lifetime value of a customer, or customer lifetime value (CLV), represents the total amount of money a customer is expected to spend in thw business, or on the products,
during their lifetime. CLV gives a crucial insight into how much money should be spended on acquiring the customers by telling how much value they’ll bring to the business in the long run.

With CLV we’ll be able to understand which customers we should be focusing on and, more importantly, why we should be focusing on them? Therefore, CLV is a clear look at the
benefit of acquiring and keeping any given customer.

### Calculating CLV:

* **Step One** - Segment customers with RFM (Recency- Frequency - Monetary) model:
       Here **recency** refers to the last time that a customer made a purchase. A customer who has made a purchase recently is more likely to make a repeat purchase than a customer who hasn’t made a purchase in a long time. **Frequency** refers to how many times a customer has made a purchase within a given time frame. A customer who makes purchases often is more likely to continue to come back than a customer who rarely makes purchases. **Monetary** Value is the amount of money a customer has spent within that same time frame. A customer who makes larger purchases is more likely to return than a customer who spends less.
        
By segmenting the customers with RFM, we’ll be able to analyze each group individually and determine which set of customers has the highest CLV.

* **Step Two** - Giving a score for each variable (RFM variables) and create segment based on RFM:
       We ranked the customers in different ranges from 0 to 4 based on their purchase behaiviour. Next we added up the score for each customer and listed a total under RFM Score. Then sorted data by RFM Score and divided the results by highest, middle and lowest score. The highest scoring results will be the most valuable customer segment.
      
* **Step Three** - Calculating the Customer Lifetime Value for each customer segment
       Now that we are all set, we'll calculate the CLV by applying the relevant formulas. We have applied the following formulas.
       
       Average Order Value per customer : Average Order Value = Total Sales / Order Count
       Purchase frequency per customer : Purchase Frequency = Total Orders / Total Customers
       Customer Value per customer: Customer Value = Average Order Value x Purchase Frequency
       CLV per customer: CLV = Customer Value * Average Customer Lifespan
       
## Churn Rate:  

Churn Rate is the percentage of people who abandon your service over time.
Churn Rate = (Number of churns during period) / (Number of customers at beginning of period）

* Average Customer Lifespan = 1/(churn rate)
     
      
      
  

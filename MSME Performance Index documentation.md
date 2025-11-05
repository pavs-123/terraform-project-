# MSME Performance Index

The MSME Performance Index is a pivotal score designed to assess the financial health of our Anchor Traders. It provides valuable insights into the stability and viability of our customers' businesses. By analysing various metrics derived from GST data, the MSME Performance Index helps us evaluate the risk associated with lending to a particular customer and enables us to improve our decision-making processes and enhance customer relationships.

## Simulation and Weightage

Simulations for the MSME Performance Index are being conducted in a Google Sheets document. 
The link to the document: [MSME Performance Index](https://docs.google.com/spreadsheets/d/1FsaB4c9FHcTXKq6XlRf2Fo9YCyTTYGJ9moPWhtKhMvo/edit#gid=469934413)

The decision regarding weights and bands for the metrics are currently in progress and will be updated once finalized.

## Metrics: 

## Average Invoice Value

- Description: Average Invoice Value refers to the average amount of money invoiced by the AT per transaction. It is calculated by dividing the total value of invoices by the number of invoices issued.
- Formula: \[ \text{Average Invoice Value} = \frac{\text{Total Value of Invoices}}{\text{Number of Invoices}} \]
- Insights: A high Average Invoice Value indicates that the borrower is dealing with high-value transactions, which may suggest a healthy business with strong purchasing power or high-value products/services. On the other hand, a low Average Invoice Value may indicate a business that relies on low-value transactions, which could be a risk factor in terms of revenue stability and profitability.
- Questions it can answer: 
  - What is the average value of each transaction for the AT?
  - What is the typical size of a transaction for the AT?

## New Buyers

- Description: New Buyers refers to the number of new customers acquired by the AT within a specific period.
- Formula: Count of distinct TPs over a specific period of time. 
- Insights: An increasing number of New Buyers suggests that the AT is successfully expanding its customer base, which is a positive indicator of business growth. It also indicates that the borrower's products/services are attracting new customers, which can lead to increased revenue and market share.
- Questions it can answer:
  - How many new customers did the borrower acquire in the last quarter?
  - What is the rate of growth in new customers compared to previous periods?

## Buyer Dependence

- Description: Buyer Dependence measures the extent to which the borrower's revenue is dependent on a few key buyers. It is calculated by dividing the revenue from the top buyers by the total revenue.
- Formula: \[ \text{Buyer Dependence} = \frac{\text{Revenue from Top Buyers}}{\text{Total Revenue}} \]
- Insights: A high Buyer Dependence indicates that the borrower's revenue is heavily reliant on a small number of customers. This can be risky, as the loss of a key buyer could significantly impact revenue. Therefore, diversifying the customer base is essential to reduce this risk.
- Questions it can answer:
  - What percentage of the borrower's revenue comes from the top buyers?
  - How many key buyers account for a significant portion of the revenue?

## Transaction Velocity

- Description: Transaction Velocity measures the speed at which transactions are conducted. It is calculated by dividing the total number of transactions by the number of days in the period.
- Formula: \[ \text{Transaction Velocity} = \frac{\text{Total Number of Transactions}}{\text{Time Period}} \]
- Insights: A high Transaction Velocity indicates that the borrower is generating revenue at a fast pace, which may suggest strong demand for their products/services. It also indicates efficient operational processes, which can lead to cost savings and increased profitability.
- Questions it can answer:
  - How many transactions does the AT process per day/month/quarter?
- is there a seasonal pattern in the transaction velocity

## Revenue Growth Rate

- Description: Revenue Growth Rate compares the borrower's current revenue to the revenue from a previous period, typically month-over-month.
- Formula: Formula: ((Current Revenue - Previous Revenue) / Previous Revenue) * 100
- Insights: A high Revenue Growth Rate indicates a growing business, while a negative growth rate may indicate declining business performance.
- Questions it can answer:
  - How fast is the borrower's revenue growing compared to previous periods?
  - How has the customer's revenue grown over the past few quarters?
  - Is there a consistent pattern in the customer's revenue generation?

## Sales vs. Purchase

- Description: Sales vs. Purchase compares the sales made by the borrower to the purchases they have made.
- Formula: \[ \text{Sales vs. Purchase} = \frac{\text{Total Sales}}{\text{Total Purchases}} \]
- Insights: A healthy Sales vs. Purchase ratio indicates that the borrower is generating more revenue than spending on purchases, which is crucial for profitability. A healthy business typically has higher sales than purchases. if purchases are more than sales then there's no profit.
- Questions it can answer:
  - How efficiently is the AT managing their sale and purchases?
  - Are there any trends in customer buying behaviour that affect the Sales vs. Purchase?

## Cash Flow

- Description: Cash Flow measures the amount of cash coming into and going out of the AT’s business.
- Formula: \[ \text{Cash Flow} = \text{Total Cash Inflow} - \text{Total Cash Outflow} \]
- Insights: Positive cash flow indicates that the borrower has enough cash to meet their financial obligations, while negative cash flow may indicate financial distress.
- Questions it can answer:
  - What is the AT's ability to generate cash from its operations?
  - How does the cash flow fluctuate with changes in revenue and expenses?
  - What is the trend in the customer's cash flow over the past few quarters? 
   - Is the customer facing any cash flow constraints?

## Churn Rate

- Description: Churn Rate measures the percentage of customers who stop doing business with the borrower.
- Formula: Churn rate = ((prev month unique customers - current month unique customers)/prev month unique customers)*100

- Insights: A high churn rate may indicate customer dissatisfaction or operational issues, which can impact revenue and profitability.
- Questions it can answer:
  - What is the rate at which customers are leaving the business?
  - What is the overall trend in customer churn rate over the past few quarters?
  - How does the churn rate vary between different customer segments?

```
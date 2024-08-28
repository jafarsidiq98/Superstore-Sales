# **Superstore-Sales**

Superstore sales data provides historical record of transactions in USA, consisting of comprehensive collection of order id, customer names, product names, sales, quantities, discounts, and profits. With this data, I have created a dashboard in order to assist users quickly access their sales summary and gain insights. Here is the look of the dashboard that I developed using Power BI

<img src="https://github.com/jafarsidiq98/Superstore-Sales-Dashboard-Power-BI/blob/b76170041b109e8a28fbf65600bae3fdc2fd7306/Dashboard%20Superstore.jpg">
  
In this dashboard, I included a scorecard to summarize the sales performance during the period. Started with Total Sales to indicate the income earned, AOV to reflect the average amount customers tend to spend, COGS to show direct costs that involved in production, and Total Discount to reflect amount of discount offered, which impacts to the profit. Additionally, Total Profit and Profit Margin highlight profitability of the operation. The goals of these chart is to provide users with immediate insights into our sales performance without needing to analyze detail of data. This also make it easier for users to respond quickly if asked by senior management or their supervisors about total sales

Moving on to the next chart, I generated daily sales chart that shows a total sales and total profit throughout the period. This will help users for illustrating trends, pattern, fluctuactions, and highlights seasonality or any significant event that might have caused spikes or dips in sales and profit. 

Transitioning to the next chart, I build a pie chart to represent the relative contribution of each segment wheteher the sales are generated from Home Office, Corporate, or Regular Consumer, followed by a chart of top 10 customers. With these chart, I hope to help generate spesific programs or campaigns to boost our revenue. 

Additionally, Sales by states was created in order to maximize our potential and brand awaraness, driving more sales and potentially spotting areas for growth or areas that may need more attention. Lastly, I generated sales by subcategory, followed by top 10 products sales in order to identify which categories that perform the best and which products are most purchased. This can inform for customer retention startegies or help focus on particular products.  

# Data Source

The data can be found in the Superstore.csv file, which I obtained from Kaggle. Since the data description is not detailed, I have made several assumptions, such as interpreting the discount as a percentage rather than an amount, given that this column never exceeds one. Additionally, there is no information specifying whether the profit is net or gross, so I have assumed it to be gross profit. Furthermore, I have added new measures in Power BI, including Total Discount in dollars, COGS, AOV, and Profit Margin. Here is the formula:

```math
Total Discount = Sales * Discount
```

```math
COGS = Sales - Total Discount - Profit
```

```math
AOV = Sales / Total Order
```

```math
Profit (\%) = Profit / Sales
```

Here is the Kaggle source: https://www.kaggle.com/datasets/ishanshrivastava28/superstore-sales



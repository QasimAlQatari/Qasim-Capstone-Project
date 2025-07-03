## Unlocking Magna's Potential: E-commerce Data Analysis
## Description
This project analyzes historical e-commerce order data from Magna Middle East to address key challenges: high order cancellation rates, low customer retention, and merchant operational inefficiencies. Our goal is to provide actionable insights to enhance customer experience and optimize operations.



## Dataset

# Source: Historical E-commerce Order Files (50 CSVs) 


Size: 42,864 rows and 41 columns 


Key Data Points Include: Order timelines, customer insights, employee performance, order details, transaction types, record_date, view_date, record_time, view_time, record_hour, ip_address, Customer_Segment, pos_session_id, order_id, total_price, discount, order_status, incomplete_reason, order_type, payment_type, and is_discounted.

## Analysis Highlights

Customer Segmentation: We used Recency, Frequency, and Monetary (RFM) analysis with IP addresses as a customer proxy to identify segments such as Restaurant, Loyal Customer, Needs Attention, New Customer, and Lost/Churned Customer.


Customer Purchase Behavior: A significant portion of customers are "One Time purchase," indicating a challenge in converting initial buyers into repeat customers.


Incomplete Orders: "Pending Restaurant Response" and "Declined by Restaurant" are the dominant reasons for incomplete orders, highlighting operational bottlenecks.

Employee Performance & Responsiveness: There is significant variation in order volume processed by employees, and some are associated with higher declined orders. The average response time is 36.04 minutes, with a median of 1.15 minutes, suggesting outliers causing bottlenecks.



Transaction Patterns: Cash and Debit Card are the most popular payment methods, and discounts are frequently applied.

## Recommendations
Our recommendations focus on:


Customer Retention: Targeted campaigns for "One Time Purchase" customers, loyalty programs for "Needs Attention" customers, and structured incentives for "New Customers".


Operational Improvement: Enhancing real-time communication with restaurants and addressing employee performance gaps related to declined orders.


Marketing Strategy: Analyzing is_discounted data for promotion effectiveness and investigating response time outliers.

## Limitations

IP as Customer Proxy: Using IP addresses as a customer proxy may not always be precise due to shared IPs.


Data Timeframe: The data is limited to one quarter, potentially missing long-term trends or seasonal shifts.


Data Scope: The analysis is limited to the provided order data, excluding external factors.


Missing Context: A deeper understanding of some status codes could enhance the analysis.

## How to Run

Open the notebook:
Qasim Capstone Project.ipynb 

Run the notebook in JupyterLab, VS Code, or Google Colab.

 ## Dependencies
Install the required libraries with:

pandas
numpy
Matplotlib
Seaborn
io
os 
glob

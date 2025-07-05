# E-commerce-Payment-Customer-Analysis-Dashboard-powerbi-
E-commerce Payment & Customer Analysis Dashboard (Power BI)
This repository contains a Power BI dashboard designed to provide key insights into e-commerce payment methods and customer behavior over time, with a focus on geographical distribution.
Introduction
This Power BI dashboard visualizes transactional data to understand payment trends and customer demographics within an e-commerce context. It helps to identify preferred payment methods, track sales growth over time, and analyze purchasing patterns across different customer locations and installment choices.
Data Source
The dataset underpinning this dashboard appears to be transactional and customer-centric, including:
 * Transaction Details: payment_value, payment_type (e.g., credit card, wallet, voucher, debit card), and payment_installments.
 * Customer Demographics: customer_id, customer_zip_code_prefix, customer_city, and customer_state.
The presence of specific Brazilian states (e.g., SP, RJ, MG) suggests the data is likely from an e-commerce platform operating within Brazil.
Dashboard Overview
The dashboard provides an interactive interface to explore payment and customer data, featuring the following key components on the visible page (Page 2 of 3):
 * Payment Value by Type (Bar Chart): Displays the total sum of payment_value and sum of customer_zip_code_prefix (likely intended to show count or distinct count of transactions/customers per zip prefix) broken down by payment_type. This visual clearly highlights the leading payment methods.
 * Payment Value Distribution (Donut Chart): Shows the percentage distribution of sum of payment_value across different payment_type categories, offering a quick overview of payment method popularity.
 * Payment Value Over Time (Line Chart): Illustrates the trend of sum of payment_value year-over-year, from 2020 to 2023, indicating growth or decline in overall sales volume.
 * Customer Location Slicer: Allows users to filter data by customer_state and customer_city, enabling geographical analysis of payment trends.
 * Payment Installments Slicer: Provides a filter for payment_installments (from 1 to 17), useful for analyzing how the number of installments correlates with payment value or type.
 * Page Navigation: Indicates the presence of additional dashboard pages (Page 1, Page 3), suggesting further detailed analysis or different views of the data.
Key Insights
Based on the visuals presented in the dashboard screenshot, several key insights can be drawn:
 * Credit Card Dominance: Credit Card is the overwhelmingly dominant payment method, accounting for over 70% of the total payment value, significantly surpassing 'wallet' and 'voucher' payments. This highlights its critical role in the e-commerce platform's revenue.
 * Consistent Growth in Sales Value: The line chart demonstrates a strong and consistent year-over-year growth in total payment value from 2020 to 2023. This indicates healthy expansion and increasing transaction volumes.
 * Potential for Geographic Analysis: The customer_state and customer_city slicers enable exploration of payment method preferences and sales performance across different regions, allowing for targeted marketing or operational adjustments.
 * Installment Behavior Insights: The payment_installments slicer facilitates analysis into how the number of installments impacts payment value or the choice of payment type, potentially revealing customer purchasing habits for larger transactions.
Getting Started
To view and interact with this Power BI dashboard, you will need:
 * Power BI Desktop: Available for free download from the official Microsoft Power BI website.
Future Enhancements
 * Customer Segmentation: Develop visuals or analysis to segment customers based on their payment behavior or demographics.
 * Product-Level Analysis: Integrate product data to understand which products are purchased using which payment methods.
 * Deep Dive into Installments: Create a dedicated page for a more in-depth analysis of payment installments, including average installment count per transaction value.
 * Comparison to Industry Benchmarks: If available, compare performance metrics against industry averages.
 * Time-based Filtering: Add more granular time filters (e.g., month, quarter) for more detailed trend analysis.

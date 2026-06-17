# d2c_churn_part2_rfm
# RFM Segmentation & Retention Strategy

## Project Objective

The objective of this project is to identify customer segments that require different retention strategies before deploying a machine learning churn prediction model. Customer segmentation is performed using RFM (Recency, Frequency, Monetary) analysis together with additional behavioural and support-related signals.

## Dataset

The analysis uses the customer-level modeling snapshot dataset provided for the assignment. The dataset contains pre-computed RFM metrics along with customer engagement, support, return behaviour, campaign interaction, and discount usage information.

## Methodology

### RFM Features

The following RFM metrics were used:

* Recency (recency_days)
* Frequency (frequency_180d)
* Monetary Value (monetary_180d)

Customers were assigned quintile-based RFM scores:

* R_Score
* F_Score
* M_Score

### Additional Signals

The segmentation incorporates additional behavioural indicators:

* ticket_count_90d
* return_rate_180d
* sessions_30d
* campaign_clicks_30d
* avg_discount_pct_180d

### Customer Segments

The final segmentation includes:

* Champions
* Loyal Customers
* New Customers
* High Value But Unhappy
* Discount Sensitive
* At Risk
* Dormant Customers

## Repository Contents

* rfm_segmentation.ipynb
* segments.csv
* retention_strategy.md
* manual_review_cases.md
* requirements.txt

## Deliverables

The notebook contains:

* RFM feature analysis
* Customer segmentation logic
* Segment interpretation
* Retention recommendations
* Campaign prioritization
* Manual review cases



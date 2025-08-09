# E-Commerce-Sales-analysis-for-Data-Driven-Making--TASK-3
# Customer Segmentation Report Using RFM Analysis

## Overview
This project applies **RFM (Recency, Frequency, Monetary)** analysis to segment customers based on purchasing behavior.  
The segmentation enables businesses to target different customer groups with tailored marketing strategies, improving retention, engagement, and overall profitability.

---

## RFM Analysis Process
- **Recency (R):** Days since the customer's last purchase.
- **Frequency (F):** Total number of transactions made.
- **Monetary (M):** Total amount spent by the customer.

### Steps:
1. Transactional data was cleaned and prepared.
2. RFM scores were assigned for each customer (scale **1 to 5**, higher is better).
3. Customers were classified into predefined segments such as:
   - High-Value
   - Loyal
   - Potential Loyalists
   - At-Risk
   - Lost Customers

---

## Customer Segments & Business Impact

| Segment              | Description                                          | Business Impact                                              |
|----------------------|------------------------------------------------------|--------------------------------------------------------------|
| **High-Value**       | High scores in all RFM metrics                        | Most profitable & loyal; retain at all costs.                |
| **Loyal Customers**  | Frequent buyers, moderate to high spending            | Strong base; good for upselling & loyalty programs.          |
| **Potential Loyalists** | Recent buyers with good frequency & spending       | Can be nurtured into loyal customers.                        |
| **At-Risk Customers** | Previously active but no recent purchases            | Require re-engagement campaigns.                             |
| **Lost Customers**   | Low scores across all RFM metrics                     | Least engaged; low ROI potential.                            |

---

## Key Insights
- **High-Value Customers** make up a small percentage but contribute significantly to revenue.
- **At-Risk** and **Lost Customers** represent a large segment — opportunity for reactivation campaigns.
- **Potential Loyalists** show promising growth potential with targeted offers.
- Frequency strongly influences monetary value — repeat purchases drive revenue.

---

## Marketing Recommendations
- **High-Value:** VIP programs, exclusive deals, early access to new products.
- **Loyal Customers:** Loyalty rewards, satisfaction surveys, and tailored product recommendations.
- **Potential Loyalists:** Personalized welcome emails, discount offers, and review requests.
- **At-Risk Customers:** Win-back emails, special discounts, product reminders.
- **Lost Customers:** Evaluate reactivation ROI before targeting; consider low-touch strategies.

---

## Project Deliverables
- **Customer Segmentation Dataset (CSV)** with:
  - Customer ID
  - RFM Scores
  - Assigned Segment
- **Visualizations**:
  - Bar chart: Customer count per segment
  - Bubble/Scatter plot: R, F, M relationships
  - Heatmap: RFM score densities
  - Pie chart: Segment proportions
- **Final Report** summarizing methodology, insights, and recommendations.

---

## Tools & Technologies
- **Python**: Pandas, NumPy, Matplotlib, Seaborn
- **Data Visualization**: Heatmaps, Bar charts, Scatter plots, Pie charts
- **Data Analysis**: RFM scoring & segmentation rules

---

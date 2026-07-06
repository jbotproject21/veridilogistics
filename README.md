# Veridi Logistics Delivery Performance Audit

## Overview
This project analyzes delivery performance for Veridi Logistics using order, customer, product, and review data. The goal is to identify regions and product categories with high delivery delays and understand how delays impact customer satisfaction.
The analysis focuses on operational efficiency, regional disparities, and customer experience impact.

Project Links

Link to Notebook: https://github.com/jbotproject21/veridilogistics/blob/main/delivery_audit.ipynb

Link to Dashboard: https://app.powerbi.com/links/P7L7JqBsHz?ctid=d8212727-8a62-4c55-9cdb-863a951cc9c3&pbi_source=linkShare

Link to Presentation: 

## Key Insights
* A significant portion of orders are delivered late, with delays varying widely across regions.
* Customer review scores decrease as delivery delays increase, indicating a clear negative relationship between logistics performance and satisfaction.
* Certain states consistently experience higher average delivery delays compared to others.
* Some product categories are more prone to shipping delays due to operational complexity or handling requirements.

## Methodology
### 1. Data Preparation
* Merged Orders, Customers, Products, and Reviews datasets
* Standardized date fields for consistency
* Handled missing values and ensured data integrity

### 2. Feature Engineering
* Delivery delay = Actual delivery date − Estimated delivery date
* Delivery status classification:

  * On-time
  * Late
  * Severely Late

### 3. Analysis
* Regional performance comparison
* Product category delay analysis
* Correlation analysis between delivery delay and review scores
* Ranking of states by logistics efficiency


## Visualizations

The project includes the following insights:

* Distribution of delivery delays
* State-level performance comparison
* Correlation between delay and customer rating
* Product category delay breakdown


## Tools & Technologies

* Python (Pandas, NumPy)
* Matplotlib / Seaborn
* Jupyter Notebook
* Power BI / 

## Conclusion
The analysis shows that delivery delays are not evenly distributed and significantly impact customer satisfaction. The findings suggest that improving regional logistics efficiency and addressing high-delay states could lead to better customer experience and retention.


## Future Improvements
* Add predictive modeling for delivery delay forecasting
* Include route optimization analysis
* Integrate real-time logistics tracking data
* Build automated performance monitoring dashboard



If you want, I can also:

* tailor this to your **exact dataset results (with real numbers filled in)**
* or convert it into a **LinkedIn project post version**
* or help you add **GitHub badges + screenshots for maximum portfolio impact**


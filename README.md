# Customer Shopping Behavior Analysis

## 📊 Project Overview
This project analyzes 3,900 customer transactions using Python, SQL, and Tableau to identify shopping patterns, revenue drivers, and actionable business opportunities.

## 🎯 Objectives
- Uncover spending patterns and customer segments
- Identify product preferences and seasonal trends
- Analyze subscription behavior and payment methods
- Provide data-driven recommendations for revenue optimization

## 📁 Dataset
- **Rows:** 3,900
- **Columns:** 18
- **Key Features:**
  - Customer demographics (Age, Gender, Location, Subscription Status)
  - Purchase details (Item, Category, Amount, Season, Size, Color)
  - Shopping behavior (Discounts, Reviews, Shipping Type, Purchase Frequency)

## 🛠️ Technologies Used
- **Python** - Data cleaning, preprocessing, and feature engineering
- **PostgreSQL** - Structured business queries and analysis
- **Tableau** - Interactive dashboard and visualizations
- **Libraries:** pandas, psycopg2

## 📈 Key Analyses Performed

### Python (Data Preparation)
- Data loading and exploration
- Missing value imputation (Review Rating column)
- Column standardization and feature engineering
- Created `age_group` and `purchase_frequency_days` columns
- Database integration with PostgreSQL

### SQL (Business Queries)
1. Revenue by Gender
2. High-spending discount users
3. Top products by rating
4. Shipping type comparison
5. Subscribers vs. non-subscribers analysis
6. Discount-dependent products
7. Customer segmentation (New, Returning, Loyal)
8. Top products per category
9. Repeat buyers & subscription correlation
10. Revenue by age group

### Tableau (Visualization)
Interactive dashboard featuring:
- Customer demographics and behavior metrics
- Revenue analysis by payment method, age group, and season
- Top 10 items by revenue
- Subscription status breakdown
- Seasonal trends

## 💡 Key Insights
- **Low Average Purchase:** $9.76 per transaction
- **Subscription Gap:** Only 26.88% of customers subscribed
- **Seasonal Peak:** Fall season shows highest revenue
- **Top Performers:** Blouses, Dresses, and Jewelry lead in revenue
- **Review Rating:** 3.75/5 average - room for improvement

## 🎯 Strategic Recommendations
1. Implement bundle deals to increase average order value
2. Create subscription incentives (discounts, free shipping, exclusive access)
3. Target Adult and Senior segments for revenue diversification
4. Optimize inventory and marketing around Fall season peak
5. Address customer feedback to improve review ratings
6. Cross-sell complementary products with top performers

## 📂 Project Structure
```
├── data/
│   └── customer_shopping_data.csv
├── scripts/
│   ├── data_cleaning.py
│   └── sql_queries.sql
├── dashboard/
│   └── customer_behavior_dashboard.twbx
└── README.md
```

## 🚀 How to Run
1. Clone the repository
2. Install required Python libraries: `pip install pandas psycopg2`
3. Run data cleaning script: `python scripts/data_cleaning.py`
4. Execute SQL queries in PostgreSQL
5. Open Tableau dashboard for interactive visualization



## 👤 Author
Devadarsan Nikarthil Aneesh
---
*For questions or collaboration opportunities, feel free to reach out!*

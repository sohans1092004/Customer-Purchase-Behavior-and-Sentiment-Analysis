# Customer Purchase Behavior and Sentiment Analysis  

This repository contains an end-to-end data analytics project that integrates **SQL, Python, and Power BI** to analyze customer purchase behavior and sentiment from product reviews. The project leverages both structured transaction data and unstructured review text to provide actionable business insights.  

---

## Project Overview  

### Objective  
The primary goal of this project is to:  
- Identify patterns in **customer purchase behavior**.  
- Perform **sentiment analysis** on customer reviews.  
- Provide insights to support **marketing, product development, and customer engagement strategies**.  

---

## Datasets  

**Customer Purchase Data**  
- Transaction ID  
- Customer ID  
- Customer Name  
- Product ID  
- Product Name  
- Product Category  
- Purchase Quantity  
- Purchase Price  
- Purchase Date  
- Country  

**Customer Reviews Data**  
- Review ID  
- Customer ID  
- Product ID  
- Review Text  
- Review Date  

---

## Key Components  

### 1. Data Extraction and Transformation (SQL)  
- Designed a normalized MySQL database schema.  
- Imported purchase and review data into the database.  
- Cleaned and transformed data for consistency.  
- Developed SQL queries to generate metrics such as:  
  - Purchases and revenue by customer.  
  - Sales by product and category.  
  - Purchase trends over time.  

### 2. Data Analysis (Python)  
- Connected to the SQL database using `pymysql`.  
- Conducted sentiment analysis using **TextBlob** to classify reviews as Positive, Neutral, or Negative.  
- Performed detailed analysis including:  
  - Purchase and revenue trends (monthly, quarterly, yearly).  
  - Top customers and purchasing patterns.  
  - Product category performance.  
  - Sentiment distribution by product and category.  
- Created visualizations with **matplotlib** and **seaborn**.  

### 3. Data Visualization (Power BI)  
- Built an interactive dashboard to visualize:  
  - Purchase trends.  
  - Top-performing products and categories.  
  - Customer segmentation.  
  - Sentiment insights.  
- Enabled dynamic filtering by date, product category, and customer.  

[View Dashboard Online](https://app.powerbi.com/view?r=eyJrIjoiZmVlNTUwMzItYjYzOC00ZjQ5LTkwZDYtMmZjOTBkZDU0NmY0IiwidCI6IjZjZTcwOTA0LTUwOWMtNGI0Zi1iNjc2LTJiMGRlZjA3M2U2YyJ9)  

---

## Deliverables  

- **SQL Scripts** → `cust_pur_details.sql`  
- **Python Notebook** → `Customer Purchase Behavior and Sentiment Analysis.ipynb`  
- **Power BI Dashboard** → `Ecommerce Analytics Dashboard.pbix`  

---

## Tools and Technologies  

- Database: **MySQL**  
- Programming: **Python**  
- Libraries: `pandas`, `numpy`, `TextBlob`, `matplotlib`, `seaborn`, `pymysql`  
- Visualization: **Power BI**  

---
## Results and Insights  

- **Purchase Trends:** Monthly and yearly trends in customer purchases.  
- **Top Customers:** Identification of high-value customers.  
- **Product Performance:** Best-selling product categories and products.  
- **Sentiment Analysis:** Customer opinions categorized by product and category.  
- **Comprehensive Dashboard:** Unified insights for business decision-making.  


# Customer Purchase Behavior and Sentiment Analysis

This repository hosts a comprehensive end-to-end project that analyzes customer purchase behavior and sentiment using SQL, Python, and Power BI. The project combines structured data on customer transactions and reviews to deliver actionable insights for businesses.

## Project Overview

### Objective
The primary objective of this project is to identify patterns in customer purchase behavior and analyze customer sentiment based on product reviews. These insights will empower businesses to make informed decisions about marketing, product development, and customer engagement strategies.

###

<div align="center">
  <img src="https://github.com/RafiQamar/Customer-Purchase-Behavior-and-Sentiment-Analysis/blob/main/Ecommerce%20Dashboard.gif?raw=true" height="300" alt="IMDB Dashboard gif" />
</div>

###

### Datasets

1. **Customer Purchase Data:**
   - Fields:
     - `Transaction ID`
     - `Customer ID`
     - `Customer Name`
     - `Product ID`
     - `Product Name`
     - `Product Category`
     - `Purchase Quantity`
     - `Purchase Price`
     - `Purchase Date`
     - `Country`

2. **Customer Reviews Data:**
   - Fields:
     - `Review ID`
     - `Customer ID`
     - `Product ID`
     - `Review Text`
     - `Review Date`

## Key Features

This project involves three core components:

### 1. Data Extraction and Transformation (SQL)
- **Database Setup:**
  - Created a MySQL database schema to store and manage the datasets.
  - Established relationships between tables to maintain referential integrity.

- **Data Ingestion:**
  - Imported purchase and review datasets into the database using SQL scripts.

- **Data Cleaning and Normalization:**
  - Addressed missing or inconsistent data.
  - Normalized the database to eliminate redundancy and ensure scalability.

- **Aggregation and Insights:**
  - Designed advanced SQL queries to generate metrics, including:
    - Total purchases and revenue by customer.
    - Total sales and quantities by product.
    - Purchase trends over time.

### 2. Data Analysis (Python)
- **Data Extraction:**
  - Connected to the SQL database using Python’s `pymysql` library to fetch normalized and cleaned data.

- **Sentiment Analysis:**
  - Performed sentiment classification on review text using the `TextBlob` library.
  - Categorized reviews into Positive, Neutral, and Negative sentiments.

- **Advanced Analysis:**
  - Metrics and visualizations generated include:
    - Total purchases, revenue, and average purchase value.
    - Top customers and their purchasing patterns.
    - Purchase trends over time (monthly, quarterly, yearly).
    - Top-performing product categories based on revenue and volume.
    - Sentiment distribution across products and categories.

- **Visualization:**
  - Utilized `matplotlib` and `seaborn` to create detailed plots.
  - Generated insights such as purchase trends and sentiment breakdowns.

### 3. Data Visualization and Reporting (Power BI)
- **Interactive Dashboard:**
  - Built an intuitive and interactive Power BI dashboard showcasing:
    - Purchase trends over different timeframes.
    - Top-performing products and categories.
    - Customer segmentation based on purchasing behavior.
    - Sentiment analysis insights with breakdowns by product and category.

- **Dynamic Reports:**
  - Enabled users to filter the data dynamically by date, product category, or customer segment.

## Project Deliverables

### 1. SQL Scripts
- **File:** `cust_pur_details.sql`
- Contains SQL commands for database creation, data ingestion, and transformations.

### 2. Python Notebook
- **File:** `Customer Purchase Behavior and Sentiment Analysis.ipynb`
- Includes data extraction, cleaning, sentiment analysis, and visualization.

### 3. Power BI Dashboard
- **File:** `Ecommerce Analytics Dashboard.pbix`
- Provides an interactive interface for exploring insights derived from the datasets.

## Tools and Technologies

- **Database:** MySQL
- **Programming Language:** Python
  - Libraries: `pandas`, `numpy`, `TextBlob`, `matplotlib`, `seaborn`, `pymysql`
- **Visualization Tool:** Power BI

## How to Use

### Prerequisites
- MySQL database installed and configured.
- Python environment set up with required libraries.
- Power BI Desktop for visualizations.

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/RafiQamar/Ecommerce-Analytics-Project.git
   ```

2. Set up the MySQL database:
   - Use the `cust_pur_details.sql` script to create and populate the database.

3. Load and analyze the data:
   - Run the Python notebook (`Customer Purchase Behavior and Sentiment Analysis.ipynb`) to extract insights and generate visualizations.

4. Open the Power BI file (`Ecommerce Analytics Dashboard.pbix`) to interact with the visualized insights.
   -Or Through the published PowerBI web link(`https://app.powerbi.com/view?r=eyJrIjoiZmVlNTUwMzItYjYzOC00ZjQ5LTkwZDYtMmZjOTBkZDU0NmY0IiwidCI6IjZjZTcwOTA0LTUwOWMtNGI0Zi1iNjc2LTJiMGRlZjA3M2U2YyJ9`) to interact with the visualized insights without login on the site.

## Results and Insights

- **Purchase Trends:** Monthly and yearly trends in customer purchases.
- **Top Customers:** Insights into high-value customers and their behaviors.
- **Product Performance:** Identification of top-performing product categories.
- **Sentiment Analysis:** Understanding customer sentiment and its impact on product popularity.
- **Comprehensive Dashboard:** A dynamic and interactive dashboard summarizing all key insights.

## Repository Structure

```
├── data/
│   ├── customer_purchase_data.csv          # Raw purchase data
│   ├── customer_reviews_data.csv           # Raw review data
│   ├── updated_reviews_data.csv           # updated review data
├── sql/
│   ├── cust_pur_details.sql                # SQL script for database creation and transformation
├── notebooks/
│   ├── Customer Purchase Behavior and Sentiment Analysis.ipynb  # Python notebook
├── dashboard/
│   ├── Ecommerce Analytics Dashboard.pbix  # Power BI dashboard
│   ├── Ecommerce Analytics Dashboard.pdf  # Power BI dashboard in pdf
├── README.md                               # Project description
```

## Acknowledgments
Special thanks to the creators of `TextBlob`, `pandas`, and other open-source libraries used in this project.

---


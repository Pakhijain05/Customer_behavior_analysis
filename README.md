# Customer_behavior_analysis
End-to-end customer shopping behavior analysis using Python, PostgreSQL, SQL, and Power BI. The project covers data cleaning, exploratory analysis, feature engineering, business analysis, customer segmentation, and interactive dashboard development to uncover insights into sales, revenue, discounts, subscriptions, products, and customer behavior.

# 📊 Customer Shopping Behavior Analysis

## 📌 Overview

This project is an **end-to-end Data Analytics project** focused on analyzing customer shopping behavior and extracting meaningful business insights from customer transaction data.

The project follows a complete analytics workflow, starting with understanding the business problem and dataset, followed by data loading, exploratory data analysis, data cleaning, feature engineering, SQL-based business analysis, and interactive dashboard development in Power BI.

The objective is to understand customer purchasing patterns and provide insights that can help businesses improve **sales, customer engagement, marketing strategies, product performance, and customer loyalty**.

---

## 🎯 Business Problem

A retail company wants to better understand its customers' shopping behavior to improve sales, customer satisfaction, and long-term loyalty.

The analysis focuses on factors such as:

* Customer demographics
* Product categories
* Purchase amount
* Discounts
* Review ratings
* Subscription status
* Shipping methods
* Purchase frequency
* Previous purchases
* Customer loyalty

### Key Business Questions

* How does revenue differ between male and female customers?
* Do customers using discounts still make higher-value purchases?
* Which products have the highest average review ratings?
* Do subscribed customers spend more than non-subscribers?
* Which products rely most heavily on discounts?
* Who are the new, returning, and loyal customers?
* Which products are most frequently purchased within each category?
* Are repeat buyers more likely to subscribe?
* Which age groups generate the most revenue?

---

## 📂 Dataset

The dataset contains customer shopping information where each row represents a customer's latest purchase.

### Important Columns

* Customer ID
* Age
* Gender
* Item Purchased
* Category
* Purchase Amount
* Location
* Size
* Color
* Season
* Review Rating
* Subscription Status
* Shipping Type
* Discount Applied
* Previous Purchases
* Payment Method
* Frequency of Purchases

---

## 🛠️ Tools & Technologies

| Tool           | Purpose                                   |
| -------------- | ----------------------------------------- |
| **Excel**      | Dataset exploration                       |
| **Python**     | Data cleaning and exploratory analysis    |
| **Pandas**     | Data manipulation                         |
| **PostgreSQL** | Database storage and SQL analysis         |
| **SQL**        | Business analysis                         |
| **Power BI**   | Dashboard and visualization               |
| **Gamma**      | Presentation deck                         |
| **GitHub**     | Project documentation and version control |

---

## 🔄 Project Workflow

### 1. Data Loading & Exploration — Python

The dataset was loaded into Python using **Pandas** and explored using functions such as:

* `head()`
* `info()`
* `describe()`
* Missing-value analysis
* Categorical and numerical analysis

### 2. Data Cleaning

The dataset was prepared for analysis by:

* Handling missing review ratings
* Using category-level median values for missing ratings
* Standardizing column names using `snake_case`
* Removing redundant columns
* Checking data consistency

### 3. Feature Engineering

New analytical features were created, including:

* **Age Group** — Young Adult, Adult, Middle-aged, and Senior
* **Purchase Frequency Days** — converted text-based purchase frequency into numerical days

### 4. SQL Business Analysis

The cleaned data was loaded into **PostgreSQL** for deeper analysis.

SQL concepts used include:

* Aggregations
* `GROUP BY`
* `CASE` statements
* Subqueries
* CTEs
* Window functions
* Filtering
* Ranking

These queries were used to answer business questions related to revenue, customer segmentation, discounts, subscriptions, product performance, shipping methods, and customer behavior.

### 5. Power BI Dashboard

The analyzed data was connected to Power BI to create an interactive **Customer Behavior Dashboard**.

### Dashboard Includes

* Total Number of Customers
* Average Review Rating
* Average Purchase Amount
* Customer Subscription Analysis
* Revenue by Category
* Sales by Category
* Revenue by Age Group
* Sales by Age Group
* Interactive filters for:

  * Subscription Status
  * Gender
  * Category
  * Shipping Type

---

## 📊 Dashboard Preview

![Customer Behavior Dashboard](dashboard.png)

The dashboard provides an interactive view of customer behavior and allows users to filter the analysis based on different customer and purchase attributes.

---

## 📈 Key Results & Insights

The analysis revealed several useful business insights:

* **Young adults generate the highest revenue** among the analyzed age groups.
* **Clothing generates the highest revenue and sales** among the major product categories.
* A large proportion of customers are **not subscribed**, creating an opportunity to improve subscription conversion.
* **Express shipping customers show a higher average purchase amount** compared with standard shipping customers.
* Several products have consistently high customer review ratings and may be suitable for stronger marketing promotion.
* The analysis identifies products with a high percentage of purchases made using discounts.
* Customer segmentation highlights the distribution of **new, returning, and loyal customers**.
* Repeat customers represent an important opportunity for subscription growth.

---

## 📑 Project Deliverables

This project includes:

* Python notebook for data loading, cleaning, EDA, and feature engineering
* Cleaned dataset
* SQL queries for business analysis
* PostgreSQL database analysis
* Power BI dashboard
* Project report
* Presentation deck created using Gamma
* GitHub project documentation

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone <your-repository-link>
cd customer-shopping-behavior-analysis
```

### 2. Install Python Dependencies

```bash
pip install pandas sqlalchemy psycopg2
```

### 3. Run the Python Analysis

Open the Jupyter Notebook and run the cells sequentially to:

* Load the dataset
* Explore the data
* Clean missing values
* Perform feature engineering
* Load the cleaned data into PostgreSQL

### 4. Set Up PostgreSQL

Create a PostgreSQL database and configure the connection details in the Python notebook.

Update the required:

* Host
* Port
* Username
* Password
* Database name

### 5. Run SQL Analysis

Open the SQL file in PostgreSQL/pgAdmin and execute the queries to reproduce the business analysis.

### 6. Open the Power BI Dashboard

Open the Power BI `.pbix` file and connect it to the required database if necessary.

---

## 📁 Repository Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Dataset/
│   └── customer_shopping_behavior.csv
│
├── Python/
│   └── customer_behavior_analysis.ipynb
│
├── SQL/
│   └── customer_behavior_analysis.sql
│
├── PowerBI/
│   └── customer_behavior_dashboard.pbix
│
├── Report/
│   └── project_report.pdf
│
├── Presentation/
│   └── project_presentation.pdf
│
├── dashboard.png
│
└── README.md
```

---

## 💡 What I Learned

This project provided practical experience across the complete **Data Analytics lifecycle**.

I strengthened my skills in:

* Data cleaning and preprocessing
* Exploratory Data Analysis
* Feature engineering
* Python and Pandas
* PostgreSQL
* Advanced SQL
* Customer segmentation
* Business problem solving
* Power BI dashboard development
* Data visualization
* Business storytelling
* Project documentation

Most importantly, the project helped me understand that **data analytics is not only about writing queries or creating dashboards. It is about understanding a business problem, asking the right questions, analyzing the available data, and communicating insights that can support better decisions.**

---

## 👤 Author

**Pakhi Jain**

Aspiring Data Analyst | Python | SQL | Power BI | Excel

🔗 LinkedIn: [Add your LinkedIn profile]

🔗 GitHub: [Add your GitHub profile]

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback.

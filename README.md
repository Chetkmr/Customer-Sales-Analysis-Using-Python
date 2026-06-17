# 🛒 Customer Sales Analysis Using Python

## 📌 Project Overview

In the retail industry, understanding customer purchasing behavior is important for improving sales strategies, inventory planning, and customer targeting.

This project analyzes **11,251 customer transaction records** to identify sales trends based on customer demographics, locations, product categories, and purchasing behavior.

Using Python libraries, the raw dataset was cleaned, processed, analyzed, and converted into meaningful business insights.

---

# ❓ Business Problem

The company wants to understand:

- Which customer groups generate the highest revenue?
- Which regions and states contribute most to sales?
- Which product categories perform best?
- How customer demographics affect purchasing behavior?

Without proper analysis, marketing campaigns and inventory planning may not target the right customers, resulting in missed business opportunities.

---

# 📂 Dataset Information

The dataset contains customer purchase details:

| Feature | Description |
|---------|-------------|
| Cust_name | Customer Name |
| Product_ID | Product Identifier |
| Gender | Customer Gender |
| Age Group | Customer Age Category |
| Age | Customer Age |
| Marital_Status | Customer Relationship Status |
| State | Customer Location |
| Zone | Geographic Zone |
| Occupation | Customer Profession |
| Product_Category | Purchased Category |
| Orders | Number of Orders |
| Amount | Purchase Amount |

### Dataset Size

```
Total Records : 11,251
Total Features: 12
```

---

# 🧹 Data Cleaning Process

Before performing analysis, the raw dataset was cleaned to improve accuracy and reliability.

## Issues Found

- Missing values present in Amount column
- Incorrect data types
- Unnecessary columns
- Dataset required validation before analysis


Dataset information:

```python
Rows: 11251

Amount Column:
11239 non-null values

Missing Values:
12 records
```

---

## Solution Applied

Performed data cleaning using Python Pandas:

- Checked missing values
- Removed incomplete records
- Converted columns into correct data types
- Validated dataset before visualization


Example:

```python
data.dropna(inplace=True)

data["Amount"] = data["Amount"].astype(int)

data.info()
```

Clean and structured data was used for Exploratory Data Analysis.

---

# 📊 Exploratory Data Analysis (EDA)


# 1. Sales Analysis by Age Group


## Finding

Customers aged **26-35 years** generated the highest sales revenue.

Top performing age groups:

1. 26-35
2. 36-45
3. 18-25
4. 46-50
5. 51-55


## Business Insight

Young working professionals are the strongest customer segment and contribute maximum revenue.


## Business Impact

Marketing campaigns and product recommendations should focus more on customers between **26-45 years** to increase sales performance.

---

# 2. Customer Analysis by Gender


## Finding

Female customers placed more orders compared to male customers.


Order Distribution:

```
Female Customers : ~7800 orders

Male Customers   : ~3400 orders
```


## Business Insight

Female customers have higher purchasing activity.


## Business Impact

Businesses can create:

- Personalized offers
- Customer loyalty programs
- Targeted marketing campaigns

for high-value customer segments.

---

# 3. Sales Analysis by State


## Finding

Top revenue generating states:

1. Uttar Pradesh
2. Maharashtra
3. Karnataka
4. Delhi
5. Madhya Pradesh


## Business Insight

Few states contribute a major percentage of total business revenue.


## Business Impact

Businesses can increase:

- Inventory availability
- Regional advertisements
- Sales campaigns

in high-performing locations.

---

# 4. Product Category Analysis


## Finding

Highest selling product categories:

1. Clothing & Apparel
2. Food
3. Electronics & Gadgets
4. Footwear & Shoes


## Business Insight

Lifestyle-related products generate higher customer demand.


## Business Impact

Companies can improve:

- Stock management
- Product availability
- Promotional strategies

for best-selling categories.

---

# 5. Sales Analysis by Geographic Zone


## Finding

Highest performing zones:

1. Central Zone
2. Southern Zone
3. Western Zone


## Business Insight

Central Zone customers contribute the highest purchase activity.


## Business Impact

Regional business strategies can be improved by understanding location-based customer behavior.

---

# 📈 Final Business Insights

After analyzing **11K+ customer transactions**, the following insights were discovered:

✔ Customers aged **26-35 years** are the most valuable buyers

✔ Female customers contribute the highest number of orders

✔ Uttar Pradesh, Maharashtra, and Karnataka generate maximum sales

✔ Clothing, Food, and Electronics categories drive business growth

✔ Central Zone shows the strongest customer activity


---

# 🚀 Business Recommendations

Based on the analysis:

1. Increase marketing campaigns targeting customers aged **26-45**

2. Provide personalized offers for high-value customers

3. Maintain higher inventory for top-selling categories

4. Focus advertisements in high revenue states

5. Use customer segmentation for better decision-making


---

# 🛠 Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📚 Skills Applied

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Customer Segmentation
- Business Insights Generation

---

# 🎯 Project Outcome

Successfully transformed raw customer transaction data into actionable business insights.

This analysis helps businesses improve:

✔ Sales Strategy  
✔ Customer Targeting  
✔ Inventory Planning  
✔ Regional Marketing Decisions  


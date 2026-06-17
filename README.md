❓ Business Problem The company wants to understand: Which customer groups generate the highest revenue?

Which regions and states contribute most to sales?

Which product categories perform best?

How customer demographics affect purchasing behavior?

Without proper analysis, marketing campaigns and inventory planning may not target the right customers.
📂 Dataset Information
The dataset contains customer purchase details:
| Feature          | Description                  |
| ---------------- | ---------------------------- |
| Cust_name        | Customer Name                |
| Product_ID       | Product Identifier           |
| Gender           | Customer Gender              |
| Age Group        | Customer Age Category        |
| Age              | Customer Age                 |
| Marital_Status   | Customer Relationship Status |
| State            | Customer Location            |
| Zone             | Geographic Zone              |
| Occupation       | Customer Profession          |
| Product_Category | Purchased Category           |
| Orders           | Number of Orders             |
| Amount           | Purchase Amount              |

Total Records: 11,**251** 🧹 Data Cleaning Process Before analysis, raw data was cleaned to improve quality. Issues Found: Missing values in Amount column

Incorrect data types

Unnecessary columns

Data needed validation before analysis

Dataset summary: Plain text **ANTLR4** Bash C C# **CSS** CoffeeScript CMake Dart Django Docker **EJS** Erlang Git Go GraphQL Groovy **HTML** Java JavaScript **JSON** **JSX** Kotlin LaTeX Less Lua Makefile Markdown **MATLAB** Markup Objective-C Perl **PHP** PowerShell .properties ### Protocol Buffers Python R Ruby Sass (Sass) Sass (Scss) Scheme **SQL** Shell Swift **SVG** **TSX** TypeScript WebAssembly **YAML** **XML**

Rows: 11251Amount column:**11239** non-null valuesMissing values:12 records

Solution: Performed cleaning using Python Pandas: Checked missing values

Removed incomplete records

Converted columns into correct formats

Verified clean dataset before visualization

Example: Plain text **ANTLR4** Bash C C# **CSS** CoffeeScript CMake Dart Django Docker **EJS** Erlang Git Go GraphQL Groovy **HTML** Java JavaScript **JSON** **JSX** Kotlin LaTeX Less Lua Makefile Markdown **MATLAB** Markup Objective-C Perl **PHP** PowerShell .properties ### Protocol Buffers Python R Ruby Sass (Sass) Sass (Scss) Scheme **SQL** Shell Swift **SVG** **TSX** TypeScript WebAssembly **YAML** **XML**

data.dropna(inplace=True)data[*Amount*] = data[*Amount*].astype(int)data.info()

Clean data was used for further analysis. 📊 Exploratory Data Analysis (**EDA**) ## Sales Analysis by Age Group Finding: Customers aged 26-35 years generated the highest sales revenue. Age group ranking: 26-35

36-45

18-25

46-50

51-55

Business Insight: Young working professionals are the strongest customer segment. Impact: Marketing campaigns and product recommendations should focus more on customers between 26-45 years to increase revenue. ## Customer Analysis by Gender Finding: Female customers placed significantly more orders compared to male customers. Approximate distribution: Female customers: ~**7800** orders

Male customers: ~**3400** orders

Business Insight: Female customers show higher purchasing activity. Impact: Businesses can create targeted offers, loyalty programs, and personalized recommendations for this customer segment. ## Sales Analysis by State Finding: Top revenue generating states: ### Uttar Pradesh

Maharashtra

Karnataka

Delhi

### Madhya Pradesh

Business Insight: A few states contribute the majority of revenue. Impact: Businesses can increase inventory availability and marketing investment in high-performing regions. ## Product Category Analysis Finding: Highest selling categories: Clothing & Apparel

Food

Electronics & Gadgets

Footwear & Shoes

Business Insight: Lifestyle-related products have higher demand compared to other categories. Impact: Improve stock planning and promotional strategies around best-selling categories. ## Sales by Geographic Zone Finding: Top performing zones: ### Central Zone

### Southern Zone

### Western Zone

Business Insight: Central region customers contribute the highest purchase volume. Impact: Regional strategies can be improved by focusing on customer demand patterns. 📈 Final Business Insights After analyzing **11K**+ customer transactions: ✔ Customers aged 26-35 are the most valuable buyers

✔ Female customers contribute the highest order volume

✔ Uttar Pradesh, Maharashtra, and Karnataka generate maximum sales

✔ Clothing, Food, and Electronics categories drive business growth

✔ Central Zone has the strongest customer activity 🚀 Business Recommendations Based on analysis: Increase marketing campaigns for age group 26-45 Provide personalized offers for high-value customers Maintain higher inventory for top-selling categories

🛠 Tools & Technologies Used Python

Pandas

NumPy

Matplotlib

Seaborn

### Jupyter Notebook

### Data Cleaning

### Exploratory Data Analysis

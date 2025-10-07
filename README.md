
# Google Data Analytics Case Study (Python + SQL)

An end-to-end data analysis case study inspired by the Google Data Analytics framework — built using **Python**, **Pandas**, and **SQLite**.  
This project explores real-world business data to uncover insights, visualize patterns, and apply statistical reasoning for smarter decision-making.

---

##  Project Overview
The goal of this project is to simulate a **professional data analyst’s workflow**, combining SQL querying power with Python’s analytical ecosystem.

Through this project, I practiced:
- Data extraction using SQL queries
- Data cleaning & transformation with Pandas
- Statistical analysis with SciPy
- Insightful visualizations using Matplotlib & Seaborn
- Business-driven storytelling with data

---

##  Tech Stack

| Category | Tools Used |
|-----------|-------------|
| Language | Python 3 |
| Database | SQLite3 |
| Libraries | Pandas, NumPy, Matplotlib, Seaborn, SciPy |
| IDE | Jupyter Notebook |

---

##  Steps Involved

### **1. Data Collection**
Pulled data from local SQLite database and CSV files.

### **2. Data Cleaning**
Handled missing values, standardized formats, and optimized data types for efficiency.

### **3. SQL Integration**
Executed complex queries directly inside Python using `sqlite3` and `pandas.read_sql_query()`.

### **4. Exploratory Data Analysis (EDA)**
Visualized vendor and purchase data trends to identify correlations, outliers, and key metrics.

### **5. Statistical Testing**
Used `scipy.stats` to compare vendor performance and validate findings with t-tests.

### **6. Insights**
Generated meaningful insights around vendor efficiency, freight cost optimization, and brand-level profitability.

---

##  Key Insights

- **Top Vendors:** Identified vendors contributing most to sales and lowest freight cost.
- **Profit Drivers:** Found the correlation between purchase price and brand volume.
- **Statistical Findings:** Validated whether vendor performance differences were statistically significant.

---

## How to Run Locally

1. **Clone this repository**
   ```bash
   git clone https://github.com/<your-username>/google-data-analytics-case-study.git
2. **Install dependencies**

pip install pandas numpy matplotlib seaborn scipy


3.  **Launch Jupyter Notebook**

jupyter notebook project_google_da.ipynb


4.  **Run all cells**
Execute the notebook sequentially to reproduce results.

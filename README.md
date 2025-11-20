## 🚗 True Value Car Analysis – End-to-End Data Analysis Project

- This project focuses on performing data cleaning, manipulation, exploratory data analysis (EDA), and insights generation on the Maruti True Value Used Cars dataset. The objective is to understand pricing patterns, car conditions, demand trends, and key factors that influence car resale value.

### 🧹 1. Data Cleaning

Performed initial preprocessing to make raw data usable:
- Removed unwanted characters/spaces in Kms Driven & Price.
- Identified missing values using isnull().sum().
- Filled missing categorical values using mode and numerical values using mean.
- Standardized formats and ensured consistency.
- Verified dataset shape and structure after cleaning.

  ### 🛠️ 2. Data Manipulation

Steps performed for deeper analysis and feature enhancement:
- Cleaned symbols and inconsistent formatting.
- Forward-filled missing values in Location.
- Converted EMI values to integer type.
- Treated outliers in EMI using IQR method.

Created new features:
- Car Age (based on manufacturing year)
- Car Condition (based on kilometers driven)
- Dropped irrelevant column: Radius.

  ### 📊 3. Exploratory Data Analysis (EDA)
  🔹 Univariate Analysis
- Wagon R VXI is the most common model in the dataset.
- Petrol is the most used fuel type.
- Most cars are in Fair condition.
- Maximum cars were manufactured in 2022, 2017, 2015, 2018.
- EMI ranges mainly between ₹10,000–₹12,000.
- Most cars fall within the age group of 3, 8, and 10 years.

  🔹 Bivariate Analysis
- Higher KMs Driven → Lower Price trend observed.
- Cars manufactured in 2010 have the lowest resale prices.
- Cars from 2024 have the highest prices.
- Mumbai cars show the best condition overall.

Top low-priced models:
- Ertiga ZXI CNG, Alto K10 VXI+, Eeco CNG 5-STR, Eeco STD 7-STR
- Top high-priced models identified from the dataset.

  🔹 Multivariate Analysis
- Low-priced cars (< ₹2 lakh) with < 40,000 km are mostly Petrol models.
- Alto & Zen Estilo variants show better resale value in this segment.
- Correlation heatmap revealed relationships between Price, Kms Driven, EMI, Age, etc.

  ### 📌 Key Insights

- Petrol cars dominate the used car market.
- Price decreases as kilometers driven increases.
- Cars manufactured in recent years show premium pricing.
- Condition varies by city—Mumbai cars generally found in better condition.
- Under ₹2 lakh budget, petrol cars with low KM offer best value.

  ### 🧠 Skills Demonstrated
- Data Cleaning & Preprocessing
- Feature Engineering
- Handling Outliers
- Exploratory Data Analysis (EDA)
- Matplotlib & Seaborn Visualizations
- Python, Pandas, NumPy
- Business Insight Generation

  ### 🖥️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook
- Excel / CSV Data Sources

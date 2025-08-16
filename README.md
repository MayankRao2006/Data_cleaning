This project demonstrates data cleaning and analysis on a messy sales dataset. It takes raw, unstructured sales records and transforms them into a clean dataset for analysis, providing insights into sales performance, product trends, and revenue generation.
⚙️ Steps in the Project

Data Cleaning

Removed duplicates

Fixed missing values

Standardized product names

Added computed columns like Revenue = Quantity × Price

Exploratory Data Analysis (EDA)

Total sales and revenue by product

Sales trends by day

Identified top-selling and least-selling products

Highest revenue transaction

Key Insights

📈 Shampoo generated the highest revenue.

🧼 Soap had the highest overall quantity sold.

📅 Sales peaked on certain days, showing demand fluctuations.

❓ Some rows had "Unknown" as a product, highlighting data entry issues.

📊 Tools & Libraries Used

Python 🐍

Pandas

Jupyter Notebook

🚀 How to Run

Clone this repository

git clone https://github.com/yourusername/Sales-Data-Analysis.git
cd Sales-Data-Analysis


Install dependencies

pip install -r requirements.txt


Open the notebook

jupyter notebook Cleaned_Data.ipynb

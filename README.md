📊 Developer Survey & Job Market Analysis


📌 Project Overview

This project analyzes developer survey data alongside job market data to uncover trends in:

- compensation
- job satisfaction
- technology preferences
- experience and demographics

The goal is to simulate a real-world data analysis workflow, combining multiple data sources and applying data cleaning, transformation, and visualization techniques.

🎯 Objectives:
- Identify key factors influencing developer compensation
- Explore relationships between experience, age, and job satisfaction
- Analyze popularity of programming languages, databases, and tools
- Compare trends across countries and employment types
  
📂 Data Sources:
- Stack Overflow Developer Survey 2024 (CSV)
- Naukri.com job postings (API, JSON)
- Programming Languages dataset (Web Scraping)
  
⚙️ Data Collection Methods:
- Loading structured data from CSV files
- Collecting job data via API
- Web scraping external datasets
  
🧹 Data Cleaning & Preprocessing:
- Removed missing and non-informative values (e.g., "Prefer not to say")
- Converted categorical variables into numerical formats (e.g., age ranges → numeric values)
- Handled missing values using appropriate techniques (dropping or imputing)
- Normalized selected variables for comparison
- Split multi-response fields into individual rows (e.g., languages, databases)
  
🔍 Exploratory Data Analysis (EDA):
- Distribution analysis (compensation, age, experience)
- Outlier detection using IQR method
- Group-based aggregation (e.g., median salary by age group)
- Trend analysis across different demographics

📊 Data Visualization:
- Bar charts → categorical comparisons (countries, technologies)
- Line charts → trends over age and experience
- Histograms & box plots → distribution and outliers
- Scatter & bubble plots → relationships between variables
  
📈 Key Insights:
- Compensation is strongly right-skewed (few high earners significantly impact averages)
- Experience positively correlates with salary, but not always with job satisfaction
- Technology preferences vary across age groups and regions
- Job satisfaction shows weak correlation with compensation


add more!


🛠️ Tools & Technologies:
- Python (Pandas, NumPy, Matplotlib & Seaborn)
- SQL (PostgreSQL CHECK IT!)
- Jupyter Notebook

📁 Project Structure:

project/
│
├──                
├── 
├── 
├──               
└── README.md

💡 Future Improvements:
- Build Power BI dashboard
- Build predictive model (e.g., salary prediction)

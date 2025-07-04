# Job-Segmentation-Analytics
This project focuses on analyzing Data Analyst job listings using NLP and clustering techniques to identify patterns in required skills, experience levels and job categories. Real-world job descriptions were scraped from Naukri.com, grouped based on similarity and visualized through an interactive Power BI dashboard.

# Overview
- Scraped around 350+ job postings for Data Analyst roles from Naukri.com using Selenium

- Used Natural Language Processing (NLP) to analyze and vectorize job descriptions

- Applied clustering to group roles based on skill sets, tools and requirements
  
- Built a Power BI dashboard to explore:
    1.Role-based job clusters
    2.Most in-demand skill
    3.Experience and location trends

# 🛠Tools & Technologies
 Python (Data & Modeling)
- Selenium : automated scraping of Data Analyst job listings

- Pandas, NumPy : for data wrangling

- Scikit-learn :
  1.TF-IDF to extract keyword importance from descriptions
  2. PCA for dimensionality reduction
  3.KMeans for job segmentation (optimized using the Elbow method)

# NLP
- Vectorized job descriptions using TF-IDF

- Extracted high-frequency terms to identify key tools and responsibilities

# Power BI
Designed a dashboard to explore:

- Clustered job roles

- Top skills & keywords in demand

- Experience level distribution (Entry, Mid, Senior)

- Location-based job posting patterns

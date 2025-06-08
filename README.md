# Exploratory Data Analysis on Top 100 SaaS Companies (2025)

This project presents an exploratory data analysis (EDA) on a curated dataset of the top 100 Software-as-a-Service (SaaS) companies globally as of 2025. The analysis highlights valuation trends, revenue metrics, industry distributions, and other operational indicators that define market-leading SaaS businesses.

The objective is to derive meaningful insights from company-level data, understand growth drivers, and analyze the overall structure of the SaaS ecosystem.

## Project Overview

- Analyzed data of 100 global SaaS companies across various industries.
- Cleaned and processed structured financial and operational attributes.
- Conducted univariate, bivariate, and multivariate analysis using Python.
- Visualized industry trends, funding distributions, revenue patterns, and investor influence.

## Dataset Overview

**Dataset Source:** https://www.kaggle.com/datasets/shreyasdasari7/top-100-saas-companiesstartups/data

The dataset contains financial and operational information about leading SaaS companies. It has been compiled and verified from a variety of credible sources including investor reports, company filings, and product review platforms.

### Key Features

- 100 companies with 11 structured attributes.
- Current financial data (as of Q1 2025).
- Clean and analysis-ready format.
- Verified through multiple sources including public reports and databases.

### Columns

- Company Name  
- Founded Year  
- Headquarters  
- Industry  
- Total Funding  
- Annual Recurring Revenue (ARR)  
- Valuation  
- Number of Employees  
- Top Investors  
- Core Product  
- G2 Crowd Rating  

## Data Preparation & Cleaning

- Converted monetary values (ARR, Funding, Valuation) to floats by removing formatting characters.
- Standardized categorical fields (e.g., Industry, HQ).
- Removed missing and inconsistent records where necessary.

## Exploratory Data Analysis

### Univariate Analysis

- Distributions of ARR, Valuation, and Funding.
- Industry frequencies and regional concentrations.
- Investor name frequencies and rating breakdowns.

### Bivariate & Multivariate Analysis

- Relationship between ARR and Valuation.
- Funding vs. Employee Count.
- Industry-wise comparison of key metrics.
- Heatmaps showing feature correlations.

### Visualization Methods

- Histograms and box plots for spread and distribution.
- Bar plots and line graphs for categorical insights.
- Scatter plots and correlation heatmaps for pairwise relationships.

## Technologies Used

- Python (Jupyter Notebook)
- Pandas, NumPy (Data manipulation)
- Matplotlib, Seaborn (Data visualization)
- Jupyter Notebook (Exploratory interface)

## How to Run the Project

1. Clone the repository
git clone https://github.com/yourusername/SaaS_Companies_EDA_2025.git

2.  Navigate to the project directory
cd SaaS_Companies_EDA_2025

3. (Optional) Create and activate a virtual environment
python -m venv venv
source venv/bin/activate      # For macOS/Linux
# venv\Scripts\activate       # For Windows (use this instead)

4. Install required dependencies
pip install -r requirements.txt

5. Launch Jupyter Notebook
jupyter notebook

6. Open and run the notebook
SaaS_Companies_EDA_2025.ipynb


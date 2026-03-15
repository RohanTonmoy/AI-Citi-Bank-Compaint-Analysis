# 🏦 AI Bank Complaint Analysis & Visualization

This is a project developed during my pre-internship at Citi in July of 2023. This project utilizes **Exploratory Data Analysis (EDA)** and **Data Visualization** to analyze consumer complaints in the banking sector. By processing a large dataset of customer grievances, the notebook identifies systemic issues, the most frequently cited financial products, and the companies with the highest complaint volumes.

## 📋 Project Overview

The notebook provides an end-to-end pipeline for understanding customer dissatisfaction:

* **Data Acquisition & Cleaning**: Handles a dataset of over **3.2 million complaints**. It includes preprocessing steps to manage missing values (e.g., filling null narratives and zip codes) to ensure analytical consistency.
* **Statistical Profiling**: Generates distributions of complaints categorized by **Product** (e.g., Credit Reporting, Debt Collection, Mortgages) and **Company**.
* **Performance Metrics**: Evaluates company responsiveness, tracking whether responses were timely and if consumers disputed the outcomes.
* **Visualization**: Employs graphical representations to highlight the top 10 most complained-about banks and financial services.

## 🛠️ Tech Stack

| Category | Tools/Libraries |
| :--- | :--- |
| **Language** | Python (Jupyter Notebook) |
| **Data Handling** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **NLP** | NLTK (Tokenization) |

## 🚀 Key Features

* **Massive Data Processing**: Efficiently handles and samples large-scale CSV data (3.2M+ rows) for iterative analysis.
* **Top Company Analysis**: Identifies major industry players like **Equifax, Experian, and TransUnion** as high-volume complaint recipients in the sampled data.
* **Product Categorization**: Analyzes specific pain points, revealing that **Credit Reporting and Repair** often represent the largest share of consumer complaints.
* **Bar Chart Visuals**: Direct visualization of the top 10 companies and products to allow for quick stakeholder insights.

## 📂 How to Use

### 1. Environment
The notebook is optimized for **Google Colab** and requires access to the `complaints.csv` dataset.

### 2. Dependencies
Install the required packages via:

`pip install pandas numpy seaborn matplotlib nltk`

### 3. Execution
To reproduce the analysis, run the cells in the following order:
1. **Data Loading**: Import the CSV (ensure the file path matches your environment).
2. **Preprocessing**: Execute the cleaning cells to handle null values and formatting.
3. **Visualization**: Run the plotting cells to generate the top 10 charts and frequency distributions.

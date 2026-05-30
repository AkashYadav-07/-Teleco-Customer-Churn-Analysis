# -Teleco-Customer-Churn-Analysis
## Overview
This project analyzes customer churn data to identify patterns and factors that influence customer retention and customer loss. Using data visualization and exploratory data analysis (EDA), the project helps understand why customers leave a telecom service and which customer groups are more likely to churn.

## Objectives
- Analyze customer churn behavior.
- Identify important factors affecting churn.
- Visualize customer demographics and service usage patterns.
- Provide insights that can help improve customer retention.

## Dataset
The project uses the **Customer-Churn.csv** dataset containing customer information such as:

- Customer ID
- Gender
- Senior Citizen Status
- Tenure
- Contract Type
- Payment Method
- Internet Services
- Phone Services
- Total Charges
- Churn Status

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Preprocessing
The following preprocessing steps were performed:

- Loaded and inspected the dataset.
- Replaced blank values in `TotalCharges`.
- Checked for missing values.
- Checked for duplicate records.
- Converted `SeniorCitizen` values from `0/1` to `No/Yes` for better readability.

## Exploratory Data Analysis
Several visualizations were created to analyze customer churn:

1. Customer churn distribution.
2. Churn percentage using pie charts.
3. Gender-wise churn analysis.
4. Senior citizen churn analysis.
5. Tenure distribution analysis.
6. Contract type vs churn analysis.
7. Payment method vs churn analysis.

## Key Findings
- Approximately 26.5% of customers have churned.
- Senior citizens show a higher churn rate compared to non-senior citizens.
- Customers with shorter tenure are more likely to churn.
- Long-term contract customers tend to stay longer.
- Payment methods and service subscriptions influence customer retention.

## Project Structure

```
Customer-Churn-Analysis/
│
├── Customer-Churn.csv
├── TCA.ipynb
├── README.md
└── requirements.txt
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/customer-churn-analysis.git
```

2. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Run `TCA.ipynb`.

## Future Improvements
- Build machine learning models for churn prediction.
- Compare multiple classification algorithms.
- Create an interactive dashboard using Streamlit or Power BI.
- Perform feature importance analysis.
  

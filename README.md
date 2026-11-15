# Customer Churn Prediction & Strategic Risk Segmentation

A data science project that predicts which customers are likely to leave (churn) and segments them by risk and lifetime value, so a business can focus retention efforts where they matter most.

## Project Overview

Losing customers is expensive. This notebook analyzes customer behavior, builds a model to predict churn, and uses the results to group customers into risk segments with clear retention strategies.

**Goals**
- Explore the dataset and find the main drivers of churn
- Build and evaluate a churn prediction model
- Analyze customer lifetime value (LTV)
- Segment customers by risk to support strategic decisions

## Dataset

Each row represents one customer. The dataset contains the following variables:

| Variable | Type | Description |
|---|---|---|
| CustomerID | Categorical | Unique identifier (dropped during training to prevent overfitting) |
| Age | Numerical | Customer's age (18 - 65+) |
| Gender | Categorical | Female, Male |
| Tenure | Numerical | Duration of the customer relationship in months (1 - 60) |
| Usage Frequency | Numerical | How often the customer uses the platform (1 - 30) |
| Support Calls | Numerical | Number of calls made to customer support (0 - 10) |
| Payment Delay | Numerical | Days elapsed since the payment due date (0 - 30) |
| Subscription Type | Categorical | Basic, Standard, Premium |
| Contract Length | Categorical | Monthly, Quarterly, Annual |
| Total Spend | Numerical | Total money spent on the platform (100 - 1000) |
| Last Interaction | Numerical | Days since the last interaction with the site (1 - 30) |
| **Churn (Target)** | Binary | 1 = Churned (left), 0 = Loyal (stayed) |

## Workflow

1. **Data loading and cleaning**: inspect the data and handle missing values
2. **Exploratory data analysis**: visualize distributions and relationships with churn
3. **Preprocessing**: encode categorical variables and prepare features
4. **Modeling**: train and evaluate churn prediction models
5. **LTV analysis**: estimate the value of each customer
6. **Risk segmentation**: group customers by churn risk and value to guide retention strategy

## Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/SampreethMupparthy/customer-churn-prediction-ltv-analysis.git
   cd customer-churn-prediction-ltv-analysis
   ```
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Open the notebook:
   ```bash
   jupyter notebook customer-churn-prediction-ltv-analysis.ipynb
   ```
4. Run all cells from top to bottom.

> Make sure the dataset file used in the notebook is in the same folder as the notebook.

## Key Results

*Add your findings here, for example: model accuracy, the most important churn drivers, and what each risk segment looks like.*

## Author

**Sampreeth Mupparthy**
GitHub: [@SampreethMupparthy](https://github.com/SampreethMupparthy)

# Financial Data Analysis for AI Transition Strategy

## Overview
This project was completed as part of my **Executive Post Graduate Certification in Data Science and AI** from Intellipaat and iHub, IIT Roorkee. It analyzes financial data to support a fintech firm's transition to an AI-first strategy, focusing on bankruptcy prediction, profit forecasting, and company clustering.

## Project Structure
- `financial_analysis.ipynb`: Jupyter notebook with the complete analysis, including preprocessing, feature engineering, modeling, and results.
- `profit_forecasting_plot.png`: Scatter plot of actual vs. predicted profit values.
- `clustering_plot.png`: Scatter plot showing company clusters based on ROA and Debt-to-Equity.
- `requirements.txt`: List of Python dependencies.

**Note**: The dataset (`financial_data.csv`) is not included due to privacy constraints but can be provided upon request.

## Key Features
- **Data Preprocessing**: Removed duplicates, handled missing values, and filtered outliers using the IQR method (reduced dataset from 6819 to 457 rows).
- **Feature Engineering**: Created features like Profit_Margin_Ratio, Debt_to_Equity, and ROA_Composite.
- **Strategies**:
  - **Bankruptcy Classification**: Random Forest with 100% accuracy (noted potential overfitting).
  - **Profit Forecasting**: Linear Regression with an MSE of 1.04e-07.
  - **Company Clustering**: KMeans clustering to segment companies into three financial profiles.

## Results
- **Bankruptcy Classification**: Achieved perfect accuracy, suggesting a need for further validation with cross-validation or a more balanced dataset.
- **Profit Forecasting**: High accuracy with a tight alignment between actual and predicted values (see plot below).
- **Company Clustering**: Identified three distinct clusters for targeted strategies (see plot below).

### Profit Forecasting Plot
![Profit Forecasting](profit_forecasting_plot.png)

### Company Clustering Plot
![Company Clustering](clustering_plot.png)

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Vivekkumar-ds/financial-data-analysis.git

# Campaign Analysis

## Description
This project focuses on analyzing marketing campaign data to identify factors impacting the amount collected from campaigns. It utilizes Python libraries such as Pandas, NumPy, Seaborn, and StatsModels for data analysis, visualization, and regression modeling.


## Installation
Make sure you have Python installed on your system. Additionally, install the required libraries using pip:

```
pip install pandas numpy seaborn statsmodels
```

## Usage
1. Clone the repository or download the project files.
2. Ensure the dataset ("Campaign-Data.csv") is available in the project directory.
3. Open the project in a Python environment (Jupyter Notebook, IDE, etc.).
4. Run the provided scripts or modify them as needed for your analysis.

## Data Overview
The dataset ("Campaign-Data.csv") contains information about marketing campaigns, including client ID, client type, number of customers, monthly target, zip code, calendar date, amount collected, units sold, campaign details, sales contacts, and number of competitors.

## Analysis
- **Data Preprocessing**: Convert dates to datetime objects and extract month and year information.
- **Descriptive Statistics**: Compute value counts, cross-tabulations, and correlations to gain insights into the data.
- **Visualization**: Use Seaborn to visualize relationships and trends within the dataset.
- **Regression Analysis**: Utilize StatsModels to perform multiple linear regression to identify factors impacting the amount collected from campaigns.

## Results
The analysis reveals significant factors affecting the amount collected from campaigns, including campaign type, sales contacts, and client type. Detailed results and coefficients are provided for each variable.

## Conclusion
The project provides valuable insights into the effectiveness of marketing campaigns and suggests strategies for improving campaign performance based on the identified influential factors.

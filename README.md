Description:
This project aims to analyze marketing campaign data to identify factors impacting the amount collected from campaigns. It utilizes Python libraries such as Pandas, NumPy, Seaborn, and StatsModels to perform data analysis, visualization, and regression modeling.

Installation:
Ensure you have Python installed on your system. Additionally, install the required libraries using pip:

Copy code
pip install pandas numpy seaborn statsmodels
Usage:
Clone the repository or download the project files.
Ensure the necessary dataset ("Campaign-Data.csv") is available in the project directory.
Open the project in a Python environment (Jupyter Notebook, IDE, etc.).
Run the provided scripts or modify them as needed for your analysis.
Data Overview:
The dataset ("Campaign-Data.csv") contains information about marketing campaigns, including client ID, client type, number of customers, monthly target, zip code, calendar date, amount collected, units sold, campaign details, sales contacts, and number of competitors.

Analysis:
Data preprocessing: The script preprocesses the data, including converting dates to datetime objects and extracting month and year information.
Descriptive statistics: Various statistics such as value counts, cross-tabulations, and correlations are computed to gain insights into the data.
Visualization: Seaborn is used for visualizing relationships and trends within the dataset.
Regression analysis: StatsModels is employed to perform multiple linear regression to identify factors impacting the amount collected from campaigns.
Results:
The analysis reveals significant factors affecting the amount collected from campaigns, including campaign type, sales contacts, and client type. Detailed results and coefficients are provided for each variable.

Conclusion:
The project provides valuable insights into the effectiveness of marketing campaigns and suggests strategies for improving campaign performance based on the identified influential factors.

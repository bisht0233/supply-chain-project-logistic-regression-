-------------------------------------------------Supply Chain Project: Data to Dashboard---------------------------------------------------------------------
What is this project?
I took a dataset from Kaggle about Global Supply Chain disruptions and moved it through a full data pipeline. I wanted to see if I could predict shipping costs and find out which parts of the world are having the most trouble with shipping delays.

What I did:
Data Cleaning: I used Python and Pandas to clean up the raw data, handle missing values, and prepare it for analysis.

EDA (Exploratory Data Analysis):
I looked for patterns, like how weather or political risks affect delivery times. used heatmap from seaborn to analyse correlation between different columns.

Machine Learning:
 I built a regression model to on time delivery, used one hot encoder and label encoder to encode categorical columns to numerical, finally used linear regression to predict whether the delivery was on time or not.

Power BI Dashboard:
 I loaded the final cleaned data into Power BI to create a professional dashboard that tracks on-time deliveries, costs, and disruption events.

Files in this Repo:
supply_chain_disruption.ipynb: My Python code for cleaning and ML.
cleaned_data.csv: The data after I finished cleaning it.
supply_chain_dashboard.pbix: My Power BI file (the visual part).
global_supply_chain_disruption_v1.csv: The original data from Kaggle.

Author:
Sanjay Singh Bisht

Credit to Kaggle community:
for dataset global_supply_chain_disruption_v1.csv
link:https://www.kaggle.com/datasets/bertnardomariouskono/global-supply-chain-disruption-and-resilience


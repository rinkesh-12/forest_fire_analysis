# Forest Fire Data Analysis

📌 Overview
This project analyzes the Forest Fires dataset to identify patterns, trends, and possible factors influencing fire occurrences and severity.
The dataset contains meteorological and environmental attributes, allowing us to explore relationships between variables and create visualizations to understand the data better.

📂 Dataset
The dataset contains information such as:

Month & Day — Time period of the fire occurrence.

Weather Conditions — Temperature, relative humidity, wind speed, rainfall.

FFMC, DMC, DC, ISI — Fire Weather Index system components.

Burned Area — Hectares burned due to forest fire.

🔍 Objectives
Perform data cleaning and preprocessing.

Conduct exploratory data analysis (EDA) using visualizations.

Identify seasonal trends in forest fire occurrences.

Analyze correlation between meteorological conditions and burned area.

Present findings through plots and statistical summaries.

🛠 Technologies Used
Python

Jupyter Notebook

Pandas — Data manipulation

NumPy — Numerical computations

Matplotlib & Seaborn — Data visualization

📊 Analysis & Steps
Load the dataset into a Pandas DataFrame.

Data Preprocessing:

Convert month and day into numerical/ordered values.

Handle missing or inconsistent values.

Exploratory Data Analysis:

Distribution plots for each variable.

Correlation heatmaps.

Monthly and daily trends in fire occurrences.

Insights Extraction:

Which months have the highest fire activity.

Weather patterns that contribute to fire severity.

Visualizations:

Bar charts, line graphs, scatter plots.

Heatmaps showing correlations between variables.

📌 Key Findings
Most forest fires occur in August and September.

High temperature, low humidity, and low rainfall are common during major fire events.

The DC and ISI indices are strongly correlated with the burned area.

🚀 How to Run the Project
1. Clone this repository:
    git clone https://github.com/yourusername/forest-fire-analysis.git
2. Install dependencies:
   pip install pandas numpy matplotlib seaborn
4. Open Jupyter Notebook:
   jupyter notebook forest_fire.ipynb

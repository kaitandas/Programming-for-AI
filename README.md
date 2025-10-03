🏏 IPL Player Performance Analysis
A comprehensive data analysis project exploring IPL (Indian Premier League) cricket player statistics to uncover performance patterns and insights.

📊 Project Overview
This project analyzes IPL player statistics including batting, bowling, and fielding metrics to understand player performance trends and characteristics. The analysis includes data cleaning, exploratory data analysis, and machine learning implementation.

🛠️ Technologies Used
Python 3

Pandas - Data manipulation and analysis

Scikit-learn - Machine learning algorithms

Matplotlib - Data visualization

Jupyter Notebook - Interactive development environment

📁 Dataset
The project uses IPL Player Stat.csv containing comprehensive player statistics with the following key features:

Key Features:
Player Information: Player names and identification

Batting Metrics: Runs, boundaries, balls faced, batting average, strike rate

Bowling Metrics: Wickets, balls bowled, runs conceded, economy rate, bowling average

Fielding Metrics: Catches and stumpings

Match Statistics: Number of matches played

🔍 Analysis Performed
1. Data Exploration & Cleaning
Initial data inspection and summary statistics

Handling missing values and duplicates

Data type validation and correction

String cleaning and whitespace removal

2. Data Transformation
Created new feature: overs (calculated from balls bowled)

Grouped statistics by player

Correlation analysis between different performance metrics

3. Statistical Analysis
Descriptive statistics for all numerical columns

Correlation matrix to understand feature relationships

Filtered analysis based on specific performance criteria

4. Machine Learning
Implemented K-Nearest Neighbors (KNN) classifier

Train-test split for model validation

Feature engineering for model training

📈 Results
Key Findings:
Batting Performance:

Players with higher boundary percentages (>15%) consistently maintain strike rates above 120

Top run-scorers show strong correlation between matches played and total runs (r=0.79)

Bowling Insights:

Economical bowlers (<7.0 economy) tend to have better bowling averages

Wicket-taking ability shows weak correlation with bowling economy

Statistical Correlations:

Strong positive correlation between runs and boundaries (r=0.995)

Moderate correlation between matches played and catches (r=0.87)

Batting average shows significant correlation with strike rate (r=0.50)

🚀 Getting Started
Prerequisites
bash
pip install pandas scikit-learn matplotlib jupyter
Running the Project
Clone the repository

Ensure the IPL Player Stat.csv file is in the project directory

Open project.ipynb in Jupyter Notebook

Run the cells sequentially to reproduce the analysis

🤝 Contributing
We welcome contributions to improve this IPL player analysis project!

How to Contribute:
Fork the repository

Create a feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

Areas for Contribution:
Add new statistical analyses

Improve data visualizations

Enhance machine learning models

Optimize code performance

Add more IPL datasets

Fix bugs or improve documentation

# Startup Investment Analysis using Shark Tank India Dataset

## Project Overview

This project analyzes startup investment trends using the Shark Tank India dataset. The main objective is to understand investment patterns, funding behavior, deal outcomes, and shark participation through Exploratory Data Analysis (EDA). The project uses Python libraries such as Pandas and Matplotlib to process, analyze, and visualize the data.

## Objectives

- Analyze startup investment data.
- Identify the highest-funded startups.
- Calculate total and average investment amounts.
- Analyze successful and unsuccessful deals.
- Study shark participation in funding.
- Visualize investment trends using charts.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook / VS Code

## Dataset

The dataset contains information about startups that appeared on Shark Tank India.

### Features

- Episode Number
- Pitch Number
- Brand Name
- Business Idea
- Deal Status
- Pitch Ask Amount
- Ask Equity
- Ask Valuation
- Deal Amount
- Deal Equity
- Deal Valuation
- Sharks Present
- Sharks Invested
- Amount Per Shark

## Project Structure

```
Startup_Investment_Analysis/
│── dataset/
│   └── shark_tank.csv
│
│── analysis.py
│── README.md
│── report.pdf
│
│── project_output.mpg


```

## Installation

Install the required Python libraries.

```bash
pip install pandas matplotlib
```

## How to Run

1. Download or clone the project.
2. Place the dataset inside the `dataset` folder.
3. Open the project in VS Code or Jupyter Notebook.
4. Run the following command:

```bash
python analysis.py
```

## Project Workflow

### 1. Data Loading

- Import the dataset using Pandas.
- Verify dataset structure.

### 2. Data Exploration

- Display the first few records.
- Check dataset information.
- Find missing values.
- Generate statistical summaries.

### 3. Data Analysis

- Calculate total startup pitches.
- Calculate successful and unsuccessful deals.
- Calculate total investment amount.
- Calculate average investment.
- Find the highest and lowest investment amounts.
- Identify the top-funded startups.
- Analyze the most common business ideas.
- Analyze shark participation.

### 4. Data Visualization

The project generates the following visualizations:

- Top 10 Highest Investments
- Investment Distribution Histogram
- Deals vs No Deals Pie Chart
- Top Business Ideas Bar Chart
- Number of Sharks Invested Bar Chart

## Output

The program displays:

- Dataset Information
- Missing Values Report
- Statistical Summary
- Total Startup Pitches
- Total Successful Deals
- Total Investment Amount
- Average Investment Amount
- Highest Investment
- Lowest Investment
- Top 10 Funded Startups
- Business Idea Analysis
- Shark Participation Analysis

The following images are generated:

- top10_investments.png
- investment_distribution.png
- deal_pie_chart.png
- top_business_ideas.png
- sharks_invested.png

## Key Insights

- Investment amounts vary significantly across startups.
- Only a portion of startups receive funding.
- Some startups attract investments from multiple sharks.
- Certain business ideas receive more investor interest.
- The dataset provides valuable insights into startup funding trends.

## Future Enhancements

- Develop an interactive Power BI dashboard.
- Integrate SQL for advanced analysis.
- Build a machine learning model to predict funding success.
- Create a Streamlit or Flask web application.
- Perform advanced trend analysis and forecasting.

## Conclusion

This project demonstrates how Python can be used to analyze real-world startup investment data. Using data cleaning, exploratory data analysis, and visualization techniques, the project provides meaningful insights into investment trends and investor behavior. It is an excellent beginner-friendly data analytics project that strengthens practical skills in Python, data visualization, and business analysis.

## Author

Litheeswari B

Data Analytics Intern

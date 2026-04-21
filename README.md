# Movie Revenue Analysis

## Project Overview
This project explores what factors most influence a movie's box office 
performance. Using a dataset of thousands of films, I analyzed correlations 
between production budgets, audience ratings, vote counts, and gross earnings 
to identify the key drivers of movie profitability.

## Tools Used
- **Python** — Data cleaning, analysis, and visualization
- **Pandas** — Data manipulation and correlation analysis
- **Matplotlib & Seaborn** — Data visualization and heatmaps
- **Jupyter Notebook** — Development environment

## Process

### 1. Data Cleaning
- Loaded raw movie dataset and checked for missing values across all columns
- Converted budget, votes, and gross columns to correct integer data types
- Sorted data by gross earnings descending
- Removed duplicate records

### 2. Exploratory Data Analysis
- Built scatter plot comparing production budget vs gross earnings
- Used Seaborn regression plot to visualize the relationship with a trend line
- Generated a correlation matrix for all numeric features

### 3. Feature Encoding & Full Correlation Analysis
- Converted all categorical columns (genre, company, director, etc.) 
  to numeric codes to include them in correlation analysis
- Generated a full correlation heatmap across all 15 features
- Unstacked correlation matrix and sorted all pairs to find 
  strongest relationships

## Key Findings
- **Budget and gross earnings** have the strongest correlation at **0.74** — 
  higher budget films tend to earn significantly more
- **Votes and gross earnings** also strongly correlated at **0.63** — 
  more audience engagement drives higher revenue
- **Company had no significant correlation** to gross earnings, 
  disproving the initial hypothesis that studio name drives box office success
- Genre, director, and star power showed weak correlations to gross earnings


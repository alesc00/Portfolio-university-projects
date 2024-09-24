# 🏀 Applied Linear Model Project

This project explores how NBA player statistics and demographic data impact their salaries using linear models. The dataset includes statistics from the 2021-2022 NBA season, such as shooting percentages, games played, and player salaries.

## 📁 Project Contents

- **project.Rmd**: Complete analysis and code in R Markdown.
- **data/NBA-stats.csv**: Dataset of NBA player statistics and salaries.
- **docs/presentazione.pdf**: Summary presentation of the project.

## 📊 Summary

The dataset includes 415 players with 16 variables, including:
- **Age**: Player's age.
- **GP (Games Played)**: Number of games played.
- **W (Wins)**: Number of wins.
- **TS.PCT (True Shooting Percentage)**: Measure of shooting efficiency.
- **PTS (Points)**, **REB (Rebounds)**, **AST (Assists)**: Key performance metrics.
- **Salary**: Player salary in millions of USD.

### 🔍 Key Objectives:
The goal is to determine how these statistics impact player salaries. While performance data plays a role, other unmeasured factors, such as popularity, are not included in this analysis.

### 📈 Key Analyses:
- **Visualization**: Histograms and boxplots of salary and key metrics.
- **Linear Regression**: Using multiple regression models to predict salaries.
- **Model Selection**: Best subset selection to identify the most significant predictors (AIC, BIC, adjR²).
- **Diagnostics**: Regression diagnostics to ensure model reliability.

## 🛠️ Libraries Used:
- **dplyr**: Data manipulation.
- **ggplot2**: Visualization of salary and performance data.
- **leaps**: Best subset selection for model building.
- **corrplot**: Visualization of the correlation matrix.
- **car** & **coefplot**: Regression diagnostics and coefficient plots.

## 📌 Conclusions:
Certain performance stats (like points, games played) are predictive of salary, but unobserved factors likely influence player compensation. There is evidence of heteroscedasticity, which suggests further model refinement is needed.

⚠️ **Note**: The dataset was manually collected from NBA.com and HoopsHype.com and is not an exact representation of all factors influencing salaries.

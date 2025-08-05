# MLB ERA+ Analysis

This project explores **ERA+** (Adjusted Earned Run Average), an adjusted pitching statistic in Major League Baseball (MLB), using data from the **2022 MLB season**. The analysis investigates how different player factors may effect **ERA+**.

## Project Objectives

- Understand the distribution and significance of ERA+
- Identify patterns in ERA+ across teams, ages, and throwing handedness
- Compare performance between starting and relief pitchers
- Utilize supervised learning techniques to create robust ERA+ prediction models

## Techniques Used

- Exploratory Data Analysis (PCA, correlation analysis, clustering)
- Feature Selection
- Supervised learning (XGBoost, Random Forest, Support Vector Regression)

## What is ERA+?

ERA+ is a normalized version of Earned Run Average (ERA) that adjusts for **ballpark factors** and **league-wide pitching environment**.  
- **100** is league average  
- **>100** is better than average  
- **<100** is worse than average  
ERA+ allows better comparisons across players and teams, regardless of home park or season context.

## Key Findings

- Overall team success showed a meaningful relationship with average team ERA+ in 2022
- No significant relationship between ERA+ and either handedness or age
- Pitchers with higher ERA+ profile better as relief or closing pitchers, rather than starting pitchers
- Supervised learning models show moderate success in ERA+ prediction
- WHIP emerged as the strongest predictor for ERA+

## Tools & Data

- R (`ggplot2`, `caret`, `randomForest`, `xgboost`, `e1071`)
- MLB 2022 season data (https://www.kaggle.com/datasets/vivovinco/2022-mlb-player-stats?select=2022+MLB+Player+Stats+-+Pitching.csv)

## Acknowledgement

- This project was conducted as part of a university course on data visualiztion and analysis. It is shared here to demonstrate my skills and experience in data analysis. It is not intended for commerical use.

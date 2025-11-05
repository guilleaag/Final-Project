# Final-Project

Dataset: https://www.kaggle.com/datasets/nabihazahid/spotify-dataset-for-churn-analysis

# Spotify Churn Analysis

## Overview
This project explores a Spotify user dataset to understand what factors influence whether users churn (stop using the platform). The dataset includes user demographics, listening habits, and subscription details.

## Objective
To identify behavioral and demographic factors that predict churn using Python for data cleaning, visualization, and analysis.

## Data Cleaning
- Checked for missing values and duplicates.
- Converted categorical fields (like gender, device type) to category data type.
- Converted binary columns (`is_churned`, `offline_listening`) to boolean type.

## Data Manipulation
- Filtered churned users for focused analysis.
- Grouped data by subscription type to calculate churn rate.
- Sorted users by listening time to identify top listeners.

## Visualizations
1. **Churn Rate by Subscription Type**: Premium users churn less than Free users.
2. **Distribution of Listening Time**: Most users have moderate engagement, while heavy listeners rarely churn.
3. **Correlation Heatmap**: Skip rate and listening time show strong correlation with churn.

## Statistical Insights
- Churned users have ~40% lower listening time on average.
- Skip rate is positively correlated with churn.
- Premium users have the lowest churn rate.

## Conclusion
User engagement and subscription type play major roles in predicting churn. Encouraging longer listening sessions and reducing skip rate could improve user retention.

---

### Files Included
- `spotify_churn_dataset.csv`
- `spotify_churn_analysis.ipynb`
- `README.md`
- Visualizations (`.png` files)

---

### How to Run
1. Open `spotify_churn_analysis.ipynb` in Google Colab.
2. Upload the dataset if prompted.
3. Run all cells to reproduce the analysis and figures.

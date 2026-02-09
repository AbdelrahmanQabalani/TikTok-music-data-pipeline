# TikTok Trending Music Data Pipeline & Analysis

## Overview
This project builds a complete data engineering and exploratory data analysis pipeline for a TikTok trending music dataset.

## Objectives
- Clean and preprocess the dataset
- Engineer meaningful features
- Explore patterns in trending music characteristics
- Prepare the data for future predictive modeling

## Data Engineering Steps
- Removed duplicates
- Handled missing values (mean for numerical, mode for categorical)
- Normalized numerical features using MinMaxScaler
- Encoded categorical variables using LabelEncoder
- Created tempo bins (Slow, Moderate, Fast, Very Fast)

## Exploratory Data Analysis
- Correlation heatmap
- Histograms of numerical features
- Boxplots for outlier detection
- Statistical summaries

## Key Insights
- Higher energy and danceability are linked with popularity
- Loudness and valence show positive correlation with engagement
- Moderate tempos perform better than extreme ones

## Tools Used
- Python (Pandas, NumPy)
- Scikit-learn
- Matplotlib & Seaborn

# Exploratory Data Analysis - Deforestation Dataset

This repository contains an exploratory data analysis (EDA) of a deforestation dataset obtained from Kaggle. The dataset includes the abbreviation of countries, the percentage of forest area in 2000 and 2020.

## Data Preprocessing

- Complemented the dataset with additional country information such as continent, region, and development level by merging with another dataset.
- Complemented the dataset with area information in square kilometers (sqkm) per country, and calculated the forest area in sqkm for 2000 and 2020.

## Data Cleaning and Validation

- Checked for duplicates in the dataset.
- Verified data types to ensure accuracy and consistency.

## Descriptive Statistics

- Extracted key statistical information using the `describe()` method.
- Examined the frequency of each categorical class.

## Dataset Information

- Analyzed the shape of the dataset.

## Data Distribution

- Visualized the distribution of forest percentage in 2000 and 2020 using `histplot`.
- Plotted barplots to show the total forest area in sqkm by development, continent, and region.

## Boxplots

- Explored the distribution of forest percentage and forest area in sqkm by region and development for 2000 and 2020 using `boxplot`.
- Identified outliers in the forest area using the Interquartile Range (IQR) method.

## Data Transformation

- Performed column transformation from categorical to numerical for correlation analysis.
- Applied logarithmic transformation to normalize outliers in forest area data.

## Correlation Analysis

- Analyzed the correlation between numerical columns using the transformed data.

## Additional Visualizations

- Plotted scatter plots to visualize the relationship between forest area in sqkm and development by region for 2000 and 2020.
- Utilized `kdeplot` to analyze the distribution of forest percentage in 2000 by continent.

## Country Analysis

- Identified the countries with the minimum and maximum forest area percentage in 2000 and 2020.

The repository includes the Jupyter Notebook containing the code and visualizations for the EDA. The goal of this analysis is to gain insights into deforestation patterns and trends, identifying outliers, and understanding the relationship between various factors.

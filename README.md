# EDA and Feature Engineering of Google Play Store Dataset



## Table of Contents

- [Problem Statement](#problem-statement)

- [Data Collection](#data-collection)

- [Steps to Follow](#steps-to-follow)

  - [Data Cleaning](#data-cleaning)

  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)

  - [Feature Engineering](#feature-engineering)

- [Get the Detailed Analysis for below](#get-the-detailed-analysis-for-below)
  
- [Conclusion](#conclusion)

- [Installation and Usage](#installation-and-usage)
- [Author](#author)



## Problem Statement

The Google Play Store hosts over 2.56 million apps, making it crucial to understand app trends and user preferences. The objective of this project is to analyze app data to determine:

- The most popular app category.

- The app with the highest number of installs.

- The app with the largest size.



## Data Collection

The dataset consists of 10,841 rows and 20 columns, providing details about various apps, including category, rating, reviews, installs, size, and more.



## Steps to Follow

### Data Cleaning

1. Handle missing values.

2. Convert columns to appropriate data types.

3. Remove duplicates.

4. Clean the `Reviews`, `Size`, `Installs`, and `Price` columns to ensure uniformity.



### Exploratory Data Analysis (EDA)

1. Analyze numerical and categorical features.

2. Examine distributions and insights for each feature.

3. Visualize the popularity and distribution of app categories.



### Feature Engineering

1. Extract day, month, and year from the `Last Updated` column.

2. Create additional features based on the cleaned data.



## Get the Detailed Analysis for below
 1. Most Popular App Category
 2. Top 10 App Categories
 3. Category with Largest Number of Installations
 4. Top 5 Most Installed Apps in Popular Categories
 5. Apps with 5-Star Ratings




## Conclusion

The analysis provides insights into the most popular categories, most installed apps, and highly rated apps on the Google Play Store. This information can help developers and businesses understand user preferences and market trends.



## Installation and Usage

To run this analysis:

1. Clone this repository.

2. Install the necessary libraries:

   ```bash

   pip install pandas numpy matplotlib seaborn

   ```
3. Run the .ipynb file Jupyter Notebook to execute the code and view the visualizations.


## Author
**Sujeet Nayak** 
Data Engineering



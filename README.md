# EDA and Feature Engineering of Google Play Store Dataset

## Problem Statement

Today, 1.85 million different apps are available for users to download. Android users have even more choices, with 2.56 million apps available through the Google Play Store. These apps play a significant role in how we live our daily lives. The objective of this analysis is to:

- Identify the **most popular app category**.
- Find the app with the **largest number of installs**.
- Determine the app with the **largest size**.

## Dataset

The dataset contains information about apps on the Google Play Store. It consists of **20 columns** and **10,841 rows**, with data collected from various app attributes such as category, size, installs, reviews, and ratings.

### Key Features in the Dataset:
- **App**: Name of the application.
- **Category**: Category to which the app belongs.
- **Rating**: Average rating of the app.
- **Reviews**: Number of user reviews.
- **Size**: Size of the app (in MB or KB).
- **Installs**: Number of times the app has been installed.
- **Price**: Cost of the app (free or paid).
- **Content Rating**: Target audience for the app.
- **Genres**: Type or genre of the app.
- **Last Updated**: Date when the app was last updated.

## Objectives of Analysis

1. **Exploratory Data Analysis (EDA):**
   - Understand the structure and content of the dataset.
   - Visualize distributions and relationships among features.
   - Handle missing values and outliers.

2. **Feature Engineering:**
   - Encode categorical variables.
   - Create new features (if required) to enhance model performance.
   - Normalize and scale numerical features for consistent analysis.

3. **Key Insights:**
   - Identify the most popular app category based on installs.
   - Find apps with the highest and lowest ratings.
   - Determine which apps have the largest size and highest number of installs.

## Methods and Techniques

### Tools and Libraries:
- **Python**: The primary language for analysis.
- **Pandas**: For data manipulation and cleaning.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-learn**: For feature engineering and model building.
- **XGBoost**: For predictive analysis.

### Steps:
1. **Data Cleaning:**
   - Remove duplicates.
   - Handle missing values.
   - Convert columns to appropriate data types.

2. **Exploratory Data Analysis (EDA):**
   - Analyze distributions and relationships among variables.
   - Visualize trends in app categories, sizes, ratings, and installs.

3. **Feature Engineering:**
   - Encode categorical variables such as `Category`, `Type`, and `Genres` using label encoding.
   - Normalize numerical variables like `Size` and `Price`.

4. **Model Building:**
   - Train machine learning models to predict app ratings based on features.
   - Evaluate models using metrics like Mean Squared Error (MSE) and R² score.

## Results

- **Most Popular Category:** Game
- **App with Largest Number of Installs:**
   Most popular game is Subway Surfers.
   Most popular communication app is Hangouts.
   Most popular productivity app is Google Drive.
   Most popular social app is Instagram.
- **Number of five rated apps on Google Play store** 271


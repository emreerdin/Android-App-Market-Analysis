# Android-App-Market-Analysis
# Comprehensive Analysis of Google Play Store Apps and User Reviews

This project provides an in-depth analysis of the Android app market by examining over ten thousand apps available on the Google Play Store. The analysis covers various aspects such as app categories, ratings, pricing strategies, and user sentiment. The goal is to derive insights that can be used to drive growth and retention for mobile apps.

## Table of Contents
- [Project Overview](#project-overview)
- [Datasets](#datasets)
- [Project Structure](#project-structure)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Sentiment Analysis](#sentiment-analysis)
- [Key Findings](#key-findings)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

Mobile apps are ubiquitous, and with the ease of creation and potential profitability, the number of apps continues to grow. This project analyzes the app market on Google Play to identify trends, key categories, and user preferences. We explore the data to answer several critical questions, such as which categories dominate the market, how app size and price impact ratings, and the differences in user sentiment between paid and free apps.

## Datasets

The analysis uses two datasets:
- `apps.csv`: Contains details of the applications on Google Play, with 13 features describing each app.
- `user_reviews.csv`: Contains 100 user reviews for each app, including the sentiment (Positive, Negative, Neutral), sentiment polarity, and sentiment subjectivity.

## Project Structure

- **`apps.csv`**: The main dataset with app details.
- **`user_reviews.csv`**: The user reviews dataset with sentiment analysis.
- **`notebook.ipynb`**: Jupyter notebook containing all code for data cleaning, analysis, and visualization.
- **`README.md`**: Project overview and documentation.
- **`LICENSE`**: License for the project (if applicable).

## Data Cleaning

Data cleaning is an essential part of the analysis process. We handle special characters in the `Installs` and `Price` columns and ensure that numeric values are correctly formatted for further analysis. Data types are also corrected to ensure that features like `Installs`, `Size`, `Rating`, and `Price` are in the appropriate format for analysis.

## Exploratory Data Analysis

The exploratory data analysis (EDA) section covers:
- **App Categories**: Analyzing the distribution of apps across categories to determine market share.
- **App Ratings**: Understanding the distribution of app ratings and identifying the average rating across all apps.
- **App Size and Price**: Investigating how app size and price impact ratings and user preferences.

## Sentiment Analysis

Using the `user_reviews.csv` dataset, sentiment analysis is performed to determine the mood of user reviews for both paid and free apps. The analysis explores the differences in user feedback based on app pricing models, offering insights into user satisfaction and app quality.

## Key Findings

Some of the key findings from this project include:
- The **Family** and **Game** categories have the highest share of apps in the Google Play Store.
- Most highly-rated apps have a size between 2 MB and 20 MB.
- The majority of apps are priced below $10, with **Medical** apps being the most expensive.
- Paid apps tend to have less extreme negative feedback compared to free apps, indicating higher perceived quality.

## Installation

To run this project you need to upload ````notebook.jpynb```` on Jupyter Notebook and start running the cells.

## Usage

1. Clone this repository:
    ```bash
    git clone https://github.com/emreerdin/google-play-store-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd google-play-store-analysis
    ```
3. Open the Jupyter notebook:
    ```bash
    jupyter notebook notebook.ipynb
    ```

## Contributing

Contributions are welcome! If you would like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

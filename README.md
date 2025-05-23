# 📱 Amazon Cell Phones Market Analysis

## 🔍 Project Title
**Consumer Preferences and Pricing Trends in Amazon Cell Phones Market: A Data-Driven Analysis**

## 📚 Overview
This project explores consumer purchasing behavior on Amazon’s cell phone market using a cleaned dataset. It aims to uncover how price, brand, ratings, and reviews influence buying decisions. We use exploratory data analysis, regression modeling, clustering, and sentiment analysis to draw insights.

## 📈 Objectives
- Identify key features influencing customer purchases.
- Analyze brand pricing strategies and rating patterns.
- Segment products using clustering based on price, ratings, RAM, etc.
- Classify customer sentiment using rating categories.
- Provide actionable recommendations for e-commerce sellers.

## 🧰 Tools & Technologies
- **Python** (Pandas, Seaborn, Matplotlib, Scikit-learn)
- **Jupyter Notebook**
- **WordCloud**
- **Machine Learning Models**: Linear Regression, KMeans Clustering

## 🗃️ Dataset
Dataset sourced from Kaggle:  
📎 [Amazon Cell Phones Cleaned Scraped](https://www.kaggle.com/datasets/michaelmatta0/amazon-cell-phones-cleaned-scraped-data)

Key columns:  
`Price (Dollar)`, `Rating`, `Number of Ratings`, `Brand`, `Operating System`, `RAM`, `Storage`, `Cellular Technology`, `Available Colors`, and more.

## 🧪 Project Workflow

### Step 1: Data Cleaning
- Imputed missing values using mean/median/mode.
- Handled categorical nulls by replacing them with 'Unknown'.

### Step 2: Exploratory Data Analysis (EDA)
- Histograms, pairplots, and KDE plots
- Brand-wise count and price analysis
- Correlation heatmaps
- Price trends and scatter plots (e.g., Price vs Rating)

### Step 3: Regression Modeling
- Used Linear Regression to model the relationship between price and key features.
- **R² Score**: ~0.30  
- Important predictors: `Storage`, `RAM`, `Discount %`

### Step 4: Clustering
- Applied **KMeans** clustering for product segmentation.
- Used the **Elbow method** to choose optimal `k=3`.
- Plotted product clusters based on standardized features.

### Step 5: Sentiment Analysis
- Classified reviews as Positive, Neutral, or Negative using ratings.
- Visualized sentiment distribution and pricing across sentiments.

## 📊 Key Insights
- **Samsung and Apple** dominate in volume and price.
- Positive-rated phones tend to have higher prices and better specs.
- Discounts don't always correlate with higher ratings or sales.
- Strong positive correlation between storage and price.

## 📎 Files Included

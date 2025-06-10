# RESTAURANT-RATING-PREDICTION-AND-ANALYSIS


This project involves exploring and analyzing restaurant dataset to understand customer preferences, pricing trends, service availability, and ratings. The insights gained can help recommend the best type of restaurant to open in a specific location and understand the behavior of online food customers.

---

## 📂 Dataset Overview

The dataset contains details about restaurants including:

- Restaurant name, location, cuisines
- Table booking and online delivery status
- Price range, votes, and ratings
- Country, city, and other metadata

---

## 📌 Tasks & Implementation

### ✅ Level 1

#### 🔹 Task 1: Data Exploration and Preprocessing
- Identify the number of rows and columns
- Check and handle missing values
- Convert data types where necessary
- Analyze the distribution of the target variable (`Aggregate rating`)

#### 🔹 Task 2: Descriptive Analysis
- Compute basic statistics (mean, median, std) for numeric columns
- Explore categorical variables like `Country Code`, `City`, and `Cuisines`
- Identify top cuisines and cities with the highest number of restaurants

#### 🔹 Task 3: Geospatial Analysis
- Visualize restaurant locations using latitude and longitude
- Analyze location-based distribution of restaurants
- Explore correlation between location and rating

---

### ✅ Level 2

#### 🔹 Task 1: Table Booking and Online Delivery
- Calculate the % of restaurants offering table booking and online delivery
- Compare average ratings of restaurants with and without table booking
- Analyze online delivery availability across different price ranges

#### 🔹 Task 2: Price Range Analysis
- Find the most common price range
- Calculate average rating per price range
- Identify which price range (color) has the highest rating

#### 🔹 Task 3: Feature Engineering
- Extract features like name length, address length
- Encode new features: `Has Table Booking`, `Has Online Delivery`, etc.

---

### ✅ Level 3

#### 🔹 Task 1: Predictive Modeling
- Build a regression model to predict `Aggregate rating`
- Split data into train-test sets, evaluate with metrics
- Test models: Linear Regression, Decision Tree, Random Forest

#### 🔹 Task 2: Customer Preference Analysis
- Analyze the link between `Cuisine Type` and ratings
- Find most popular cuisines (by votes)
- Identify cuisines that consistently receive high ratings

#### 🔹 Task 3: Data Visualization
- Use histogram, boxplot, and barplot to visualize ratings
- Compare average ratings by cuisine and city
- Plot relationships between features and target variable

---

## 📊 Tools & Technologies

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook / Google Colab
- Scikit-learn (for modeling)

---

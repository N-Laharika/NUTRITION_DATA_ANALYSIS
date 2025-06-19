# NUTRITION_DATA_ANALYSIS
🧾 Problem Statement
Title: Predicting Calorie Content of Indian Foods Using Nutritional Attributes

Indian cuisine includes a wide variety of dishes with complex nutritional compositions. Manually estimating calorie content is often difficult. This project aims to:

Predict the calorie value of an Indian food item based on its nutritional components.

Support use cases like health monitoring apps and diet recommendation systems.

📂 Dataset Overview
Dataset Name: Indian_Food_Nutrition_Processed.csv

Rows: 1014

Columns: 12

Columns:
Dish Name

Calories (kcal)

Carbohydrates (g)

Protein (g)

Fats (g)

Free Sugar (g)

Fibre (g)

Sodium (mg)

Calcium (mg)

Iron (mg)

Vitamin C (mg) (contains missing values)

Folate (µg) (contains missing values)

🧹 Preprocessing Steps
Handled missing values using mean imputation.

Renamed "Folate (µg)" to "Vitamin B (µg)" for consistency.

Removed duplicates.

Outliers identified using IQR and boxplots.

Encoded Dish Name using LabelEncoder.

Standard scaling applied to numeric features.

Calorie values were discretized into levels (Low, Medium, High) using KBinsDiscretizer.

📊 Exploratory Data Analysis (EDA)
Scatter Plot: Fats vs Calories showed a strong positive correlation.

Pie Chart: Top 10 high-calorie Indian dishes.

Histogram: Distribution of calorie values across dishes.


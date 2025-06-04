# EarthQuake_Prediction_Celebal

🌍 EarthQuake Prediction Project
This project utilizes machine learning techniques to analyze and predict earthquake-related data. It involves data preprocessing, visualization, and model training using multiple regression algorithms to uncover patterns and potentially forecast earthquake metrics.

📘 Project Workflow & Key Concepts
1. 🔧 Libraries Used
pandas, numpy – For data manipulation and numerical operations.

matplotlib, seaborn – For visualizing data through charts and plots.

sklearn – For preprocessing, model building, and evaluation.

2. 📂 Data Loading
Dataset: earthquake_1995-2023.csv

Description: Contains earthquake event records from 1995 to 2023.

3. 🧐 Data Inspection
Functions used:

.shape, .head() – To view dataset structure and preview records.

.info(), .isnull().sum() – To check data types and missing values.

4. 🧹 Data Preprocessing
Handling Missing Values: Dropped rows with nulls for simplicity.

Label Encoding: Converted categorical features to numeric using LabelEncoder.

Standard Scaling: Applied StandardScaler to normalize features and enhance model performance.

5. 📊 Data Visualization Techniques (8 Types)
Plot Type	Description
Histogram	Shows distribution of a numeric variable.
Boxplot	Detects outliers, displays quartiles and spread.
Scatter Plot	Examines relationships between two numeric features.
Heatmap	Displays feature correlation matrix with color intensities.
Bar Plot	Shows frequency/count of categorical or discrete numeric features.
Line Plot	Reveals trends over time (ideal for time-series analysis).
Violin Plot	Combines boxplot and KDE to show distribution and density.
Pair Plot	Shows scatterplots of all feature pairs and histograms on the diagonal.

6. 🧠 Model Training
Feature Selection: Split dataset into features (X) and target (y).

Train-Test Split: Applied an 80-20 split using train_test_split for evaluation.

7. 🤖 Algorithms Used
Linear Regression – Assumes a linear relationship between features and target.

Decision Tree Regressor – Splits data via feature-based decision rules.

Random Forest Regressor – Ensemble of decision trees to reduce overfitting and improve accuracy.

Support Vector Regressor (SVR) – Finds the best-fit line with a defined margin; robust against outliers.

8. 📏 Evaluation Metrics
Metric	Purpose
Mean Squared Error (MSE)	Measures average squared differences between actual and predicted values. Lower is better.
R² Score	Indicates the proportion of variance explained by the model. Closer to 1 = better.
Accuracy / Classification Report / Confusion Matrix	Included optionally if target values are categorized; evaluates model precision, recall, F1-score.














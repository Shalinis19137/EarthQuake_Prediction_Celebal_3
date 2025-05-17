# EarthQuake_Prediction_Project
This project uses machine learning techniques to analyze and predict earthquake-related data. It includes data preprocessing, visualization, and model training using multiple regression algorithms to understand the patterns and potentially forecast earthquake metrics.

📘 Explanation of Terms & Workflow
1. Libraries Used
pandas, numpy: For data manipulation and numerical operations.

matplotlib, seaborn: For visualization.

sklearn: For preprocessing, model training, and evaluation.

2. Data Loading
The dataset (earthquake_1995-2023.csv) includes earthquake event records from 1995 to 2023.

3. Data Inspection
.shape, .head(), .info(), .isnull().sum(): Used to understand the structure, preview records, and check missing values.

4. Data Preprocessing
Missing Values Handling: Dropping missing rows for simplicity.

Label Encoding: Converting categorical features into numeric values using LabelEncoder.

Standard Scaling: Normalizing the data using StandardScaler to improve model performance.

5. Visualization Techniques (8 types)
Histogram: Distribution of a numeric column.

Boxplot: Detect outliers and distribution.

Scatter Plot: Relation between two variables.

Heatmap: Correlation between features.

Bar Plot: Frequency of categorical or integer features.

Line Plot: Trends over time or order.

Violin Plot: Distribution and density.

Pair Plot: Relationships between multiple numeric variables.

6. Model Training
Features (X) and Target (y) are split from the dataset.

Train-Test Split: 80-20 division using train_test_split.

7. Algorithms Used
LinearRegression

DecisionTreeRegressor

RandomForestRegressor

SVR (Support Vector Regression)

8. Evaluation Metrics
mean_squared_error (MSE): Measures average squared difference.

r2_score: Goodness of fit.

classification_report, accuracy_score, confusion_matrix: Mainly used for classification, but might be included for exploratory purposes.


📊 Plot Types Explained (8 Types)
Histogram

Shows the frequency distribution of a single numeric feature.

Helps identify the spread, skewness, and presence of outliers in the data.

Boxplot

Displays the distribution, median, and outliers of a numeric column.

Useful for spotting extreme values and understanding data spread (IQR).

Scatter Plot

Shows the relationship between two numeric variables.

Helps detect correlations or patterns like linear or nonlinear relationships.

Heatmap (Correlation Matrix)

Visual representation of the correlation coefficients between numeric variables.

Stronger correlations are easily spotted using color intensity.

Bar Plot

Represents the count of each category in an integer or categorical column.

Useful for comparing the frequency of different classes or events.

Line Plot

Connects data points with a line, usually used to observe trends over time.

Helpful for time series or sequential data to identify rising/falling trends.

Violin Plot

Combines a boxplot with a KDE (Kernel Density Estimate).

Shows both distribution and probability density of the data.

Pair Plot

Generates scatter plots for all pairwise combinations of variables and histograms on the diagonal.

Excellent for multivariate analysis and identifying correlations.


🤖 Machine Learning Models Explained
Linear Regression

Predicts a numeric target by fitting a straight line through the data.

Assumes a linear relationship between input features and output.

Decision Tree Regressor

Predicts values by learning decision rules from features.

Breaks the data into branches like a flowchart based on feature conditions.

Random Forest Regressor

An ensemble of multiple decision trees.

Improves accuracy and reduces overfitting by averaging the results of many trees.

Support Vector Regressor (SVR)

Tries to fit the best line within a margin of tolerance.

Good for complex relationships and outlier-resilient predictions.


📏 Evaluation Metrics Used
Mean Squared Error (MSE)

Measures the average squared difference between actual and predicted values.

Lower MSE indicates better model performance.

R² Score (Coefficient of Determination)

Represents how much variance in the target variable is explained by the model.

Ranges from 0 to 1; higher values mean better performance.

Accuracy Score / Classification Report / Confusion Matrix

Though typically used for classification, they might be included if the target variable is binned into classes.

They help evaluate model correctness, precision, recall, and F1-score.

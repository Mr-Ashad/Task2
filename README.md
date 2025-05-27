# Task 2 – Exploratory Data Analysis
Tools Used: Python, Pandas, NumPy, Matplotlib, Seaborn
### Steps:
## Visualized Missing Data
Used heatmaps and info summaries to get a clear picture of null vs non-null values across the dataset.

## Dropped Columns with Excessive Missing Values
The Cabin column had too many missing entries, so it was removed from the dataset.

## Removed Irrelevant Features
Columns like PassengerId, Name, and Ticket were dropped since they don’t carry predictive value for survival.

## Handled Missing Age Values
Filled missing values in the Age column using the median age, calculated based on both Pclass and Sex for more accurate imputation.

## Filled Embarked Values
Missing values in the Embarked column were filled using the most frequent value (mode) of the column.

## Encoded Categorical Variables

## Converted Sex into binary values (0/1) using Label Encoding.

## Transformed Embarked using One-Hot Encoding to capture non-ordinal categorical data.

## Detected and Removed Outliers
Boxplots were used to visually identify outliers in numeric columns like Fare and Age. Detected outliers were removed to make the dataset more robust for modeling.


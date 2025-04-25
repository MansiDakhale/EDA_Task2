# EDA_Task2

Exploratory Data Analysis (EDA)
Objective: Understand the structure, relationships, and patterns in the Titanic dataset to guide preprocessing and modeling.

Key Steps Performed:

Summary Statistics

Used .describe() and .info() to understand numerical and categorical distributions, null values, and data types.

Histograms & Boxplots

Visualized distributions and detected outliers in Age, Fare, SibSp, and Parch.

Correlation & Pairplots

Used a heatmap and pairplot to explore inter-feature relationships.

Noted positive correlation between Fare and Survived.

Category-wise Survival Analysis

Survival rates were higher for:

Females (especially in 1st class).

1st class passengers.

Those who paid higher fares.

Feature-Level Observations

Fare is right-skewed and contains outliers.

Age distribution is more centered, but has outliers and gaps.

Sex and Pclass show strong influence on survival
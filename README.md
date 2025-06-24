# Task-2
This notebook performs a complete Exploratory Data Analysis (EDA) on the Titanic dataset to understand patterns, relationships, and key features influencing passenger survival.
The goal of this EDA is to:
-> Understand the data using descriptive statistics
-> Use visualizations to uncover insights and trends
-> Identify and engineer key features useful for modeling.
keypoints:-
 Summary Statistics: Computed mean, median, standard deviation, skewness, and kurtosis for all numerical features
 Histograms & Boxplots:	Visualized distribution and outliers for numeric variables like Age, Fare, etc.
 Categorical Analysis:	Explored survival rates across Sex, Pclass, and Embarked using countplots and barplots 
 Correlation  Matrix:	Created heatmap to assess linear relationships among numeric features
 Pairplot:	Visualized grouped relationships with Survived using scatter and KDE plots
 Anomaly Detection:	Spotted unusually high fares and travel patterns through sorting and boxplots
 Feature Engineering:	Added FamilySize, FareBand, AgeGroup, and FamilyType for deeper insights
 Inference:	Derived meaningful insights and trends to guide future feature selection and modeling
--> Notable Insights :
1) Females and 1st class passengers had significantly higher survival rates
2) Children and small families survived more than solo travelers or large groups
3) Higher fares were correlated with survival due to better class/treatment.
--> Output:
EDA insights ready for machine learning modeling.
Cleaned & enhanced Titanic dataset (df) with new features.


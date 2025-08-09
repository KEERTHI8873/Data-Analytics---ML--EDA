Exploratory Data Analysis (EDA) – Iris Dataset 

Exploratory Data Analysis (EDA) is the heart of understanding our dataset before diving into model building. For the Iris dataset, we focused on visualizing patterns, spotting trends, and understanding feature relationships that help in classification tasks.

1. Understanding the Dataset 
Dataset Size: 150 rows × 5 columns

Features:

Sepal Length (cm)

Sepal Width (cm)

Petal Length (cm)

Petal Width (cm)

Species (Target Variable) – Iris-setosa, Iris-versicolor, Iris-virginica

2. Data Quality Checks 
Null Values: Checked for missing data → None found.

Duplicates: Removed if any (ensures clean data).

Data Types: Verified numerical and categorical columns for accuracy.

3. Statistical Summary 
Using df.describe() we observed:

Mean & Median to understand central tendency.

Min & Max for range of values.

Standard Deviation for spread of features.

Key Insights:

Petal length and petal width show high variation across species, making them great predictors.

Sepal width has the widest range and slightly skewed distribution.

4. Data Visualization 
a) Univariate Analysis (One Feature at a Time)
Histograms: Showed feature distributions for each species.

Boxplots: Revealed outliers, especially in sepal width.

b) Bivariate Analysis (Two Features Together)
Scatter Plots: Petal length vs. petal width gave clear separation between species.

Pairplot (Seaborn): Allowed us to view all feature relationships at once.

c) Multivariate Insights
Correlation Heatmap: Showed strong positive correlation between petal length and petal width.

Violin Plots: Displayed distribution and density differences per species in an aesthetic way.

5. Class Separability Observation 
Iris-setosa: Well-separated from the other two species in petal measurements.

Iris-versicolor & Iris-virginica: Some overlap but still separable through feature combinations.

6. Outcome of EDA 
Identified petal features as the strongest predictors.

Discovered that sepal features have partial overlap between species.

Confirmed balanced dataset (equal samples for each species).

Visual Storytelling Tools Used:

Matplotlib → For simple plots.

Seaborn → For stylish statistical plots.

Heatmaps → For correlation insights.

Pairplots → For overall relationship mapping.

📌 This EDA provided the foundation for building an accurate classification model, as we now understand which features carry the most predictive power.
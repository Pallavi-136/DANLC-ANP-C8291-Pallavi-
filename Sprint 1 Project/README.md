# Wine Quality Prediction

*Predicting Excellence: Unlocking the Secrets of Fine Wine*

Wine analysis and prediction have long been a fascinating field, combining art, science, and tradition. With the increasing demand for high-quality wines, accurate prediction models can significantly impact the industry. This project leverages machine learning algorithms to predict wine quality, exploring the complex relationships between physicochemical properties and sensory evaluations.

# Abstract

Predicting the quality of wine using machine learning algorithms for regression analysis, data visualizations, and data analysis. This project aims to develop an automatic predictive system to support wine certification, reducing subjectivity and improving accuracy.

# Dataset

The dataset used is related to red and white variants of the Portuguese "Vinho Verde" wine, available on the UCI Machine Learning Repository.

# Features

1. Fixed Acidity
2. Volatile Acidity
3. Citric Acid
4. Residual Sugar
5. Chlorides
6. Free Sulfur Dioxide
7. Total Sulfur Dioxide
8. Density
9. pH
10. Sulphates
11. Alcohol

# Target Variable

1. Quality (score between 0 and 10)

# Algorithm Applied

Random Forest Classifier

# Conclusion

The analysis reveals that good quality wines have:

- Higher levels of alcohol
- Lower volatile acidity
- Higher levels of sulphates
- Higher levels of residual sugar

# Plots demonstrate:

- Quality is high when volatile acidity is low
- Quality is high when citric acid is high
- Quality is high when chlorides are low
- Quality is high when sulphates are high
- Quality is high when alcohol is high

# Accuracy

Maximum accuracy achieved: 92.8125% using Random Forest Classifier

# Classification

Wines with quality score 7 or higher are classified as 'Good Quality Wine/1', others as 'Bad Quality Wine/0'

# Acknowledgement

This dataset is available on the UCI Machine Learning Repository:- 
https://archive.ics.uci.edu/ml/datasets/wine+quality

# References

- Benjamin, B.A., & Podolny, J.M. (1999). Status, quality, and social order in the California wine industry.
- Cicchetti, D.V. (2004a). Who won the 1976 blind tasting of French Bordeaux and U.S. cabernets?
- Cicchetti, D.V. (2004b). On designing experiments and analysing data to assess the reliability and accuracy of blind wine tastings.
- Cicchetti, D.V. (2006). The Paris 1976 wine tastings revisited once more.
- Hulkower, N. (2009). The judgment of Paris according to Borda.
- Schnabel, H., & Storchmann, K. (2010). Prices as quality signals: evidence from the wine market.

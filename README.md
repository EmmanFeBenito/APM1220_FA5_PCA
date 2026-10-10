## Name:

Emmanuel Fe Benito

Aldrin Tupas

## Section:

APM1220 Sec2

## FA5

## **Dataset source:** 
Helliwell, J. F., Layard, R., Sachs, J. D., De Neve, J.-E., Aknin, L. B., & Wang, S. (Eds.). *World Happiness Report 2021*. Sustainable Development Solutions Network. The CSV was obtained from a dataset mirror.

## PCA Analysis Description

This assessment applies Principal Component Analysis (PCA) to the World Happiness Report 2021 dataset to find out whether seven correlated well-being variables can be summarized by fewer components. The analysis covers 149 countries and uses Ladder Score, Logged GDP per capita, Social Support, Healthy Life Expectancy, Freedom to Make Life Choices, Generosity and Perceptions of Corruption. Country name and regional indicator were excluded.

The variables were standardized because they are measured on different scales. PCA was then performed through the eigen-decomposition of the correlation matrix, using Python (pandas, NumPy, scikit-learn, seaborn and matplotlib).


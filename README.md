# Air-Pollution-Clustering-Analysis
This project applies data imputation and clustering techniques to air pollutant data (2011–2020, Sebokeng) to identify distinct pollution patterns.

Project Overview

Goal: Group air quality data into meaningful clusters to better understand dominant pollution patterns.

1.Techniques Used:

-Missing value imputation (multivariate imputation)

-Exploratory Data Analysis (EDA)

-K-means clustering

-Visualization of pollutant distributions before & after imputation

2.Data Preprocessing

-Missing values were imputed using multivariate.

-Distributions were visualized before vs after imputation to assess the impact.

3.Clustering Results

The K-means algorithm identified 2 distinct clusters in the dataset:

-Particulate-dominated → higher PM2.5 & PM10, moderate O₃
-Ozone-influenced → elevated O₃, lower particulates

4.Key Visualizations

-Distribution plots of pollutants before vs after imputation

-Cluster centroids comparison

5.Conclusion

Cluster 0 highlights particulate-heavy pollution events (linked to traffic, combustion, dust).

Cluster 1 is ozone-driven, likely due to photochemical reactions in the atmosphere.

The clustering successfully revealed distinct pollution regimes in Sebokeng.

6.Tools used:
-Pandas, numpy, matplotlib, seaborn, scikit-learn)

-Jupyter Notebook

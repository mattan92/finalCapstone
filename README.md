# finalCapstone
This repository contains the Final Capstone Project from HyperionDev

Using the US arrests dataset obtained from Kaggle challenge (https://www.kaggle.com/kurohana/usarrets), this capstone project involves the production of a detailed PCA report.

The dataset contains statistics, in arrests per 100,000 residents, for assault, murder, and rape in each of the 50 US states in 1973. Also given is the percent of the population living in urban areas.

The following steps are performed:
- Initialisation: importing all required packages for data processing, visualisation and clustering analysis, followed by loading the data into a Pandas dataframe
- Pre-processing: initial descriptive statistics, checking for null data, and describing the datatypes to allow for appropriate data analysis later
- Visualisation:
  - Histograms to determine frequency distributions
  - Pairplots to visualise any clear correlations
  - Heatmap to quantify the correlated fields
- Clustering:
  - PCA analysis - visualised using a scatterplot
  - Feature importance, cumulative variance and Scree plot to determine number of components to use in the analysis
  - Dendrogram clustering using complete linkage - generates 4 clusters
  - K-means clustering using 4 clusters
- Analysis of clustering data to draw conclusions regarding the similarities and differences inter- and intra-group

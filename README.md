# finalCapstone
This repository contains the Final Capstone Project from HyperionDev

Table of Contents:
- Description of project
- Steps taken in project
- Installation
- Usage
- Credits

Description of Project:
Using the US arrests dataset obtained from Kaggle challenge (https://www.kaggle.com/kurohana/usarrets), this capstone project involves the production of a detailed PCA report.

The dataset contains statistics, in arrests per 100,000 residents, for assault, murder, and rape in each of the 50 US states in 1973. Also given is the percent of the population living in urban areas.

Steps taken in Project:
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

Installation:
Download the file Compulsory Task.ipynb from the master branch.

Usage:
- Local usage: open the Jupyter notebook file with an appropriate code editor e.g. Visual Studio Code.
- Web-browser based Jupyter notebook - please ensure that you have installed the required software before trying this route:
  - Navigate to the folder containing the file using the command line (Windows) or terminal (MacOS/Linux)
  - Then type jupyter notebook into the terminal
  - This should open a web browser that will allow you to open the notebook file directly in the web browser
  - Run the notebook in the web browser to view all analysis and visualisations

Credits:
This analysis was performed by myself as part of the HyperionDev Data Science bootcamp which I participated in from November 2022 to January 2023

# Cab Data Analysis: Streamlining Transportation

This repository contains code and resources for analyzing Uber and Lyft ride-sharing data to uncover pricing strategies, identify patterns, and propose actionable insights. By leveraging data visualization, unsupervised learning, and predictive modeling, this project aims to enhance understanding and forecasting in the transportation industry.

## Project Overview

- **Dataset:** Kaggle data of Uber and Lyft trips (Nov 26–Dec 18, 2018).
- **Objective:** Explore pricing strategies, feature correlations, and predictive modeling of ride costs.
- **Key Techniques:**
  - Data Cleaning and Preprocessing
  - Exploratory Data Analysis (EDA)
  - Dimensionality Reduction (PCA, UMAP, t-SNE)
  - Clustering (K-Means, GMM)
  - Predictive Modeling (Logistic Regression, Decision Trees, Random Forest)
  - Cross-Validation for performance assessment

## File Structure

- `DPAProject.ipynb`: Main Jupyter Notebook with code and analysis.
- `rideshare_data_with_all_analysis.csv`: Processed dataset with clustering results.
- `kmeans_plot.png`, `gmm_plot.png`, `pca_plot.png`: Visualization outputs.
- `kmeans_cluster_stats.csv`, `gmm_cluster_stats.csv`: Cluster statistics.

## Key Insights

1. **Patterns Identified:**
   - Correlation between ride features and pricing.
   - Effects of weather and time on ride costs.
   - Clusters revealing ride preferences and trends.

2. **Modeling Results:**
   - Logistic Regression achieved the highest accuracy (74%).
   - Recommendations for enhancing predictive accuracy:
     - Feature engineering
     - Addressing class imbalance with SMOTE
     - Advanced models like Gradient Boosting

## Planned Future Work

- Integrating traffic and real-time conditions.
- Optimizing feature selection for Random Forests.
- Testing additional file formats (e.g., Parquet, Avro) for efficiency.

## Authors

- **Pratima Yadav**: [pyadav6@hawk.iit.edu](mailto:pyadav6@hawk.iit.edu)
- **Shreya Padaganur**: [spadaganur@hawk.iit.edu](mailto:spadaganur@hawk.iit.edu)
- **Chinmay Chaudhari**: [cchaudhari1@hawk.iit.edu](mailto:cchaudhari1@hawk.iit.edu)
- **Rafay Danish**: [mdanish@hawk.iit.edu](mailto:mdanish@hawk.iit.edu)

**Professor:** Oleksandr Narykov, Illinois Institute of Technology  
**Course:** CSP 571 - Data Preparation and Analysis

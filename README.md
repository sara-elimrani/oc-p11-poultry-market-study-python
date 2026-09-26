# International Poultry Market Study with Python

This project was completed as part of the OpenClassrooms Data Analyst training program.

The objective was to identify attractive international markets for a French poultry company by combining food supply, demographic, economic, urbanization, and political stability indicators.

---

## Project Context

The study evaluates countries for a potential export strategy. It enriches FAO food-balance data with World Bank and governance indicators, then applies multivariate analysis and clustering to reveal comparable market profiles.

The analysis is split into two notebooks:

1. Data preparation, enrichment, and exploratory analysis
2. PCA, hierarchical clustering, K-Means, and market prioritization

---

## Objectives

- Prepare and combine multiple international open-data sources
- Measure the place of poultry in national food consumption
- Integrate economic, demographic, urbanization, and political indicators
- Reduce dimensionality with Principal Component Analysis
- Segment countries with hierarchical clustering and K-Means
- Build a prioritization score for export opportunities

---

## Data Sources

- FAO food availability and population data
- World Bank GDP per capita data
- World Bank urban population indicators
- Worldwide Governance Indicators for political stability

---

## Tools and Technologies

- Python
- pandas and NumPy
- Matplotlib, Seaborn, and Plotly
- scikit-learn
- SciPy
- Jupyter Notebook / Google Colab

---

## Analytical Methods

- Data cleaning, reshaping, and multi-source joins
- Poultry consumption ratios by calories and quantity
- Outlier detection with the IQR method
- Standardization with `StandardScaler`
- Principal Component Analysis (PCA)
- Hierarchical clustering and dendrogram analysis
- K-Means clustering
- Silhouette score and cluster profiling
- Multi-criteria export opportunity scoring

---

## Key Results

- The first three principal components retain approximately 75.8% of total variance
- A three-cluster solution was selected using the dendrogram and elbow method
- Cluster 1 groups 52 developed markets with high purchasing power, political stability, and poultry consumption
- Cluster 2 groups 22 large, mature, and highly competitive poultry markets
- Cluster 0 groups 67 less-developed markets with lower production, consumption, and purchasing power
- A final scoring model ranks priority countries using GDP, stability, consumption, imports, and local production

---

## Repository Structure

```text
notebooks/
  01_data_preparation_eda.ipynb
  02_pca_clustering.ipynb
presentation/
  project_presentation.pptx
```

The notebooks contain executed outputs. To rerun them, provide the original project datasets and update the data paths used in the loading cells.

---

## Skills Developed

- Multi-source data preparation
- Market research with open data
- PCA and unsupervised learning
- Country segmentation
- PESTEL-informed indicator selection
- Business recommendation and data storytelling

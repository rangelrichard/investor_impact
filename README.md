# San Diego Housing Market Analysis
### Project Overview
This project analyzes the relationship between institutional investor activity and housing price appreciation across San Diego zip codes. Using data from Redfin, Zillow, and demographic sources, the analysis examines how investor activity correlates with housing price movements at the zip code level, with a particular focus on whether areas with higher investor activity experience faster price appreciation.

### Key Findings

- Investors tend to target higher-income neighborhoods in San Diego
- A moderate negative correlation exists between investor activity and housing price appreciation
- When accounting for median income and sales volume through a weighted model, this negative relationship becomes stronger and more statistically significant
- Clustering analysis identified distinct neighborhood patterns based on investor activity, price appreciation, and income levels

### Methodology
The analysis employs several data science techniques:

- Exploratory Data Analysis (EDA) to understand variable distributions and relationships
- K-means clustering to identify natural groupings of zip codes
- Correlation analysis to quantify relationships between variables
- Weighted average modeling to incorporate economic contextual factors
- Geographic visualization to identify spatial patterns

### Data Sources

- Redfin Investor Activity Data
- Zillow Home Value Index (ZHVI)
- Demographic and income data

### Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Geospatial analysis (GeoPandas)
- Machine learning techniques (scikit-learn)
- Statistical analysis (SciPy)

### Repository Structure
This repository contains a series of Jupyter notebooks that document the progression of the project through various stages:

- `ProjectProposal_groupXXX.ipynb`: Initial project planning and research question formulation
- `DataCheckpoint_groupXXX.ipynb`: Data acquisition and preliminary processing
- `EDACheckpoint_groupXXX.ipynb`: In-depth exploratory data analysis
- `FinalProject_groupXXX.ipynb`: Complete analysis and findings

### Note
This project was completed as part of a data science course. The analysis and findings represent academic research and should not be used as the sole basis for investment decisions without additional research.

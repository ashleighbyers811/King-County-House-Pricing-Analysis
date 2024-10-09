# King-County-House-Pricing-Analysis

## Project Summary
This repository presents an exploratory analysis of housing prices in King County, WA, aimed at identifying key factors influencing house prices. The analysis seeks to answer essential questions relevant to real estate agents operating in King County, enabling them to price properties accurately and effectively.

## Key Questions
- What factors have the strongest correlation with house prices?
- How does the number of bedrooms or bathrooms influence the sale price of homes?
- Which neighborhoods in King County have the highest average home price?
- Does the year of renovation significantly impact property values in King County?
- How does the proximity to the waterfront impact property values in King County?
- Is there a difference in pricing trends between homes with high ‘view’ scores versus those with lower scores?

## Folders
Description of folder contents are as follows:

- 01 Project Management: Contains the project brief and related documentation.
- 02 Data: Includes two subfolders: 
  - 'Original Data': Original datasets.
  - 'Prepared Data': Cleaned data ready for analysis.
- 03 Scripts: Python code for the analysis, executed using Jupyter notebooks.
- 04 Analysis: Contains the 'Visualizations' subfolder with any python created visualizations used for exploratory analysis and explaining insights.
- 05 Sent to Client: Final Tableau presentation.

## Code Overview
Code was written in Python and executed in Jupyter notebooks.

Utilizes the following libraries:
- Pandas: For data manipulation and analysis
- NumPy: For numerical operations and array handling
- OS: For interacting with the operating system, including file and directory operations
- Matplotlib.pyplot: For creating static, interactive, and animated visualizations
- Matplotlib.ticker.FuncFormatter: For custom formatting of axis ticks in plots
- Seaborn: For statistical data visualization and creating informative, attractive graphics
- Statsmodels.api: For estimating and testing statistical models, including regression analysis.
- Folium: For creating interactive maps and visualizing geospatial data.
- Sklearn: For implementing machine learning algorithms and preprocessing data.
   - from sklearn.cluster import KMeans: For performing K-means clustering on the dataset.
   - from sklearn.model_selection import train_test_split: For splitting the dataset into training and testing sets.
   - from sklearn.linear_model import LinearRegression: For implementing linear regression analysis.
   - from sklearn.metrics import mean_squared_error, r2_score: For evaluating the performance of regression models.
   - from sklearn.preprocessing import StandardScaler: For standardizing features by removing the mean and scaling to unit variance.

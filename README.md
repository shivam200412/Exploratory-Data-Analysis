# **Exploratory Data Analysis**

Exploratory Data Analysis (EDA) is the process of analyzing datasets to summarize their main characteristics, often with visualizations. It helps in understanding the data structure, identifying patterns, spotting anomalies, and forming hypotheses for further analysis.

## Steps in Exploratory Data Analysis

1.Understand the Dataset  
  - Import the data using tools like pandas in Python.  
  - Check the dataset dimensions (shape), column names, and data types.  
  - Preview the data using .head() or .tail().  

2.Clean the Data  
  - Handle missing values (isnull(), dropna(), fillna()).  
  - Remove duplicates.  
  - Handle inconsistent data entries (e.g., fixing typos or formatting issues).  
    
3.Descriptive Statistics  
  - Use .describe() to get basic statistical summaries like mean, median, and standard deviation.  
  - Identify data distributions using histograms or summary tables.  
    
4.Univariate Analysis  
  - For numerical data: Use histograms, boxplots, and density plots.  
  - For categorical data: Use bar plots and pie charts.  

5.Bivariate Analysis  
  - Numerical vs. Numerical: Use scatter plots, correlation matrices, and pair plots.  
  - Numerical vs. Categorical: Use boxplots or violin plots.  
  - Categorical vs. Categorical: Use stacked bar plots or heatmaps.  
    
6.Multivariate Analysis  
  - Analyze the interaction of multiple variables.  
  - Use techniques like pair plots, parallel coordinate plots, or clustering.  

7.Data Transformation  
  - Apply scaling or normalization.  
  - Create new derived features, if needed.  
  - Log transformation for skewed data.  

8.Identify Outliers  
  - Use box plots or z-scores to detect and handle outliers.  
  - Visualize Relationships  



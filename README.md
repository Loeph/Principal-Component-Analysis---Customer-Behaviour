Customer Segmentation Using Principal Component Analysis (PCA)

This project applies Principal Component Analysis (PCA) to customer purchasing and behavioural data to identify underlying patterns and reduce dataset dimensionality.

The analysis explores relationships between customer spending habits, purchasing channels, income, and engagement metrics to better understand customer behaviour and support segmentation analysis.

Objectives
- Standardise and preprocess customer data
- Analyse correlations between customer behaviour variables
- Reduce dimensionality using PCA
- Evaluate explained variance using scree plots
- Interpret principal component loadings
- Apply Varimax rotation for improved component interpretability

Technologies Used
- R
- corrplot
- psych
- PCA (`prcomp`)
- Varimax rotation

Variables Analysed
The analysis includes variables related to:
- Customer age
- Annual income
- Spending on:
  - Meat
  - Wine
  - Organic food
  - Wellness products
  - Treats
  - Luxury goods
- Online, store, and catalogue purchases
- Promotional purchases
- Website visits
- Customer loyalty/years with company

Methods
The project includes:
- Data standardisation using `scale()`
- Correlation analysis and visualisation
- Principal Component Analysis (PCA)
- Scree plot analysis
- Cumulative variance evaluation
- Principal component interpretation
- Varimax rotation using the `psych` package

Key Findings
- PCA successfully reduced the dimensionality of the dataset while preserving key behavioural patterns.
- Correlation analysis revealed relationships between customer spending categories and purchasing behaviour.
- The first three principal components captured the majority of variance within the dataset and were selected for further analysis.
- Varimax rotation improved the interpretability of component loadings by producing clearer variable groupings.
- Customer purchasing behaviour appeared to cluster around:
  - High-value/luxury spending
  - Online purchasing activity
  - Promotional engagement
  - General spending intensity

## Project Overview (Unsupervised Learning)

In this challenge, I will use my kneowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

The project workflow includes the following major steps:

1. **Data Preparation**:
   - Loading the dataset and performing data summary statistics.
   - Normalizing data using StandardScaler from scikit-learn.

2. **Finding Optimal k**:
   - Employing the elbow method to find the best value for k using both original and PCA data.

3. **Clustering Cryptocurrencies**:
   - Using K-means clustering with the best k-value obtained to group cryptocurrencies.
   - Visualizing clusters using scatter plots.

4. **PCA Analysis**:
   - Reducing features to three principal components and evaluating explained variance.

5. **Comparing Results**:
   - Comparing the impact of using fewer features for K-means clustering.




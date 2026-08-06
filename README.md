# Product-Segmentation-Case-Study/
This is a data analysis project using unsupervised learning model to cluster customers based on their income and spending behavior.


#  Files in this Repository
**Mall_Customers dataset.xlsx**: A dataset of customers with columns of age, sex, income, and spending score (from 0-100).
**ProductSegmentation (1).ipynb**: Main Jupyter Notebook containing the full analysis.

# Analysis Workflow
1. **Exploratory Data Analysis (EDA)**: Basic information of the dataset, including mean, standard deviation, maximum, and minimum.
2. **Data Distribution Check**: Building boxplots and histograms to observe the data, checking for skewness or outliers.
3. **Category Relationships**: Using line and bar charts to observe the relation between each category.
4. **Elbow Method**: Defining a range of cluster numbers to try (from 1 up to 8 clusters) and plotting the elbow curve.
5. **Silhouette Analysis**: Plotting silhouette scores for different values of $k$ to find the most optimal K-Means.
6. **Labeling & Highlighting**: Adding labels for each column and highlighting the maximum values.
7. **Cluster Distribution**: Creating boxplots to visualize the distribution of scaled numerical variables across different K-Means clusters.
8. **Insights**: The y-axis shows the distribution of the data, and the boxplots show the relation of mean values to each cluster in each category.


# Business Insights
**Cluster 0 (Older Age, Average Income, Medium Spenders)**:
Focus on building loyalty, emphasizing reliability and comfort value. Campaigns should use traditional channels, and products can highlight practical durability, stability, and family-oriented benefits.

**Cluster 1 (Middle Age, High Income, Low Spenders)**:
Focus on exclusivity, prestige, unique features, and the investment or functional value of products rather than price. Introduce premium, high-quality, or durable goods that appeal to a pragmatic yet affluent mindset.

**Cluster 2 (Younger Age, Moderate to High Income, Highest Spenders)**:
Focus on continuous innovation by introducing high-end, trendy, and fashionable products. Since they have high spending enthusiasm, marketing campaigns can leverage digital channels, social media, and experiential engagement.

**Cluster 3 (Middle-Aged to Senior, Lowest Income, Low Spenders)**:
Focus on value proposition, affordability, and essential utility. Promote through clear price comparisons, cost-effectiveness, and practical discounts to attract budget-conscious consumers.

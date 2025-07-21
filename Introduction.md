# Clustering Happiness Country Using KMeans

This project involves the application of K-Means Clustering, an unsupervised machine learning algorithm, to analyze and categorize countries based on the World Happiness Report 2015 dataset.
## Brief Description of Each Variable
The dataset consists of the following key variables:
1. **Country**, The name of the country being evaluated.
2. **Region**, The broader geographical or economic region to which the country belongs (e.g., Western Europe, Sub-Saharan Africa).
3. **Happiness Rank**, The overall rank of the country in terms of happiness, based on the Happiness Score.
4. **Happiness Score**, A composite score (typically from 0 to 10) that reflects the average reported happiness of people in each country.
5. **Standard Error**, The margin of error in the Happiness Score, indicating the uncertainty of the measurement.
6. **Economy (GDP per Capita)**, A measure of a country’s economic output per person. It reflects how much income contributes to a country’s happiness.
7. **Family**, Also referred to as social support, this indicates whether people have someone they can rely on in times of trouble.
8. **Health (Life Expectancy)**, This reflects the average healthy lifespan of a country’s citizens, contributing to overall well-being.
9. **Freedom**, The extent to which people feel free to make life choices.
10. **Trust (Government Corruption)**, This measures the level of trust people have in public institutions, and how common corruption is perceived to be.
11. **Generosity**, Based on how charitable people are, often measured by recent donations to others.
12. **Dystopia Residual**, A calculated baseline representing the hypothetical "worst possible life," used to understand how much better a country is doing compared to that baseline.

# The K-Means Clustering
This project applies K-Means Clustering, a widely used unsupervised machine learning algorithm, to analyze and group countries from the World Happiness Report 2015 dataset. By using clustering techniques, the project aims to identify natural groupings among countries that exhibit similar happiness profiles.

**The Using of K-Means Clustering**

The main purpose of this project is to discover hidden patterns and structures within the dataset by grouping countries into clusters based on the similarity of their happiness-related features. K-Means allows for dimensionality reduction in interpretation, providing insights into how different countries compare to one another in terms of well-being. These findings can be used to inform policy recommendations, regional comparisons, and further sociological or economic research.
**The Main Insight**
This project addresses the challenge of analyzing high-dimensional, unlabeled data. The World Happiness dataset does not come with predefined categories, making it difficult to draw conclusions about similarities or differences across countries. K-Means Clustering solves this by partitioning the data into k groups, where each country is assigned to the cluster with the nearest mean value of all selected indicators. This approach enables:
- Easier comparative analysis between groups of countries,
- Identification of shared characteristics within clusters,

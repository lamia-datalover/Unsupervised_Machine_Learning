
# Situation
Using the Mall Customers dataset, I conducted a study on customer behavior, particularly focusing on their spending score ranging from 1 to 100. My objective was to discern the factors influencing their distinct behavior categories: low, moderate, and high spending scores.
# Task
Studying the spending score of customers in relation to their age and annual income.
# Actions 
Initially, I conducted preprocessing using the Sklearn library, eliminating redundant columns. Employing Elbow and Silhouette techniques, I determined the optimal number of clusters. Subsequently, I trained a KMeans model with the identified ideal number of clusters, K.

Following this, I performed Exploratory Data Analysis (EDA) to understand the distribution of ages, annual incomes, and gender within the dataset. I then visualized relationships between the spending score and age, as well as between the spending score and annual income, using scatter plots.

Finally, I synthesized all this information into a comprehensive 3D scatter plot for a visual summary of the dataset's key insights.
# Results
Thanks to the KMeans model and thorough EDA, I observed distinct patterns in the spending scores, categorizing them into three types: low, moderate, and high. Surprisingly, the low spending score category includes individuals with high incomes, possibly indicating their possession of all necessities and only fewer additional needs . Conversely, the high spending score group is largely comprised of young individuals with an annual income exceeding 60K in average. The moderate score category seems to involve individuals with an average income of 50K.

If you're interested in more detailed insights, feel free to review the code. I've extensively commented on it, providing comprehensive and detailed insights into the findings. 

## Acknowledgements

 - [This project was proposed by jedha bootcamp during my training in data science and data engineering. ](https://www.jedha.co/formations/formation-data-scientist)



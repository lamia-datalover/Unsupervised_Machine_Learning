
# Situation
Using the load_digits dataset from sklearn library , I had to group non labeled data .
# Task
Grouping images of the same type  ( we have number images that goes from 0 to 9).
# Actions 

Initially, I needed to understand the different components of the dataset. Then, I trained a KMeans model using 10 clusters, but initially, the model did not perform well. In fact, the images did not match the labels. As a result, I had to address this issue by identifying the most frequent number within each cluster (using the mode) and assigning that number's label to the entire cluster.

Following this adjustment, the labels were corrected and aligned appropriately with the clusters.
# Results

The majority of the images were correctly labeled; however, there were some mislabeled images that I showcased in the final confusion matrix.

This project demonstrates that KMeans can also be utilized to cluster unlabeled data effectively.

If you're interested in delving deeper into such projects or reviewing the code for more details, please let me know.

## Acknowledgements

 - [This project was proposed by jedha bootcamp during my training in data science and data engineering. ](https://www.jedha.co/formations/formation-data-scientist)



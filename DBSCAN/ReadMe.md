
# Situation
Using the data from 911.csv, I have compiled recommendations for a US county to safeguard its citizens against common issues that could have a negative impact on them.
# Task
To know the main cases that the US-county are suffering from.
# Actions 
Initially, I sampled a subset of the dataset and preprocessed it by applying normalization to scale numerical features and one-hot encoding for categorical features. Next, I employed the DBSCAN model to group similar rows within the dataset, representing issues prevalent in the US county that pose a threat to the peace and well-being of its population. Using an epsilon value of 0.2 and a min_samples=100, I identified 11 clusters.
# Results
The project aimed to identify problems that threaten the well-being of a US county's population. The objective was achieved; major issues identified include:

'EMS: SUBJECT IN PAIN', 
'Traffic: ROAD OBSTRUCTION -', 
'Traffic: VEHICLE ACCIDENT -', 
'Fire: FIRE ALARM', 
'EMS: FALL VICTIM', 
'EMS: RESPIRATORY EMERGENCY', 
'EMS: VEHICLE ACCIDENT', 
'Traffic: DISABLED VEHICLE -', 
'EMS: CARDIAC EMERGENCY'.

If interested, you can view the map displaying the origin of these issues in the provided notebook.

## Acknowledgements

 - [This project was proposed by jedha bootcamp during my training in data science and data engineering. ](https://www.jedha.co/formations/formation-data-scientist)



# Situation:
The goal of this project is to cancell the noise of images .
# Actions :
I first familiarized myself with the information present in the dataset by displaying some statistical information. Next, I examined the different images in the dataset to assess their noise levels. 
Following this, I split the data into a training set and a test set and trained an SVM model for image classification. The objective of this step was to compare the results of the model, including the training time and its score.

Right after this step, I normalized the data for use with a PCA model. 
Subsequently, I displayed the data and the SVM model's score. 
The results were interesting: the images were not as noisy as before, the model didn't take as long as the initial training, and the score improved!
# Results :
Thanks to the use of PCA, the images are no longer as noisy as they were, the training time for the model decreased, and the score improved!

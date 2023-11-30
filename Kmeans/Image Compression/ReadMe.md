
# Situation
Using the load_sample_image library from sklearn , I had to compress the image china.png  .
# Task
Compressing china.png using MiniBatchkmeans.
# Actions 
Initially, I had to divide each pixel by 255 to not alter the contrast of the image . Then I reshaped it to 2 dimensions because the MiniBatchkmeans can not be used on an image having 3 dimensions.
After that I assigned the centroid of the cluster that each sample is predicted to belong to as its associated color in the new_colors array.
Put in mid that the centroid color of each cluster is assigned to the corresponding samples based on their predicted cluster labels. This step creates a palette of colors representing the image.
After assigning the cluster centroids as the new colors, the reshaped image (2D) is transformed back to its original dimensions (3D). The new assigned colors are then mapped to their respective pixels, essentially compressing the image by using a reduced set of colors determined by the clustering process.
# Results
The image compression has been successfully completed. Please feel free to review the notebook to examine the code and the results.

## Acknowledgements
 - [This project was proposed by jedha bootcamp during my training in data science and data engineering. ](https://www.jedha.co/formations/formation-data-scientist)



# PCA-on-clusters

For this project, I used a dataset concerning customers of a bank with credit accounts. In this project, I first dealt with some missing values in the 'Minimum Payments' and 'Credit Limit' columns by setting the missing values to 0. My reasoning behind doing so is that the NA did not signify that there is no data, but that those specific customers do not have a history of minimum payments or a known credit limit. Next, I performed K-means clustering on the dataset using a range of K-values from 2-20 and evaluated the best K-value by using the elbow and silhouette methods. 

Then, I used PCA to transform the data and saw that I am able to explain 95% of the variance in data only using 6 of the new principle components. Next, I selected those 6 components and used them in K-means clustering with the found optimal K-value to see how PCA is able to achieve similar and sometimes better performance with using fewer variables.

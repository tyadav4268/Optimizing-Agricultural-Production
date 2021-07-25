"# Optimizing-Agricultural-Production"

A Machine Learning Model to suggest the most suitable Crops to grow based on the available Climatic and Soil conditions.
- In this project, I have created different python fuction to take out meaningful and interesting insights from our data.
- Used distplot of seaborn library to see the trend in soil and climatic conditions requirements of different crops.
- Used elbow method to find suitable number of clusters in the dataset and using the unsupervised machine learning algorithm
  K-Means clustering I found the dataset can be clustered into 4 clusters and the crop belonging to same cluster need same type of 
  soil and climatic conditions.
- Then using the supervised machine learning algorithm Logistic Regression, a classification algorithm, built a predictive model 
  to predict the best crop to be grown in the given soil and climatic conditions.
- For validation, I used confusion matrix as well as classification report from the sklearn.metrics to find out the values for
  precision and recall for the model.
- The mode has high precision and recall.

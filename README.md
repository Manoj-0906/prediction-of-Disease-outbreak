# Prediction-of-Disease-outbreak
Prediction of disease outbreak by the method of spreading using Machine Learning
The process of identifying, assessing, and managing people who have been exposed to a disease which may causes a outbreak and may cause a mass outbreak and to prevent transmission.
People who may have been exposed to the virus from affected countries/people are to be traced and monitored for certain number of days and if they are not monitored and who cthey are in contact, the virus may spread even more, which causes a massive outbreak and loss of many innocent lives.
This works for any person who had contact with patients under treatment for suspected, probable or confirmed case of that certain disease. Generally, Any person who provided care for the patient suspected or confirmed with the disease, including a health care worker or family member. The sprerad can be contained with proper measures and with some help of AI and ML.
Building a Machine Learning model based on various parameters such as longitude and latitude.
Feature engineering implementation is the heart of this model.

# Dataset
Kaggle: spread of disease dataset(json file)
Machine Learning implementation based on multiple classifier algorithm implementations and correlation.

 # In this project, what I did was
->Taken the dataset and checked for Null Values
->Did Exploratory Data Analysis and Visualized the Considerable Factors and Finded the correlation

# For training my model, I used DBSCAN clustering
DBSCAN is a density-based clustering algorithm that groups data points that are closely packed together and marks outliers as noise based on their density in the feature space. It  identifies clusters as dense regions in the data space, separated by areas of lower density.

Unlike K-Means or hierarchical clustering, which assume clusters are compact and spherical, DBSCAN excels in handling real-world data irregularities such as:

Arbitrary-Shaped Clusters: Clusters can take any shape, not just circular or convex.
Noise and Outliers: It effectively identifies and handles noise points without assigning them to any cluster.
->Showed the clusters predicted by my model.
->And hence, Plotted the spread of disease using contact tracing curve.
->Finally, Predicted and showed the infected person through spreading.

# Gratitude
prateekagr21

# References
chatgpt

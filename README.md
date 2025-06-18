##Customer Segmentation Using KMeans Clustering
This project demonstrates a beginner-friendly implementation of KMeans Clustering to group mall customers based on features such as age, income, gender, and spending behavior. It is built using a publicly available mall customer dataset (from Kaggle) as part of a machine learning internship task.

##Dataset
I used a Kaggle dataset in CSV format: Mall Customers Dataset – https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

##Features Used
#To prepare the data, I perform the following operations:
Original Columns	Description
Gender	Encoded as 0 or 1 using LabelEncoder
Age	Customer’s age in years
Annual Income (k$)	Yearly income in thousands of dollars
Spending Score (1–100)	Score assigned by mall based on behavior
The final dataset contains these columns:
Gender (0 or 1)
Age
Annual Income (k$)
Spending Score (1-100)

##Clustering Model
I used KMeans Clustering from the sklearn.cluster module.
Number of clusters: 3

##Visualization
The clusters are visualized using a scatter plot:
X-axis: Annual Income
Y-axis: Spending Score
Color-coded clusters
Matplotlib is used for plotting

##Output


##Libraries Used
Python, pandas, matplotlib, scikit-learn

##Summary
This project is a great example for beginners learning:
Data preprocessing with Label Encoding
Feature selection for clustering
Unsupervised machine learning with KMeans
Visualizing customer segments

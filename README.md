#  Customer Segmentation Using K-Means Clustering
This project implements **K-Means Clustering** to segment customers of a mall based on their behavior and demographics. It helps businesses understand their customer base, target marketing efforts better, and optimize sales strategies. The project is beginner-friendly and focuses on visualizing customer groups using unsupervised machine learning.

## Dataset
I use the popular **Mall Customer Segmentation dataset**, which includes the following features for each customer:
- `CustomerID`: Unique ID for each customer
- `Gender`: Male or Female
- `Age`: Age of the customer
- `Annual Income (k$)`: Estimated income
- `Spending Score (1-100)`: Score assigned based on spending habits
- The dataset is from Kaggle and used in csv format: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

##  Data Preprocessing
Before applying machine learning:
- I check for **missing values** using `isnull().sum()`.
- Since `Gender` is a categorical feature, we use `LabelEncoder()` to convert it to numerical format:
  - Female = 0
  - Male = 1

Final features used for clustering:
- Gender (encoded)
- Age
- Annual Income
- Spending Score

##  Clustering with K-Means
I use **K-Means Clustering** from `sklearn.cluster`. For simplicity, the number of clusters is set to 3

##  Visualization
To make the segmentation visually understandable, we create a 2D scatter plot:
- X-axis: Annual Income (k$)
- Y-axis: Spending Score (1–100)
- Color: Cluster ID
- Each point represents a customer
- Uses matplotlib for plotting

##  Libraries Used
- pandas
- matplotlib
- sklearn (KMeans, LabelEncoder)

## output 
![Image](https://github.com/user-attachments/assets/2abe9299-b541-443f-b720-6c9ffee38c37)



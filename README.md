# Customer Clustering Using K-Means Algorithms
In this project, we analyze a dataset of mall customers to understand their characteristics, preferences, and behaviors. By applying data analysis techniques and clustering algorithms, we aim to identify customer segments based on their shopping patterns and Annual Income.
## Problem Statement
The problem addressed by the Mall Customer Cluster Dataset is to segment customers based on their shopping behavior and demographic information. The dataset aims to answer questions such as:

* Can we identify distinct customer segments or clusters based on their spending patterns?
* What are the key demographic factors that influence customer behavior in the mall?
* How can we develop targeted marketing strategies for different customer segments?
![](https://media.baamboozle.com/uploads/images/231743/1611285225_970520)

## Data Source
You can access and download data from [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python) or get it from me.\
\
The dataset is provided in a CSV (Comma Separated Values) format, where each row represents a customer and each column represents a specific attribute. The dataset includes the following information:
* CustomerID:
    Unique identifier for each customer.
* Gender:
    Gender of the customer (male or female).
* Age:
    Age of the customer.
* Annual Income:
    Annual income of the customer in monetary units.
* Spending Score:
    A score assigned to the customer based on their shopping behavior and spending patterns.
The dataset aims to identify meaningful customer segments or clusters based on their demographic information and spending behavior.

## Solution Approach
The solution approach involves utilizing the Mall Customer Cluster Dataset to segment customers and gain insights into their shopping behavior. The following steps can be followed:

* **Data Loading:** Load the dataset file (dataset.csv) into your preferred programming environment or data analysis tool.

* **Data Preprocessing:** Perform any necessary data cleaning and preprocessing steps, such as handling missing values or outliers, encoding categorical variables (if any), and scaling numerical features.

* **Exploratory Data Analysis:** Explore the dataset by visualizing the distribution of different variables, examining correlations between variables, and identifying any patterns or trends.

* **Feature Selection:** Select relevant features that contribute significantly to customer segmentation and spending behavior, based on exploratory data analysis and domain knowledge.

* **Customer Segmentation:** Apply clustering algorithms such as K-means, hierarchical clustering, or DBSCAN to group customers into distinct segments based on their spending behavior and demographic attributes.

* **Cluster Analysis:** Analyze the characteristics and traits of each customer segment to gain insights into their preferences, needs, and behaviors. Compare the clusters to identify distinct groups and their unique characteristics.
## Clustering 
Clustering based on 2 features: annual income and spending score.\
**Spending and Income Cluster** is the label of data:
![](https://github.com/chinneee/Mall_Clustering_Project/blob/main/Table%20with%20labels.png)
We can clearly see that 5 different clusters have been formed from the data. The **blue cluster** is the customers with the least income and least spending score, similarly, the **green cluster** is the customers with the most income and most spending score.
![](https://github.com/chinneee/Mall_Clustering_Project/blob/main/Spending%20and%20Income%20Cluster.png) 

So, we used K-Means clustering to understand customer data. K-Means is a good clustering algorithm. Almost all the clusters have similar density. It is also fast and efficient in terms of computational cost.

Thanks for reading. I am Trinh Nguyen.

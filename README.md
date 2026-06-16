# Mall Customer Segmentation using K-Means Clustering

## Project Overview

Customer segmentation is an important strategy used by businesses to understand their customers better and provide personalized services. In this project, K-Means Clustering, an unsupervised machine learning algorithm, is used to divide mall customers into different groups based on their purchasing behavior and demographic characteristics.

The analysis helps identify customer segments that can be targeted with specific marketing strategies, ultimately improving customer satisfaction and business performance.

## Problem Statement

Shopping malls often have a large and diverse customer base. Treating all customers in the same way may not be effective for marketing and customer engagement. The objective of this project is to segment customers into meaningful groups based on their characteristics, enabling businesses to understand spending patterns and make informed decisions.

## Objectives

* Explore and understand the mall customer dataset.
* Perform data preprocessing and exploratory data analysis.
* Identify the optimal number of customer clusters.
* Apply the K-Means clustering algorithm.
* Visualize the customer segments.
* Interpret the characteristics of each cluster.

## Dataset

This project uses the Mall Customer Segmentation dataset available on Kaggle.

Dataset Link:
https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

### Dataset Features

* CustomerID – Unique identifier for each customer
* Gender – Gender of the customer
* Age – Age of the customer
* Annual Income (k$) – Annual income of the customer
* Spending Score (1–100) – Score assigned based on customer spending behavior

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Methodology

1. Import the required libraries.
2. Load and explore the dataset.
3. Perform data preprocessing.
4. Conduct Exploratory Data Analysis (EDA).
5. Use the Elbow Method to determine the optimal number of clusters.
6. Train the K-Means clustering model.
7. Visualize the customer segments.
8. Interpret the results and business insights.

## Results

The K-Means algorithm successfully grouped customers into distinct segments based on their annual income and spending score. These segments can help businesses identify high-value customers, understand customer behavior, and design targeted marketing campaigns.

## How to Run the Project

1. Clone this repository or download the notebook.
2. Install the required libraries listed in `requirements.txt`.
3. Download the dataset from Kaggle.
4. Place the dataset file in the working directory.
5. Open the notebook in Google Colab or Jupyter Notebook.
6. Run all cells sequentially to reproduce the analysis and results.

## Repository Structure

* `Mall_Customer_Segmentation.ipynb` – Complete project notebook
* `Mall_Customers.csv` – Dataset
* `README.md` – Project documentation
* `requirements.txt` – Required Python libraries
* `visuals/` – Graphs and visualizations generated during analysis

## Business Insights

* High-income customers with high spending scores can be targeted with loyalty programs and premium offers.
* Customers with high income but low spending may require personalized promotions to increase engagement.
* Understanding customer segments allows businesses to allocate resources more effectively and improve marketing efficiency.

## Conclusion

This project demonstrates the practical application of unsupervised machine learning in customer segmentation. By using K-Means clustering, businesses can gain valuable insights into customer behavior and develop data-driven marketing strategies to enhance customer experience and profitability.

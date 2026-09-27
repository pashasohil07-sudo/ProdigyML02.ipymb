# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project uses the **K-Means Clustering algorithm** to segment retail customers based on their purchasing behavior and characteristics. The goal is to identify different customer groups and understand their shopping patterns.

## 🎯 Objective

* Segment customers into different groups.
* Analyze customer purchasing behavior.
* Identify similarities between customers.
* Visualize customer clusters.
* Understand customer segments for better business decisions.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## 🔄 Project Workflow

1. Load the customer dataset.
2. Explore and understand the data.
3. Clean and preprocess the data.
4. Select relevant features.
5. Apply the K-Means Clustering algorithm.
6. Determine the suitable number of clusters.
7. Visualize the customer segments.
8. Analyze the resulting clusters.

## 🤖 Algorithm Used

### K-Means Clustering

K-Means is an **unsupervised machine learning algorithm** that divides data into `K` groups based on similarities between data points.

The algorithm works by:

1. Choosing the number of clusters `K`.
2. Selecting initial cluster centers.
3. Assigning customers to the nearest cluster.
4. Updating the cluster centers.
5. Repeating until the clusters become stable.

## 📊 Customer Segmentation

The model groups customers based on selected characteristics such as:

* Annual Income
* Spending Score
* Age
* Purchasing behavior

## 📈 Visualization

The clusters are visualized using graphs to make it easier to understand the different customer segments and their purchasing patterns.

## 🚀 How to Run

Install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open the project notebook and run the cells step by step.

## 📁 Project Structure

```text
Customer-Segmentation/
│
├── customer_segmentation.ipynb
├── dataset.csv
└── README.md
```

## 📌 Result

The project successfully identifies different groups of customers with similar purchasing characteristics. These segments can help businesses understand their customers and develop more targeted marketing strategies.

## 👨‍💻 Author

**Sohil Pasha**

⭐ If you found this project useful, consider giving the repository a star!

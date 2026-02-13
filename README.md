# Mall Customer Segmentation using KMeans

## 📌 Overview

This project performs customer segmentation using the KMeans clustering
algorithm. The goal is to group customers based on similar
characteristics such as age, annual income, and spending score.

------------------------------------------------------------------------

## 📂 Project Structure

    mall-customer-clustering/
    │
    ├── data/
    │   └── Mall_Customers.csv
    │
    ├── notebooks/
    │   └── clustering.ipynb
    │
    ├── requirements.txt
    └── README.md

------------------------------------------------------------------------

## 📊 Dataset

-   Dataset: Mall Customers Dataset
-   Source: Kaggle
-   Features:
    -   CustomerID
    -   Gender
    -   Age
    -   Annual Income (k\$)
    -   Spending Score (1-100)

------------------------------------------------------------------------

## ⚙️ Methods Used

1.  Data Cleaning and Preprocessing
2.  One-Hot Encoding for Gender
3.  Feature Scaling using StandardScaler
4.  Elbow Method for Optimal Cluster Selection
5.  KMeans Clustering (k=5)
6.  Cluster Visualization
7.  Cluster Interpretation

------------------------------------------------------------------------

## 📈 Results

Using the Elbow Method, the optimal number of clusters was determined to
be 5. The model successfully identified distinct customer segments based
on income and spending behavior.

Example cluster interpretations:

-   High income -- High spending → Target customers
-   High income -- Low spending → Conservative customers
-   Low income -- High spending → Impulsive customers
-   Low income -- Low spending → Budget customers
-   Moderate income -- Moderate spending → Average customers

------------------------------------------------------------------------

## 🧠 Technologies Used

-   Python
-   NumPy
-   Pandas
-   Matplotlib
-   Scikit-learn

------------------------------------------------------------------------

## ▶️ How to Run

1.  Install dependencies:

```{=html}
<!-- -->
```
    pip install -r requirements.txt

2.  Open the notebook:

```{=html}
<!-- -->
```
    jupyter notebook

3.  Run all cells.

------------------------------------------------------------------------

## 📌 Author

This project was created as part of a Machine Learning learning journey,
focusing on unsupervised learning and clustering techniques.

------------------------------------------------------------------------

## 📜 License

This project is for educational purposes.

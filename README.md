# Customer Segmentation using Machine Learning

## Project Overview

This project focuses on **segmenting customers into distinct groups** based on their behavior and characteristics using **unsupervised machine learning** techniques.

The goal is to help businesses:

* Understand different types of customers
* Target marketing strategies effectively
* Improve customer retention and revenue

---

## Problem Statement

Businesses often have large amounts of customer data but lack clarity on:

* Who their most valuable customers are
* Which customers are at risk of leaving
* How to personalize marketing strategies

This project solves that by grouping customers into meaningful segments using clustering.

---

## Dataset

* The dataset contains customer-related features such as:

  * InvoiceNo
  * StockCode       
  * Description     
  * Quantity         
  * InvoiceDate     
  * UnitPrice     
  * CustomerID     
  * CountryAge

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn
* Jupyter Notebook / VS Code

---

## Methodology

### 1. Data Preprocessing

* Handled missing values
* Feature selection
* Scaling using StandardScaler

### 2. Exploratory Data Analysis (EDA)

* Distribution plots
* Correlation analysis
* Customer behavior insights

### 3. Model Building

* Applied **K-Means Clustering**
* Used **Elbow Method** to find optimal number of clusters

### 4. Visualization

* Cluster visualization using scatter plots
* Clear interpretation of each segment

---

## Model Used

* **K-Means Clustering**

Why?

* Simple
* Interpretable
* Industry-relevant for segmentation problems

---

## Results & Insights

Insights :

* Cluster 0 (Moderately engaged): Medium Recency and Frequency. They are steady customers but don't spend as much as VIPs.
* Cluster 1 (At Risk/Churn): High Recency, Low Frequency, Low Monetary. These customers haven't visited in a long time and spent very little.
* Cluster 2 (High Value):Low Recency, High Frequency, High Monetary. These are our VIP customers.
* Cluster 3 (Promising): Very Low Recency but Low Frequency. These are new customers who just started shopping; we should welcome them.


## Business Impact

This project can be used in:

* Retail industry (customer targeting)
* E-commerce platforms (recommendation systems)
* Banking & finance (customer profiling)
* Telecom (churn prediction segmentation)

---


## How to Run

1. Clone the repository:

```
git clone <https://github.com/Madhulika-ram/Customer-Segmentation>
```

2. Navigate to the folder:

```
cd Customer-Segmentation
```

3. Install dependencies:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Run the notebook:

```
jupyter notebook
```

---

## Future Improvements

* Add **customer prediction for new data**
* Deploy using **Streamlit dashboard**
* Integrate with **real-time business data**
* Use advanced clustering (DBSCAN, Hierarchical)

---

## Author

Ramaneti Madhulika

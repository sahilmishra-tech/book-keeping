# 📚 Google Books Clustering Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** and **Unsupervised Machine Learning** on the Google Books dataset to discover hidden patterns among books. The project includes data cleaning, preprocessing, dimensionality reduction using Principal Component Analysis (PCA), and clustering using **K-Means** and **Agglomerative Hierarchical Clustering**.

The objective is to group similar books based on their characteristics, which can be useful for recommendation systems, catalog management, and market analysis.

---

## 🎯 Problem Statement

With the increasing size of digital libraries, organizing and analyzing thousands of books manually has become difficult. Books differ in terms of authors, publishers, categories, publication years, and page counts. Identifying similarities among books using traditional methods is challenging.

This project aims to apply **unsupervised machine learning** techniques to automatically discover meaningful groups of books based on their features, enabling better organization, recommendations, and data-driven insights.

---

## 🎯 Objectives

- Perform data cleaning and preprocessing.
- Handle missing values and duplicate records.
- Conduct Exploratory Data Analysis (EDA).
- Standardize numerical features.
- Reduce dimensionality using PCA.
- Determine the optimal number of clusters.
- Apply K-Means Clustering.
- Apply Agglomerative Hierarchical Clustering.
- Compare clustering results through visualizations.

---

## 📂 Dataset

**Dataset:** Google Books Dataset

### Features

- Book ID
- Title
- Authors
- Publisher
- Categories
- Description
- Published Date
- Page Count
- Subtitle
- Average Rating

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- SciPy

---

## 📊 Data Preprocessing

The following preprocessing steps were performed:

- Removed duplicate records
- Handled missing values
- Removed unnecessary columns
- Label Encoding for categorical variables
- Standard Scaling using StandardScaler

---

## 📈 Exploratory Data Analysis

The following visualizations were created:

- Missing Value Analysis
- Distribution of Page Count
- Top Publishers
- Top Authors
- Top Categories
- Publication Year Distribution
- Box Plot for Outlier Detection
- Correlation Heatmap
- PCA Visualization
- Cluster Distribution

---

## 🔍 Principal Component Analysis (PCA)

Principal Component Analysis was used to reduce the dimensionality of the dataset while preserving most of the important information.

Benefits:

- Faster clustering
- Reduced noise
- Better visualization
- Lower computational cost

---

## 🤖 Clustering Algorithms

### 1. K-Means Clustering

- Elbow Method used to determine optimal clusters
- Optimal Number of Clusters: **6**
- 2D PCA Visualization
- 3D Interactive Visualization using Plotly

---

### 2. Agglomerative Hierarchical Clustering

- Ward Linkage
- Dendrogram Visualization
- Cluster Visualization using PCA

---

## 📊 Model Evaluation

The following methods were used:

- Elbow Method
- Dendrogram
- Silhouette Score

---

## 📁 Project Structure

```
Google-Books-Clustering/
│
├── Dataset/
│   └── google_books_dataset-selected-columns.csv
│
├── notebooks/
│   └── Google_Books_Clustering.ipynb
│
├── images/
│   ├── elbow_method.png
│   ├── dendrogram.png
│   ├── kmeans_2d.png
│   ├── kmeans_3d.png
│   └── agglomerative.png
│
├── README.md
└── requirements.txt
```

---

## 🚀 Workflow

```
Dataset
    │
    ▼
Data Cleaning
    │
    ▼
Missing Value Handling
    │
    ▼
Feature Engineering
    │
    ▼
Exploratory Data Analysis
    │
    ▼
Label Encoding
    │
    ▼
StandardScaler
    │
    ▼
Principal Component Analysis (PCA)
    │
    ▼
Elbow Method
    │
    ▼
K-Means Clustering
    │
    ▼
Agglomerative Clustering
    │
    ▼
Dendrogram
    │
    ▼
Visualization & Evaluation
```

---

## 📈 Results

- Successfully cleaned and preprocessed the dataset.
- Performed comprehensive EDA to understand data characteristics.
- Reduced feature dimensions using PCA.
- Determined the optimal number of clusters using the Elbow Method.
- Clustered books into **6 distinct groups** using K-Means.
- Validated clustering with Agglomerative Clustering.
- Visualized clusters using both 2D and interactive 3D PCA plots.

---

## 💡 Future Enhancements

- Apply DBSCAN for density-based clustering.
- Use t-SNE or UMAP for advanced visualization.
- Build a book recommendation system based on clusters.
- Incorporate NLP techniques using book descriptions.
- Develop an interactive dashboard with Streamlit.

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/google-books-clustering.git
```

Navigate to the project directory:

```bash
cd google-books-clustering
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## 📚 Libraries Required

```text
pandas
numpy
matplotlib
seaborn
plotly
scikit-learn
scipy
jupyter
```

---

## 👨‍💻 Author

**Sahil Mishra**

B.Tech Computer Science Engineering (Data Science)

Bhagwan Parshuram Institute of Technology (BPIT)

---

## 📄 License

This project is created for educational and academic purposes.

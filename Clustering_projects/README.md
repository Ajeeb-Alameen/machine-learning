# 📊 Clustering Project

## 📌 Overview

This project explores clustering techniques using two different datasets: **Iris Dataset** and **Moons Dataset**. The goal is to apply unsupervised learning methods to group data points into meaningful clusters and analyze the performance of different clustering algorithms.

## 📂 Project Structure

```
📂 Clustering_project
   ├── Iris_clustering_project.ipynb
   ├── Moons_Clustering_project.ipynb
   ├── data(Iris.csv)
   ├── README.md
```

## 🔍 Datasets Used

### 🌸 Iris Dataset
- **Description**: A well-known dataset containing measurements of **sepal length, sepal width, petal length, and petal width** for three species of iris flowers.
- **Goal**: Cluster the flowers based on their features to identify natural groupings.
- **Source**: UCI Machine Learning Repository

### 🌙 Moons Dataset
- **Description**: A synthetic dataset with **two interleaving moon-shaped clusters**.
- **Goal**: Apply clustering techniques and observe how different algorithms handle arbitrary shapes.
- **Source**: Generated using `make_moons()` function in `sklearn.datasets`

## 🔬 Techniques Used

- **K-Means Clustering**: Partitions data into K clusters by minimizing intra-cluster variance.
- **Hierarchical Clustering**: Builds a tree-like structure to merge clusters.
- **DBSCAN**: Detects arbitrary-shaped clusters based on density.
- **Silhouette Score & Inertia**: Used for evaluating clustering quality.

## 📈 Results & Analysis

### Iris Dataset:
- K-Means successfully grouped flowers but required an optimal `K` selection.
- Hierarchical clustering provided a dendrogram-based visualization.
- DBSCAN was less effective due to the compact nature of clusters.

### Moons Dataset:
- K-Means struggled with the moon-shaped clusters.
- Hierarchical clustering worked well but required careful parameter tuning.
- DBSCAN outperformed other techniques in detecting the curved structure.

## 🛠 Technologies Used

- **Language**: `Python`
- **Tools & Libraries**: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scikit-Learn`
- **Environment**: `Jupyter Notebook

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Ajeeb-Alameen/Machine_learning.git
   cd Machine_learning/Clustering_projects
   ```
2. **Launch any notebook**
   ```bash
   jupyter notebook <notebook_name>.ipynb
   ```


## 📌 Next Steps

- Experiment with **additional clustering techniques** like **Gaussian Mixture Models (GMM)**.
- Apply **dimensionality reduction (PCA, t-SNE)** before clustering.
- Optimize clustering algorithms with **hyperparameter tuning**.

## 🔗 Links

- 📂 **Main Repository**: [Machine Learning Repository](https://github.com/Ajeeb-Alameen/Machine_learning)
- 📄 **Iris Dataset**: [UCI Repository](https://archive.ics.uci.edu/ml/datasets/iris)

---

## 🔗 Links

- 📂 GitHub Repository: [Machine Learning Repo](https://github.com/Ajeeb-Alameen/Machine_learning)
- ✍ Author: Ajeeb Alameen
- 📧 Email: ajeebizzalameen@gmail.com
- 🔗 LinkedIn: [Ajeeb Alameen](https://www.linkedin.com/in/ajeeb-alameen)

---


# mimic3-clustering-analysis
Clustering on MIMIC-III clinical data using K-Means and Hierarchical techniques

This project applies unsupervised learning techniques—**K-Means** and **Hierarchical Clustering**—to analyze real patient data from the MIMIC-III clinical database. The goal is to uncover hidden patterns in demographics, lab test results, and vital signs, which may help better understand patient profiles.

## 🔍 Project Objectives

- Prepare and preprocess clinical data from MIMIC-III
- Perform clustering using:
  - K-Means (with Elbow method)
  - Hierarchical Clustering (with dendrograms and linkage methods)
- Visualize and compare cluster characteristics
- Draw insights based on feature distributions across clusters

## 🧰 Features Used

- **Demographics**
- **Lab Tests**
- **Vital Signs**

## 📊 Techniques & Tools

- K-Means Clustering
- Hierarchical Clustering (Ward, Complete, Average linkage)
- Elbow Method
- Silhouette Score
- Dendrogram Visualization
- Pairplot, Heatmaps, and Scatter plots for cluster interpretation

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `scipy`

## 🗃️ Dataset

- **MIMIC-III Clinical Database**
- Public project source: [https://github.com/DanielSola/mimic-iii-project](https://github.com/DanielSola/mimic-iii-project)

## 📈 Insights

- Identified patient clusters based on physiological profiles
- Clear differences observed in lab results and vitals across clusters
- Hierarchical clustering offered deeper hierarchical relationships

## 🎯 Target Audience

This project is intended for:
- Recruiters in data science and healthcare analytics
- Portfolio and resume enhancement
- Kaggle-style project showpieces

---

## ▶️ Run the Notebook

To run the notebook:
1. Clone the repo
2. Open the `.ipynb` file in Jupyter/Colab
3. Install dependencies from `requirements.txt`


# 📘 Machine Learning Notebooks

This repository contains two Jupyter Notebooks demonstrating clustering and environmental data analysis using Python. Each notebook walks through data preprocessing, exploration, model development, and evaluation.

---

## 🌸 1. Iris Clustering

**File:** `Iris_Clustering.ipynb`

### 🎯 Objective
To explore and cluster the famous *Iris flower dataset* using unsupervised learning techniques to uncover natural groupings based on petal and sepal measurements.

### 🧩 Key Steps
- Load and preprocess the Iris dataset.  
- Perform exploratory data analysis (EDA) using visualizations.  
- Apply clustering algorithms:
  - **K-Means Clustering**
  - **Hierarchical Clustering**
- Visualize clusters using scatter plots and dendrograms.  
- Evaluate clustering quality using the **silhouette score**.  
- Compare clusters with the actual Iris species labels.

### 💡 Insights
K-Means formed clearer and more distinct clusters compared to hierarchical clustering.  
The results closely matched the true Iris species, indicating that K-Means effectively captures the dataset's structure.

---

## 🌍 2. Urban Air Pollution Challenge

**File:** `urban_air_pollution.ipynb`

### 🎯 Objective
To analyze and cluster global air pollution data and evaluate the model’s performance through a public leaderboard.

### 🧩 Key Steps
- Data cleaning and preprocessing of air pollutant measurements.  
- Exploratory analysis to understand patterns and correlations.  
- Apply machine learning techniques:
  - **K-Means Clustering**
  - **Agglomerative Clustering**
  - **Random Forest** as a baseline classification model.  
- Evaluate results based on leaderboard ranking.

### 🏆 Results
- **Leaderboard Rank:** 372 out of 1582 participants.  
- Discovered distinct patterns in pollutant magnitudes and meteorological factors.  
- Demonstrated strong performance despite being an individual submission.

### 💡 Reflection
This project reinforced clustering concepts and model evaluation skills. Future improvements could involve deeper feature engineering and ensemble modeling to improve accuracy.

---

## 🧰 Technologies Used
- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**


---



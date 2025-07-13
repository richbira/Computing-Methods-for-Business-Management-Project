# Computing Methods for Business Management Project
Author: Richard Rabi
University of Milano-Bicocca — Academic Year 2023/2024

This is a university project for the course *Computing Methods for Business Management*, which involves building a **Recommendation System** (Collaborative Filtering & Content-Based) using a dataset of book reviews.  
The main focus is on **Collaborative Filtering**, with evaluation and comparison against Matrix Factorization techniques.

---

📋 **Main activities**
- Exploratory Data Analysis (EDA) of the dataset (descriptive statistics, missing values, correlations, distribution analysis)
- Optimization of the **K-NN (K-Nearest Neighbors)** algorithm:
  - Testing different similarity metrics (cosine, pearson, msd)
  - Different *k* values and user/item-based configurations
  - Evaluation using RMSE and MSE
- Filling the rating matrix with predictions based on the optimal K-NN configuration
- User segmentation via **K-Means clustering** using cosine similarity and elbow method
- Generating a list of top-N recommended items for each user based on predicted ratings
- Applying **Matrix Factorization (SVD)** and comparing its performance with K-NN

---

🛠️ **Technologies used**
**Language:** Python

**Main libraries:**
- `numpy`, `pandas` — data manipulation and analysis
- `matplotlib`, `seaborn` — data visualization
- `scikit-surprise` — collaborative filtering algorithms (K-NN, SVD)
- `scikit-learn` — clustering, metrics, preprocessing
- `json`, `os` — data reading and handling

---

📄 **Repository contents**
This repository contains:
- The Jupyter Notebook with the full code and report (in italian)
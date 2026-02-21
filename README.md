# Movie Recommendation System 🎬

A comprehensive recommendation engine implementing Collaborative Filtering and Matrix Factorization on the **MovieLens 100k** dataset.

## 📌 Project Overview

This project explores different recommendation strategies to solve the data sparsity problem (). It implements neighborhood-based methods (User-Based and Item-Based) and advanced Model-Based methods (SVD) to provide personalized movie suggestions.

## 🚀 Key Features

* **Temporal Data Splitting:** split data chronologically (80/20) to prevent "data leakage" from the future.
* **EDA:** Visualization of rating distributions and user-item matrix sparsity.
* **KNN-Based Filtering:** Compared User-User vs. Item-Item similarities using Cosine Similarity.
* **SVD Matrix Factorization:** Utilized Singular Value Decomposition to identify latent factors.
* **Cold-Start Solution:** Implemented a popularity-based fallback for new users.
* **Evaluation Metrics:** Measured performance using RMSE, MAE, Precision@10, and Recall@10.
* **Latent Factor Visualization:** Projected 100-dimensional movie embeddings into 2D space using PCA.

## 🛠️ Installation & Setup

1. **Clone the repository** (or download the files).
2. **Install dependencies:**
```bash
pip install -r requirements.txt

```


3. **Run the Notebook:**
Open `Project_Notebook.ipynb` in Jupyter or Google Colab and run all cells.

## 📊 Results Summary

The **SVD Model** proved to be the most effective for this dataset:

* **Lowest RMSE:** ~0.94
* **Precision@10:** 0.7218
* **Recall@10:** 0.3703

## 📂 Project Structure

* `moviee
* .ipynb`: The main execution file.
* `requirements.txt`: List of required Python libraries.
* `README.md`: Project documentation.


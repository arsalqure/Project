readme_content = """
# 📦 Amazon Electronics Product Recommendation System

A data-driven recommendation engine built using real-world Amazon electronics product ratings. This project explores **popularity-based** and **collaborative filtering** (item-item) techniques to suggest highly-rated products using machine learning models and visualization.

---

## 📊 Project Overview

This project analyzes a large-scale Amazon product review dataset to:
- Explore rating trends, distribution, and user behavior
- Build a **popularity-based recommendation engine**
- Build an **item-based collaborative filtering model** using `scikit-surprise`
- Visualize top-rated products and understand rating skewness
- Perform **Singular Value Decomposition (SVD)** to reduce dimensionality and recommend similar products

---

## 📎 Dataset

- **Source**: [Kaggle - Amazon Product Reviews (Electronics)](https://www.kaggle.com/datasets/irvifa/amazon-product-reviews/data)
- **Size**: 7.8 million rows (20% sampled for analysis)

---

## 🔧 Installation

Make sure you have Python 3.8+ and install the required libraries:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn scikit-surprise

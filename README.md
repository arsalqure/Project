
# 📦 Amazon Electronics Product Recommendation System

A data-driven recommendation engine built using real-world Amazon Electronics product ratings. This project implements both **popularity-based** and **item-based collaborative filtering** approaches, combined with dimensionality reduction techniques to generate personalized product suggestions.

---

## 📊 Project Overview

This project analyzes a large-scale Amazon Electronics review dataset to:

- Understand rating distribution and user behavior
- Build a **popularity-based recommendation engine**
- Implement **item-based collaborative filtering** using scikit-surprise
- Apply **Truncated Singular Value Decomposition (SVD)** to reduce dimensionality
- Evaluate and visualize recommendation performance

---

## 📂 Dataset

- **Source**: [Kaggle – Amazon Product Reviews (Electronics)](https://www.kaggle.com/datasets/irvifa/amazon-product-reviews/data)
- **Size**: ~7.8 million rows (sampled 20% for performance optimization)
- **File Used**: ratings_Electronics.csv

---

## ⚙️ Installation

Ensure Python 3.8+ is installed. Then install the required dependencies:

bash
pip install pandas numpy seaborn matplotlib scikit-learn scikit-surprise

---

## 🔍 Features

- 📊 **Efficient Sampling**  
  Sampled a large dataset (7.8 million rows) — reduced by 80% for faster prototyping.

- 📈 **Data Visualization**  
  - Rating distribution  
  - Top 20 most-rated products  
  - Correlation: rating vs. rating count  

- 🌟 **Recommendation Systems**  
  - Popularity-based recommendations (using rating frequency)  
  - Item-item collaborative filtering with KNNWithMeans  
  - Dimensionality reduction using **Truncated SVD**  
  - Generated top-20 product recommendations using similarity matrix  

- 📉 **Model Evaluation**  
  - RMSE metric used for accuracy assessment  
  - Hyperparameter tuning with GridSearchCV *(commented for runtime control)*  

---

## 🧠 Technologies Used

- **Python 3.8+**
- **Pandas** & **NumPy** – data manipulation
- **Seaborn** & **Matplotlib** – data visualization
- **scikit-learn** – dimensionality reduction, model tuning
- **scikit-surprise** – collaborative filtering and recommendation algorithms

- ---

## 📈 Evaluation

- **RMSE** of item-based collaborative model: ~1.308  
- **Correlation** between rating and rating count: 0.11  
- **Top correlated products** identified and visualized successfully  

---

## 📄 License

This project is open-source under the **MIT License**.

---

## 👤 Author

**Arsalan Ahmed Qureshi**  
*Aspiring Data Analyst | Python | SQL | Visualization | Machine Learning*  

- 🔗 [LinkedIn](https://www.linkedin.com/in/arsalanahmed9144/) <!-- Replace with actual link -->
- 📫 arsalanahmed9144@gmail.com <!-- Replace with actual email -->

---

## 💡 Future Enhancements

- Deploy as a web app using **Flask** or **Streamlit**  
- Add **user-based collaborative filtering** for comparison  
- Implement advanced models like **SVD++** or **NMF**  
- Integrate with **real-time product APIs** or create a **UI interface**  

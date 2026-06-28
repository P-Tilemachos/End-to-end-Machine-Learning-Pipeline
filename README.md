# End-to-End Machine Learning Pipeline

This repository contains an end-to-end machine learning project where core techniques are applied to a real dataset.  
The project focuses on data inspection, preprocessing, supervised learning, unsupervised learning, and systematic performance evaluation.

The main goal is to analyze how different machine learning methods behave under various preprocessing choices and train–test splits, and to draw meaningful conclusions based on quantitative results.

---

## 📌 Project Overview

In this project, I implemented a complete machine learning workflow, starting from raw data analysis and preprocessing, and continuing with classification and clustering techniques.  
Both supervised and unsupervised approaches are explored in order to better understand the structure of the data and the effectiveness of different models.

The project emphasizes practical experimentation and comparison of methods rather than theoretical derivations.

---

## 📊 Dataset

The dataset used in this project is a tabular dataset containing multiple features and a target (class) variable.  
It is suitable for both supervised classification and unsupervised clustering experiments.

Initial data inspection includes:
- checking for missing values
- analyzing class distribution
- identifying potential outliers and data inconsistencies

---

## 🧪 Methods Implemented

### Data Preprocessing
- Descriptive statistics analysis
- Missing value inspection and handling
- Feature scaling / normalization
- Outlier detection
- Feature selection
- Train–test splitting (70/30, 80/20, 90/10)

### Supervised Learning
- Linear classification model
- Quadratic classification model
- Naive Bayes classifier
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion matrix

### Unsupervised Learning
- K-means clustering
  - Elbow method
  - Silhouette analysis
- Hierarchical clustering
  - Dendrogram visualization
- Comparison between clustering results and true class labels

---

## 📈 Results & Evaluation

The performance of each model is evaluated and compared using standard machine learning metrics.  
Special attention is given to:
- the impact of preprocessing steps
- differences between supervised and unsupervised approaches
- model stability across different train–test splits

The results highlight the strengths and limitations of each method and provide insights into the structure of the dataset.

---

## ▶️ How to Run

1. Clone the repository:
git clone https://github.com/P-Tilemachos/end-to-end-machine-learning-analysis.git

2. Install the required Python packages:
pip install numpy, pandas, matplotlib, seaborn, scikit-learn



## 📄 License

This project is intended for educational and learning purposes.

---

## 👨‍💻 Author

P-Tilemachos  
GitHub: https://github.com/P-Tilemachos

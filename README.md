# Machine Learning & Techno-Economic Optimization for Sustainable Interlocking Bricks

This repository contains the machine learning modeling, cross-validation framework, and techno-economic cost optimization scripts developed for evaluating the compressive strength of lateritic interlocking bricks reinforced with alkali-treated bamboo fibers and sawdust ash.

## 📌 Project Overview
* **Dataset:** $N = 61$ physical laboratory specimens (cleaned from 66 via ASTM C109/E178 intra-batch outlier screening).
* **Validation Strategy:** Stratified 80/20 train-test split ($n=48$ train, $n=13$ unseen test) combined with 48-fold Leave-One-Out Cross-Validation (LOOCV).
* **Candidate Models:** Random Forest, Gradient Boosting, XGBoost, and CatBoost (optimized with tight regularization to prevent overfitting).
* **Economic Framework:** Material cost-benefit analysis and Pareto-frontier optimization calibrated for standard 180-brick batches in Nigerian Naira (₦).

## 🛠️ Tech Stack & Libraries
* Python 3.x
* `scikit-learn`, `xgboost`, `catboost`
* `pandas`, `numpy`, `matplotlib`, `seaborn`, `ipywidgets`
* `openpyxl`

## 🚀 How to Run the Code
1. Clone the repository or open the script in **Google Colab**.
2. Ensure your input data file (`ML_Data.xlsx`) is uploaded to your working directory.
3. Run the cells sequentially to execute outlier screening, feature normalization, model training, interactive diagnostic widgets, and the Naira cost-optimization module.

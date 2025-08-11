# Decision Trees & Random Forests - Heart Disease Classification

## Overview
This project demonstrates the use of **Decision Tree** and **Random Forest** classifiers on the Heart Disease dataset. It includes training, overfitting control, feature importance analysis, cross-validation, and tree visualization using **Graphviz**.

## Dataset
- **Name:** Heart Disease Dataset  
- **Target:** `target` (1 = Disease, 0 = No Disease)  
- **Source:** Public dataset (e.g., UCI Repository / Kaggle)

## Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Graphviz

## Features
1. Train Decision Tree Classifier  
2. Visualize tree structure  
3. Control overfitting (max depth)  
4. Train Random Forest Classifier  
5. Compare accuracy of models  
6. Plot feature importances  
7. Evaluate with cross-validation  

## Results
- Decision Tree with unlimited depth may overfit  
- Limited depth reduces overfitting  
- Random Forest provides better and more stable accuracy  

## Tree Visualization
Generated using Graphviz, showing feature splits, thresholds, and class distribution at each node.

# Machine-Learning-Tasks
This project explores three fundamental machine learning techniques: **clustering**, **regression**, and **classification**. Each technique is applied to a real-world dataset, and the results are analyzed to provide insights into the effectiveness of different algorithms.

## Introduction
The project focuses on three key machine learning tasks:
- **Clustering**: Grouping similar data points using algorithms like KMeans, Hierarchical Clustering, and DBSCAN.
- **Regression**: Predicting continuous outcomes using models like Linear Regression, Gradient Boosting, and Random Forest.
- **Classification**: Categorizing data into predefined classes using classifiers like LightGBM, XGBoost, and AdaBoost.

## Clustering
The clustering task uses the **Wholesale Customers Dataset** to group customers based on their purchasing behavior. Techniques like KMeans, Hierarchical Clustering, and DBSCAN are applied, and the results are analyzed to identify patterns and outliers.

### Key Findings:
- **KMeans** and **Hierarchical Clustering** are effective in identifying high-spending customers.
- **DBSCAN** is less sensitive to outliers and provides distinct clustering results.
- **Winsorization** is used to handle outliers without removing them.

## Regression
The regression task predicts house prices using the **Ames Housing Dataset**. Various regression models, including Linear Regression, Gradient Boosting, and Random Forest, are compared to find the best-performing model.

### Key Findings:
- **Gradient Boosting** performs best among the tested models.
- **Log transformation** of the target variable improves model performance but requires careful handling.
- Feature engineering, such as creating a total area feature, enhances model accuracy.

## Classification
The classification task predicts whether an individual's income exceeds $50,000 using the **Adult Income Dataset**. Multiple classifiers, including LightGBM, XGBoost, and AdaBoost, are evaluated based on accuracy and F1 score.

### Key Findings:
- **LightGBM** achieves the highest accuracy and F1 score.
- Feature importance analysis reveals that **Capital Gain** and **Age** are the most influential features.
- Data preprocessing, including handling missing values and scaling, is crucial for model performance.

## Lessons Learnt
- **Clustering**: Outliers can significantly impact clustering results, and techniques like Winsorization can help mitigate their effects.
- **Regression**: Log transformation can improve model performance but requires careful handling to avoid issues like data leakage.
- **Classification**: Imbalanced datasets require careful handling, and ensemble methods like LightGBM can provide robust results.

## References
1. Dixon, W. J. (1960). Simplified Estimation from Censored Normal Samples. *The Annals of Mathematical Statistics*, 31, 385–391.
2. Scikit-learn Documentation: [https://scikit-learn.org](https://scikit-learn.org)
3. LightGBM Documentation: [https://lightgbm.readthedocs.io](https://lightgbm.readthedocs.io)

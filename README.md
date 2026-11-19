**Project Implementation**

This research project, Multi-Objective Nature-Inspired Feature Selection for Efficient Machine Learning Classification, was implemented using Python in Google Colab with the TopoClass dataset which is a real time dataset published in 2025.

The project explores nature-inspired feature-selection techniques to identify informative material descriptors, reduce feature dimensionality, and evaluate their impact on machine learning classification performance.

**1 Implemented Approaches**

- Pearson Correlation: Ranks features and selects the top 300 descriptors.
- Ant Colony Optimization (ACO): Selects an optimized subset of 74 features.
- Binary Firefly Algorithm: Selects an optimized subset of 130 features.
- Machine Learning Models: Linear SVM, Random Forest, and XGBoost.

**2 Experimental Results**

| Configuration | Features | Accuracy | Macro-F1 |
| Random Forest – Baseline | 300 | 80.85% | 0.5994 |
| Random Forest – ACO | 74 | 81.11% | 0.6026 |
| Random Forest – Binary Firefly | 130 | 80.69% | 0.5940 |

Best Result: Random Forest combined with ACO achieved 81.11% accuracy and a macro-F1 score of 0.6026, with approximately 75.33% feature reduction.

**3 Implementation Notebook**

The complete implementation, including dataset preprocessing, feature selection, model training, evaluation, and result comparison, is available in the google colab Notebook:

(./topo-final.ipynb)

Execution Environment: Google Colab

**4 Technologies and Libraries**

- Python
- Google Colab
- NumPy and Pandas
- Scikit-learn
- XGBoost
- Matplotlib and Seaborn

**1 Dataset Source**

[TopoClass – Materials Cloud Archive](https://archive.materialscloud.org/records/gnv15-27a69)

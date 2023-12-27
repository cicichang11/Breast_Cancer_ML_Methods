# Breast Cancer Machine Learning Methods Comparison Project

## Overview
This project focuses on comparing different machine learning methodologies, including supervised, semi-supervised, unsupervised, and active learning techniques. The analysis is conducted using Monte-Carlo simulations on two datasets: Breast Cancer Wisconsin Diagnostic and Banknote Authentication. The primary goal is to evaluate these methods based on performance metrics like accuracy, precision, recall, F1-score, and AUC, with a specific emphasis on learning curves in active learning scenarios.

## Datasets
1. **Breast Cancer Wisconsin Diagnostic Dataset**
   - Contains IDs, classes (Benign=B, Malignant=M), and 30 attributes.
2. **Banknote Authentication Dataset**
   - Binary classification dataset for authenticating banknotes.

## Methods
1. **Supervised Learning**
   - L1-penalized SVM training using 5-fold cross-validation.
2. **Semi-Supervised Learning**
   - Combination of labeled and unlabeled data in training SVM.
3. **Unsupervised Learning**
   - K-means clustering assuming two clusters.
4. **Spectral Clustering**
   - Clustering using RBF kernel focusing on data point balance.
5. **Active Learning**
   - SVMs trained with incremental data points selection.

## Files Description
- `Breast_Cancer_ML_Methods_Cici_Chang.ipynb`: Main Jupyter notebook containing code implementations for each method, data processing, model training, evaluation, and result visualization.

## Requirements
- Python 3.x
- Libraries: sklearn, pandas, numpy, matplotlib (see notebook for detailed requirements and installation commands)

## Usage
To run the notebook:
1. Ensure Python 3.x is installed on your system.
2. Install required Python libraries.
3. Open the `Breast_Cancer_ML_Methods_Cici_Chang.ipynb` notebook in a Jupyter environment.
4. Execute the cells sequentially to view the analysis and results for each method.

## Results
The results section in the notebook provides a comprehensive analysis of each learning method. It includes comparisons based on accuracy, precision, recall, F1-score, and AUC, along with visualizations like ROC curves and confusion matrices.

## Conclusions
The notebook concludes with insights on the effectiveness of each learning strategy in the context of classification tasks, highlighting the strengths and weaknesses of each method.

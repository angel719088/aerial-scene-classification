# Aerial Landscape Image Classification

In this repository, we will classify aerial scene images using traditional machine learning with imbalanced methods

## Requirements

We recommend using Python 3.8+ with the following libraries:

- `opencv-python`
- `matplotlib`
- `joblib`
- `numpy`
- `scipy`
- `scikit-learn`
- `seaborn`

## Implemented Models

**Machine Learning Methods**
KNN, Decision Tree, Random Forest
SVM, SGD  
**Feature Extraction:** SIFT, LBP  
**Imbalance Handling:** SMOTE

## Training and Evaluation Methods 
We utilized performance metrics including Accuracy, Precision, Recall, F1-score, Classification Report, Confusion Matrix to evaluated models

## Usage Instructions

KNN & DT & RF (KNN_DT_RF_SIFT_LBP_Imbalance_SMOTE.ipynb)
This notebook merges several key processes and results, including traditional classifiers and imbalance handling.
Please review and update before reusing. Please don't rerun these cells.


### Dataset
Download the dataset from [Kaggle](https://www.kaggle.com/datasets/ankit1743/skyview-an-aerial-landscape-dataset/data) and place it in the appropriate directory.
The dataset contains 15 aerial scene classes with 800 images each.


## Code References

**KNN, DT, RF, CNN, Plot, ConfusionMatrix**
- [KNeighborsClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)
- [DecisionTreeClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html)
- [RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
- [cnn](https://www.tensorflow.org/tutorials/images/cnn)
- [plot_sift](https://scikit-image.org/docs/0.25.x/auto_examples/features_detection/plot_sift.html)
- [plot_local_binary_pattern](https://scikit-image.org/docs/0.24.x/auto_examples/features_detection/plot_local_binary_pattern.html)
- [plot_sift](https://scikit-image.org/docs/0.25.x/auto_examples/features_detection/plot_sift.html)
- [ConfusionMatrixDisplay](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.ConfusionMatrixDisplay.html)
  
**Gradcam**
- [pytorch-grad-cam](https://github.com/jacobgil/pytorch-grad-cam)

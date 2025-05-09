# Multimodal Classification with Autoencoder & Ensemble Methods

## Overview  
This Jupyter notebook builds a simple **convolutional autoencoder** to extract latent representations from images, **concatenates** them with tabular/textual features, and then trains and compares several classifiers (Decision Tree + AdaBoost, Random Forest, SVM) using **K-fold cross-validation**. It concludes with performance plots and a brief comparative analysis.

## Keypoints
* Autoencoder is implemented using `PyTorch` and the architecture is based on CNN
* AdaBoost is implemented from scratch


## Dataset  
AiGen-FoodReview dataset, available here: https://zenodo.org/records/10511456.
The metadata CSV includes an `ID` column matching filenames in `images/`.





# Assignment 7 — Credit Default Classification

This folder contains two different practical workflows. The notebook compares support-vector machine (SVM) and k-nearest-neighbors (KNN) classifiers for predicting credit-card payment default. The Word report covers transfer learning for flower image classification with pretrained AlexNet, VGG16, ResNet50, and EfficientNet-B0 models.

## Files

- `Assignment7.ipynb` — credit-default analysis notebook with confusion matrices, an accuracy chart, and a metrics heatmap.
- `DL_Assignment-7_12414973.docx.docx` — transfer-learning practical report. The doubled `.docx` extension is retained as supplied.

## Requirements and data

The notebook uses pandas, NumPy, Matplotlib, seaborn, and scikit-learn. It expects the UCI credit-card dataset as `UCI_Credit_Card.csv`; update the input path if it is not located at `/content/sample_data/`. The separate report uses PyTorch/torchvision and a Kaggle flowers dataset, with setup commands intended for Google Colab.

# Final Term Project

## Brain Tumor Classification

Brain Tumors are classified as: Benign Tumor, Malignant Tumor, Pituitary Tumor, etc.The folder contains MRI data. The images are split into Training and Testing folders. Each folder has more four subfolders. These folders have MRIs of respective tumor classes

### What I do in my project
I create model to predict types of Brain tumor in this project.
Firstly, I Train a model using training dataset.
Secondly, I Measure accuracy of the trained model on test dataset.
Finaly, I tune the best yuper-parameter to maximize the accuracy.

### Training dataset

Tumor_dataset has 4 classes of images which are classified as: Benign Tumor, Malignant Tumor, Pituitary Tumor, etc.

### Requirement

* os

* sklearn.datasets

* sklearn.linear_model

* sklearn.svm

* sklearn.tree

* sklearn.ensemble

* sklearn.model_selection

* sklearn.metrics

* skimage.io

* skimage.transform

* skimage.color

* optuna

* pandas

* LogisticRegression

* accuracy_score 

* train_test_split

* numpy

* cross_validate

* cross_val_score

* matplotlib.pyplot

### Installation

```bash
pip install scikit-learn
```
```bash
pip install scikit-image
```
```bash
pip install optuna
```

### algorithm

LogisticRegression

### n hyper-parameter of the function

Optimization Algorithm
'solver': 'saga'.
Regularization strength
'C': 1.229528032208937 
Maximum number of iterations
'max_iter': 64032

### Author

* Mika Yoon
* Contact information : mimymo225@naver.com

# License

"Final Term Project" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).


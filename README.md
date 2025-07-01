# K-Nearest-Neighbor-Classification

**NAME** : MURARI YAMINI

### OBJECTIVE : 
This task demonstrates how to build a simple and effective K-Nearest Neighbors (KNN) classification model using the popular Iris dataset. The main objectives are:

- normalize the feature data for fair distance-based classification
  
- test KNN models for various values of K (from 1 to 10)

- identify the best K based on accuracy

- train and evaluate the final model using the best K

- visualize performance with a confusion matrix

### TOOLS USED :
- python

- scikit-learn –for dataset, preprocessing, model training, evaluation

- matplotlib –for visualization

- pandas –for structured data handling

### DATASET : iris dataset

### Workflow

1. load dataset:using load_iris() from sklearn.datasets

2. normalize features:standardize data using StandardScaler

3. train/test split:60% for training,40% for testing

4. model tuning:evaluate KNN for k = 1 to k = 10

5. plot Accuracy vs. K: visual to choose best K

6. train final model:using best K based on accuracy

7. evaluate with Confusion matrix:print and display confusion matrix using ConfusionMatrixDisplay


### OUTPUT :
![Image](https://github.com/user-attachments/assets/908fdd85-9713-498d-a491-8f657a99784e)

![Image](https://github.com/user-attachments/assets/d2cf3d2e-ac77-42be-a465-b9f90c6d0b02)

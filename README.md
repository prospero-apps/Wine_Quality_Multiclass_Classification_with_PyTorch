# Wine Quality Multiclass Classification with PyTorch
wine quality multi-class classification with PyTorch

In this notebook we'll use PyTorch to build a multiclass classification model to predict wine quality based on a couple physicochemical features of wine.

## Contents:

### Data Preparation
The analysis will be based on the 'Wine Quality Dataset' dataset available on kaggle.com - https://www.kaggle.com/datasets/yasserh/wine-quality-dataset. The datasets is related to red variants of the Portuguese "Vinho Verde" wine.

This dataset consists of 1143 records containing information on particular samples, regarding 11 physicochemical features like acidity, various chemicals, density, pH and so on.

![image](https://github.com/user-attachments/assets/18f1fcb2-0a3e-452a-8c53-3721c42dbe7b)

### Model Building
We have the data in place, it's time to build a model. Besides the model, we'll define a loss function and optimizer.

![image](https://github.com/user-attachments/assets/c9bd0049-bf19-4dfc-a527-bd4772343762)

### Model Training
Training the model involves two loops: a training loop, where the model learns the relationships between the features and labels, and a testing loop, where the model is evaluated.

![image](https://github.com/user-attachments/assets/5cdc7aa1-3aab-4dd0-8f6d-2f05f6366c7c)

### Model Evaluation
Let's evaluate the model and see how it performs on data it never saw.

![image](https://github.com/user-attachments/assets/e3805696-75ba-4d6f-9363-959601bb2e0c)

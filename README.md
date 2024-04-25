# AI Project
# KNN model
## Firstly you should download dataset in this link https://drive.google.com/drive/folders/1WBiCUYnvrPFJq591jIPkKsu5c87b5_D1?usp=drive_link
# Description
+ This project build a KNN (K-Nearest Neighbours) model used to classify 5 types flower including: sunflower, rose, tulip, dandelion, daisy.
# About model
+ This project is built base on Python.
+ Framework: sklearn, OpenCV, numpy, pandas, matplotlib.
+ Environment: Google Colab.
+ This project has 2 parts:
  - Part 1: Implemment KNN algorithm (to understand how KNN work) for classifying Iris flower.
  - Part 2: Building KNN base on sklearn for classifying 5 types flower.
# Note
+ You should setting the path before running the code.
# Setting and run the code
+ Step 1: Download file KNN_Model_code.ipynb.
+ Step 2: Open Google Colab and push file code and dataset in Google Colab.
+ Step 3: Run file KNN_Model_code.ipynb.
# Screenshots
Predicting result Iris flower (Implemment KNN).

![image](https://github.com/LangNhatTan/KNN_model_classification_flower/assets/93020907/ade46829-157a-4f5d-a7cd-6077d571b92b)

Accuracy of model

![image](https://github.com/LangNhatTan/KNN_model_classification_flower/assets/93020907/8f2a2946-4412-4aac-9386-c7e088ccf1a4)

Predicting result 5 types flower (KNN base on sklearn).

![image](https://github.com/LangNhatTan/KNN_model_classification_flower/assets/93020907/365a96fd-35f0-43f0-bcd0-cf138d666e22)


# Overall
+ This model has a low accuracy because algorithm in Machine Learning can't good fit with dataset type image. In other word if we want to increase accuracy of this model we have to ways.
  - Way 1: Using dataset type (csv, excel, ...) because Machine Learning is a type of statistical learning -> columns is a feature of object -> good fit -> increase accuracy.
  - Way 2: Extract object before converring to vector -> vector will have the feature of the object -> good fit -> increase accuracy.

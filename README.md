# AI07_Project_1-Heart-Disease-Prediction

This project show how to construct a Neural Network model in google colab to predict whether a patient is having heart disease or not.

You may click on [![image](https://user-images.githubusercontent.com/108325848/180697976-7db0c631-5842-47eb-bda3-aa398e4048e2.png)
](https://colab.research.google.com/?utm_source=scs-index) to open a new Google Colab file. 

We use the [heart_disease.csv](heart_disease.csv) as the raw data set.
You can find the whole code [here](Project_1_Heart_Disease_Prediction.ipynb) or directly in the [google colab](https://colab.research.google.com/drive/1UBavWuPHAuDjxr5M8N5wjGck5J8FT3c7#scrollTo=7Wdzx9gqPeGH). <br>
You can also download the dataset from https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

## Summary of the Dataset
The dataset has 14 attributes. We will use the first 13 attributes as the features, and the last attribute, "target", as the labels. <br>
"Target" is integer valued, with <br>
<p align="center">
0 = no heart disease <br> 
1 = has heart disease    
</p>

The first 13 attributes are:<br>
1. age <br>
2. sex <br>
3. chest pain type (4 values) <br>
4. resting blood pressure <br>
5. serum cholestoral in mg/dl <br>
6. fasting blood sugar > 120 mg/dl <br>
7. resting electrocardiographic results (values 0,1,2) <br>
8. maximum heart rate achieved <br>
9. exercise induced angina <br>
10. oldpeak = ST depression induced by exercise relative to rest <br>
11. the slope of the peak exercise ST segment <br>
12.number of major vessels (0-3) colored by flourosopy <br>
13.thal: 0 = normal; 1 = fixed defect; 2 = reversable defect <br>

## Main Steps in the code
- import the needed modules/packages <br>
- Upload the dataset <br>
- Define the features and the labels <br>
- Seperate the train data and the test data <br>
- Create a neural network using Keras.Sequential <br>
- Compile the model <br>
- Fit the model <br>
- Analyze the performance of the model, tweak the hyperparameter such as learning rate, epoch if needed. <br>
- Save the model <br>


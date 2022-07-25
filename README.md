# AI07_Project_Heart_Disease_Prediction

This project show how to construct a Neural Network model in google colab to predict whether a patient is having heart disease or not.

You may click on [![image](https://user-images.githubusercontent.com/108325848/180697976-7db0c631-5842-47eb-bda3-aa398e4048e2.png)
](https://colab.research.google.com/?utm_source=scs-index) to open a new Google Colab file. 

We use the [heart_disease.csv](heart_disease.csv) as the raw data set.
You can find the whole code [here](https://colab.research.google.com/drive/1UBavWuPHAuDjxr5M8N5wjGck5J8FT3c7)
You can also download the dataset from https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

## Summary 
### Dataset
The dataset has 14 attributes. We will use the first 13 attributes as features, and the last attribute, "target" as labels.
"Target" is integer valued, with 0 = no heart disease and 1 = has heart disease.
The first 13 attributes are:
1. age
2. sex
3. chest pain type (4 values)
4. resting blood pressure
5. serum cholestoral in mg/dl
6. fasting blood sugar > 120 mg/dl
7. resting electrocardiographic results (values 0,1,2)
8. maximum heart rate achieved
9. exercise induced angina
10. oldpeak = ST depression induced by exercise relative to rest
11. the slope of the peak exercise ST segment
12.number of major vessels (0-3) colored by flourosopy
13.thal: 0 = normal; 1 = fixed defect; 2 = reversable defect

### Main Steps to Constuct the Model
0. import the needed module/package
1. Upload the dataset
2. Define the features and the labels
3. Seperate the train data and the test data by using the train_test_split
4. Create a neural network using Keras.Sequential
5. Compile the model
6. Fit the model
7. Analyze the performance of the model, tweak the hyperparameter such as learning rate, epoch if needed.
8. Save the model


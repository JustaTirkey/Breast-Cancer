
# Breast Cancer Prediction 

This is a machine learning project on the breast Cancer dataset to predict if a person is likely to be diagnosised with breast cancer or not. In this I have tested three very basic models to predict the diagnosis. The models are namely logistic regression, deccision tree and random forest.  


## Libraries used
This project is entirely done on jupyter notebook in python. I have used the following python libraries :
1. `pandas` to read and visualize the data 
2. `seaborn` to plot the dataset 
3. `matplotlib.pyplot` to plot the graph 
4. `sklearn.preprocessing.StandardScaler` for feature scaling
5. `sklearn.linear_model.LogisticRegression` for model selection 

## How to implement the project ?!

Steps to implement the project 

1. Open google colab or jupyter notebook.
2. Either download the source code or copy the codes to a new .py file  or new .ipynb file
3. run the codes 


## Accuracy of the model 
I have tested it for three models here are the score for different models for both training and testing set.

|Model|training Score|testing Score|
|-----|---------------|-------------|
|Logistic regression|0.989 |0.956|
|Decision Tree|1.0|0.938|
|Random Forest|0.997|0.973|


As evident the decision tree model is overfitted and we get the best results with the random forest model. So finally Random forest should be used for future predictions. 

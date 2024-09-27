# wine_type_prediction

The repo contains following files:
wine_type_by_chemical_properties.ipynb -jupyter lab with python code
white_wine.csv -dataset containing white wine data 
red_wine.csv -dataset containing red wine data 

Project.
The aim of this project is to predict type of the wine-white or red-based on its chemical properties (features). For this project two wine datasets were used that contain information about some chemical components for both the white wine and the red wine. The two analyzed datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. Vinho Verde (pronounced “veeng-yo vaird”) is a Portuguese wine that comes from the region of Vinho Verde. The 11 wine's features were included in datasets together with a column containing quality score of each wine (score ranges between 0 and 10). Each dataset contains following features:

1 - fixed acidity 

2 - volatile acidity 

3 - citric acid 

4 - residual sugar 

5 - chlorides 

6 - free sulfur dioxide 

7 - total sulfur dioxide 

8 - density 

9 - pH 

10 - sulphates 

11 - alcohol 

12 - quality (score between 0 and 10)


Logistic regression was used to classify wine for white or red based on its features.
Classification report:
              precision    recall  f1-score   support

           0       0.99      0.99      0.99      1225
           1       0.98      0.96      0.97       400

    accuracy                           0.98      1625
   macro avg       0.98      0.98      0.98      1625
weighted avg       0.98      0.98      0.98      1625

Conclusion: The most important features to discriminate between white wine and red wine are:
total sulfur dioxide: about 3 times higher in white wine in comparison with red wine
residual sugar: about 3 times higher in white wine in comparison with red wine
chlorides: about 2 times higher in red wine in comparison with white wine
volatile acidity: about 2 times higher in red wine in comparison with white wine

 




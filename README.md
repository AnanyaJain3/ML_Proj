# Machine Learning Projects 
Machine Learning Assignments and Projects

# PROJECT - SDGs for Machine Learning

- Wildfires are a natural phenomenon but are becoming more dangerous and
affecting substantial areas. Wildfires are predicted to worsen in the coming years and decades,
the United Nations Environment Programme (UNEP) has warned in its annual Frontiers report
released February 17, 2022. There has been a rapid expansion of cities towards forest areas in
many regions in recent decades. This wildland-urban interface is the area where wildfire risks are
most pronounced. The given dataset gives you an insight into the forest fires in the Northeast
region of Portugal. Using the dataset, identify the probability of future fires and the extent of
damage.

# Model for prediction of weather a wildfire is going to happen 
The optimal model is a random forest. We chose among several machine learning models, as well as deep learning models, because it exhibited the best performance. 
For the exploration of different models, please refer to the notebooks FH_base_model.ipynb and FH_NN.ipynb. 

In the rf_model.py file, the following functions can be found:
- get_data(): loads the dataset 
- preprocess(): preprocesses the data, namely sums up the forest measures and does the train test split. One hot encoding has already been done for the csv file and scaling is not necessary for a random forest.
- train_model(): trains the random forest
- predict_rf(): returns a binary prediction of weather there will be a fire or not
- predict_proba_rf(): returns a probability that a wildfire happens 
- score_rf(): returns a score of the model based on the test set 
- save_model(): saves the model as a joblib file 
- load_model(): loads the model

**Insight Deliverable: Predict future fires and the extent of damage.**

# Assignment 1

1. Stochastic Gradient Descent and Batch Gradient Descent using Linear Regression
2. Lasso and Ridge Regression using Polynomial Regression
3. Logistic Regression and Least Squares Classification

The Diabetes dataset given contains the following features. It is used to predict which patient is diabetic
based on the analysis of the patient’s history and key medical factors.

1. No. of Pregnancies: To express the number of pregnancies
2. Glucose level: To express the Glucose level in blood
3. Blood Pressure: To express the Blood pressure measurement
4. Thickness of Skin: To express the thickness of the skin
5. Insulin level: To express the Insulin level in blood

6. BMI: To express the Body mass index
7. Diabetes Pedigree Function: To express the Diabetes percentage. DPF calculates diabetes
likelihood depending on the subject's age and their diabetic family history.
8. Age: To express the age
9. Outcome: To express if the person is diabetic; 1 is Yes and 0 is No

   

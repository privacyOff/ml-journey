**Dataset used**  
I used Kaaggle's Heart Disease Dataset(https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset/data)  
The dataset has 13 different attributes with around 10000 values.  
The dataset consists of labeled instances for a binary classification problem, containing both positive and negative classes. The data was split into training and testing sets to evaluate model performance.  

**Models trained**  
I trained three model on the above dataset. They are :-
- Logistic Regression
- Decision Tree
- Random Forest
All three model were trained on the smae train-test split and only logistic regression model was fed feature scaled values to ensure that model is fairly trained.  

**Metrics used**  
Model performance was evaluated using the following metrics derived from the confusion matrix:
- Accuarcy
- Precision
- Recall

**Key observations**
- Random Forest achived the perfect performance across all metric indicating its the best but its likely due to overfitting.
- Decision Tree displayed great performance with high recall and low false positives.
- Logistic Regression underperformed compatred to other model paticularly in recall indicating it missed many positives.
- This was likely because the data were non-linear.

**Debugging**
- analyzed model performance to find if it was overfitting
- fixed overfitting by limiting max deptha and tuning hyperparameters
- found out which features are important to random forest in making prediction and if it is medically correct.
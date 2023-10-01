# Diabetes-Prediction-LogisticRegression

This project predicts Diabetes for a person using the Logistic Regression Algorithm of Supervised Machine Learning.

### Steps Involved:
- Install Dependencies and Setup :
  
    Install using the requirements file provided -
  ```
  pip install -r requirements.txt
  ```
- Performing the EDA and Feature Engineering on the Data set.
- Segregate the dependent and independent variables.
- Separate dataset into train and test.
- In this step, I have done the Standard Scaling- Standardization and using pickling for the raw unseen data points.
- Train the Model using the Logistic Regression Algorithm.
- Perform the Hyperparameter Tuning using the GridSearch CV.
- Finally, obtain the Accuracy, Precision and Recall for the Trained data.

---
### Important Features Used :

{
    "Pregnancies",
    "Glucose",
    "BloodPressure",
    "SkinThickness",
    "Insulin",
    "BMI",
    "DiabetesPedigreeFunction",
    "Age"
}

### To run the flask application 

```
python app.py
```
---
##### This project is Deployed on the AWS by using the services like Elastic BeanStalk and CodePipeLine.
----

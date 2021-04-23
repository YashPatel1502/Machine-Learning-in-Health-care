# Developed by students of DEPSTAR CSE2 
## Yash D. Patel(18DCS086) 
## Janushi Shastri(18DCS116)
## Shraddha Tandel(18DCS127)

# ----------Multiple Disease Predictor ----------
## About
This webapp was developed using Flask Web Framework . The models used to predict the diseases were trained on large Datasets. All the links for datasets and the python notebooks used for model creation are mentioned below in this readme. The webapp can predict following Diseases:
* Diabetes
* Breast Cancer
* Heart Disease
* Kidney Disease
* Liver Disease


## Models giving best Accuracy of Prediction
Disease | Type of Model | Accuracy
--- | --- | ---
Diabetes | Logistic Regression | 80%
Breast Cancer | Naive Bayes | 97.38%
Heart Disease | Logistic Regression | 88.53%
Kidney Disease | Random Forest & Naive Bayes | 100%
Liver Disease | XGBoost | 77.77%



## Steps to run the WebApp in local Computer
**Step-1:** Download the files in the repository.<br>
**Step-2:** Get into the downloaded folder, open command prompt in that directory and install all the dependencies using following command<br>
```python
pip install -r requirements.txt
```
**Step-3:** After successfull installation of all the dependencies, run the following command<br>
```python
python app.py
```
## 
## Dataset Links
All the datasets were used from kaggle.
* [Diabetes Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
* [Breast Cancer Dataset](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)
* [Heart Disease Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)
* [Kidney Disease Dataset](https://www.kaggle.com/mansoordaku/ckdisease)
* [Liver Disease Dataset](https://www.kaggle.com/uciml/indian-liver-patient-records)


## Links for Python Notebooks used for model creation
* [Diabetes Notebook](https://github.com/YashPatel1502/Machine-Learning-in-Health-care/blob/6c2ee8f8be7809d6005eb0b7df34ef5d3e3f6821/Python%20Notebooks/Diabetes_Prediction.ipynb)
* [Breast Cancer Notebook](https://github.com/YashPatel1502/Machine-Learning-in-Health-care/blob/b14e7bca7071432229dde3d18b0cba9e5410dabb/Python%20Notebooks/Cancer_Prediction.ipynb)
* [Heart Disease Notebook](https://github.com/YashPatel1502/Machine-Learning-in-Health-care/blob/7b5f6beef9a2a386691d805325892fc74e10e592/Python%20Notebooks/Heart_Disease_Prediction.ipynb)
* [Kidney Disease Notebook](https://github.com/YashPatel1502/Machine-Learning-in-Health-care/blob/abe642effc743e9ac7db27c240ff437e9df1f6cc/Python%20Notebooks/Kidney_Disease_Prediction.ipynb)
* [Liver Disease Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Liver_Disease_Prediction.ipynb)

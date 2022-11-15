# Project: Heart Disease Prediction Using ML
### Project Intro/Objective 

The purpose of this project is to predict whether a person is suffering from Heart Disease or not on the basis of his/her input data. The prediction has been done by using Machine Learning (ML) classification algorithm.

### Install

This project requires **Python** and the following Python libraries installed:

- NumPy
- Pandas
- matplotlib
- Seaborn
- scikit-learn

You will also need to have software installed to run and execute a Jupyter Notebook.

If you do not have Python installed yet, you can install the Anaconda distribution of Python, which already has the above packages and more included. 

### Code

Code is provided in the `Heart_Disease_Prediction.ipynb` notebook file. You will also be required to use the `heart.csv` dataset file to complete your work.

### Run

In a terminal or command window, navigate to the top-level project directory `Heart-Disease-Prediction-ML/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Heart_Disease_Prediction.ipynb
```  
or
```bash
jupyter notebook Heart_Disease_Prediction.ipynb
```
or open with Jupyter Lab
```bash
jupyter lab
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The heart dataset consists of 1025 data points, with each datapoint having 13 features. This dataset is Heart Disease Dataset found on the kaggle.

**Features**
1. `age`: age in years
2. `sex`: (1 = male; 0 = female)
3. `cp`: chest pain type
4. `trestbps`: resting blood pressure (in mm Hg on admission to the hospital)
5. `chol`: serum cholestoral in mg/dl
6. `fbs`: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
7. `restecg`: resting electrocardiographic results
8. `thalach`: maximum heart rate achieved
9. `exang`: exercise induced angina (1 = yes; 0 = no)
10. `oldpeak`: ST depression induced by exercise relative to rest
11. `slope`: the slope of the peak exercise ST segment
12. `ca`: number of major vessels (0-3) colored by flourosopy 
13. `thal`: 0 = normal; 1 = fixed defect; 2 = reversable defect

**Target Variable**
14. `target`: Class variable (0 or 1) 526 of 1025 are 1, the others are 0. Value 0 = no heart disease and 1 = heart disease
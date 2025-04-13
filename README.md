## **DESCRIPTION**

Project developed for the study presented in the article *“Just-in-Time Software Defect Prediction Using a Deep Learning-based Model”* published by *New Trends in Computer Sciences* (Volume 02, Issue 02, Dec. 2024).

**Software Defect Prediction (SDP)** has been one of the most widely researched topics in Software Engineering over the last two decades, and one reason for this is that companies recognize the importance of detecting and fixing software defects before releasing them to end users. **Just-In-Time Software Defect Prediction (JIT-SDP)** is a technique to determine whether a change is potentially defect-inducing when the change is registered in versioning control systems.

This study proposes an approach based on **Deep Learning** for predicting defects in software. The objective is to evaluate the potential of using Deep Learning models as tools to help improve software quality. A Multilayer Perceptron (MLP) model was presented for evaluating a large dataset composed of historical data from several popular software projects.
<br><br>
## **PROJECT STRUCTURE**

|--- source<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- preprocess-apachejit-dataset.ipynb (Python code to exploratory data analysis)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- scatterplot-apachejit-dataset.ipynb (Python code to visual analysis of data)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- randomforest-apachejit-model.ipynb (Python code to create and train a random forest model)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- xgboost-apachejit-model.ipynb (Python code to create and train a XGBoost model)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- mlpercetron-apachejit-model.ipynb (Python code to create and train a Multilayer Perceptron model)<br>
|--- modelconfig<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- Models configuration files<br>
|--- dataset<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- java<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- The dataset location
<br><br>
## **ARTICLE LINK**

https://doi.org/10.3846/ntcs.2024.22274
<br><br>
## **RESOURCES**
The dataset used in this study is publicly available at: https://doi.org/10.5281/zenodo.5907001
<br><br>
## **LICENSE**
This project is open-source.
<br><br>

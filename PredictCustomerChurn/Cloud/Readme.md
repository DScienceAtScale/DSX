## Predicting customer churn lab on Apache Spark using Jupyter notebooks
This repository contains the data and analytic assets for the Lab. The Jupyter Notebook is designed to run on 
<a href="https://datascience.ibm.com" target="_blank">IBM Data Science Experience</a> and builds a predictive model using
the churn.csv and customer.csv data sets.

There are 4 main notebooks you can work through:<br><br>
Notebook-1 (PredictCustomerChurnStudent_Learn.ipynb):<br> Applying data science and machine learning methodology to build the predictive model. Save model locally.<br><br>
Notebook-2 (PredictChurnScoreNewData.ipynb):<br> Reloading the predictive model and performing batch scoring.<br><br>
Notebook-3 ( 	PredictChurnDeploytoWML.ipynb):<br> Saving the predictive model to the Watson Machine Learning repository and deploying it using the WML service.<br><br>
Notebook-4 (PredictCustomerChurnStudent_Practice.ipynb):<br> Optional: Modifying the notebook from 1- above to build different models.<br>

### Steps:
1- Create a **Project** in DSX Cloud and name it *PredictChurn* as per the screen capture below (your spark service name may be different):

![Create the project](../Images/CreateProject.png?raw=true)

<br>

2- Within the *PredictChurn* project, **add a Notebook** and choose to import it from this **URL** 
https://raw.githubusercontent.com/DScienceAtScale/DSX/master/PredictCustomerChurn/Cloud/PredictCustomerChurnStudent_Learn.ipynb
(Give a meaningful name to the notebook as well such as BuildChurnModel). Check the screen capture below for guidance:

  ![Add a notebook](../Images/create_notebook_URL.png?raw=true)
  
3- Work through the "*PredictCustomerChurnStudent_Learn*" notebook which is Notebook-1 in the list above.<br><br>
4- Add the "*Predict Churn - Score New Data*" notebook into your *PredictChurn* project and work through the notebook.  The **URL** is https://raw.githubusercontent.com/DScienceAtScale/DSX/master/PredictCustomerChurn/Cloud/PredictChurnScoreNewData.ipynb
<br/><br>
5- Add the "*	PredictChurnDeploytoWML.ipynb*" notebook into your *PredictChurn* project and work through the notebook.  The **URL** is https://raw.githubusercontent.com/DScienceAtScale/DSX/master/PredictCustomerChurn/Cloud/PredictChurnDeploytoWML.ipynb
<br/>

### Optional Lab Exercises

#### 1. Inject a new transformer and building a LogisticRegression model
- Add the "*PredictCustomerChurnStudent_Practice*" notebook into your *IntroToNotebooks* project and work through the notebook.  The **URL** is https://raw.githubusercontent.com/DScienceAtScale/DSX/master/PredictCustomerChurn/Cloud/PredictCustomerChurnStudent_Practice.ipynb

- Follow the instructions in the notebook and work through it.

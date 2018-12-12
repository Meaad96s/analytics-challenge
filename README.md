# Analytics-challenge
A challenge by IBM for STC Hackathon. The challnge starts from 1:00PM to 2:30PM.

## Challenge Summary
The challenge is to build a machine learning model to predict customer churn. The model helps the company to know the probability of losing customers.

## Pre-requisites
* **IBM Cloud account:**  An account must exist to use the platform, create an account [here](https://ibm.biz/Bd2DjV).
* **Watson Studio service instance:** A service instance must exist to be able to use **Jupyter notebook or SPSS Modeler**.
Create a service [here](https://console.bluemix.net/catalog/services/watson-studio)
* **Cloud Object Storage:** A service instance must exist to be used for storage.
Create a service [here](https://console.bluemix.net/catalog/services/cloud-object-storage)
* **Watson Machine Learning** Create a service [here](https://console.bluemix.net/catalog/services/machine-learning).


## Challenge Dataset
Download the telco customer churn dataset from [here](https://github.com/Meaad96s/analytics-challenge/blob/master/Telco-Customer-Churn.csv)


## Deliverables
1. Machine learning model.
2. Dashboard consisting of at least 2 charts of 2 variables or more.

## Judging Criteria
1. Highest model accuracy, preferably above 80%.
2. Insightful charts.
3. Priority is given to temas who first complete the challenge.

## How to start

### Create a Standard Project in Watson Studio
From the Get Started page, select **Create a Project**

![](https://user-images.githubusercontent.com/20974667/48708691-4a9b6880-ec14-11e8-8936-64d0ec4f6b8b.png)

Then Choose the **Standard plan**

![](https://user-images.githubusercontent.com/20974667/48708692-4a9b6880-ec14-11e8-88a6-928cc5646f13.png)

![](https://user-images.githubusercontent.com/45757604/49737461-01cc5200-fc9e-11e8-8c48-febd0e8080ec.png)
* Make sure a cloud storage instance exists, or add a new **IBM Cloud Object Storage** instance by clicking on **Add** under Select storage service.

### Upload Dataset to the Project

Under the **Asset** tab in the project, choose this icon <img width="39" alt="dataicon" src="https://user-images.githubusercontent.com/20974667/47075498-5b1b8600-d205-11e8-957c-10fa11498354.PNG"> on the right to upload the dataset to the platform.
* Click browse to navigate your folders where the dataset set can be found, select file **train.csv**.
* After it's uploaded, it will be listed in **Data asset**.

![](https://user-images.githubusercontent.com/45757604/49737597-566fcd00-fc9e-11e8-891f-62684bb66f5d.png)
![](https://user-images.githubusercontent.com/45757604/49737598-57086380-fc9e-11e8-9e11-76158cfdf895.png)
![](https://user-images.githubusercontent.com/45757604/49737599-57086380-fc9e-11e8-93bd-a009f98d653d.png)


### A. Add Modeler Flow to the Project
From the **+ Add to project** up in the toolbar.
![screenshot 94](https://user-images.githubusercontent.com/45757604/49737601-57a0fa00-fc9e-11e8-83f0-d3a1bc914850.png)
![screenshot 95](https://user-images.githubusercontent.com/45757604/49737604-58399080-fc9e-11e8-9266-e624b4f15626.png)
![screenshot 96](https://user-images.githubusercontent.com/45757604/49737608-58399080-fc9e-11e8-9d2c-0de796fff8a9.png)

Congratulations! Now you have the Modeler Flow Canvas.
![screenshot 97](https://user-images.githubusercontent.com/45757604/49737609-58d22700-fc9e-11e8-8739-fdb47bcf1049.png)



### B. Add Modeler Flow to the Project
From the **+ Add to project** up in the toolbar.
![screenshot 1](https://user-images.githubusercontent.com/45757604/49797643-1fa6bf00-fd51-11e8-851f-d1472fd23229.PNG)
![screenshot 2](https://user-images.githubusercontent.com/45757604/49797660-2a615400-fd51-11e8-9481-20bc30d93fc2.PNG)
![screenshot 3](https://user-images.githubusercontent.com/45757604/49797662-2cc3ae00-fd51-11e8-996f-e1948199a40e.PNG)

Congratulations! Now you have the Jupyter Notebook ready.
![screenshot 4](https://user-images.githubusercontent.com/45757604/49797666-2f260800-fd51-11e8-818b-84b434321fc4.PNG)

![congrats](https://user-images.githubusercontent.com/20974667/49898293-b070be00-fe69-11e8-8a74-51c9f67e8111.gif)

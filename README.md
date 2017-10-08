# CSC 591 - Algorithms for Data-Guided Business Intelligence - Capstone Project

## BUSINESS VALUE
Key for an organization's success lies in attracting and retaining top talent.  It is important for a company to determine which factors keep employees at the company and which prompt others to leave.   
 
Hiring and training the employees takes up a large portion of the budget. Therefore, by knowing what factors influence attrition rate, the company will be able to save lot of resources like time, money. High employee turnover affects a company's bottom line. It has been estimated that it costs nearly twice the salary of an employee to find a replacement and train them. Attrition can also damage the morale among the remaining employees or can lead to a chain reaction causing more number of employees to leave the company. Moreover, when an employee leaves the organization suddenly, there is no time left for the company to look for another replacement and conduct the hiring process again, from scratch. 
 
We propose to build a model that predicts the factors that influence attrition rate, which need to be addressed by a company, in order to preserve its resources.  
The dataset that we are using has employees' details such as years at a company, percentage salary hike, marital status, business travel, etc. We try to find the factors and compare its influence on attrition rate. 
 

Problem Statement: Identify the important features and their influence on attrition rate 

## Setup

* Install the required dependencies using the following commands (for Ubuntu 14.04 Base):

    - Numpy
    - pip
    - wheel
    - pandas
    - Seaborn
    - matplotlib
    - Plotly
    - scikit-learn
    - keras

	```
	sudo apt-get install python numpy
    sudo apt-get -y install python-pip
    sudo pip install wheel
    sudo pip install pandas
    sudo pip install seaborn
    sudo apt-get install python-matplotlib
    sudo pip install plotly
    sudo pip install -U scikit-learn
    sudo pip install keras

	```
	
* Run the python file using the following command:

	```
	python RF_GBM.py
	```


## Plots

### Correlation Matrix

![screenshot 1](https://github.com/Prashanth261993/IBM-Attrition/blob/master/CorrelationMatrix.png)

### Feature Density Distribution
![screenshot 2](https://github.com/Prashanth261993/IBM-Attrition/blob/master/FeatureDensityDistribution.png)

### Gender vs Income
![screenshot 3](https://github.com/Prashanth261993/IBM-Attrition/blob/master/Gender_Income.png)



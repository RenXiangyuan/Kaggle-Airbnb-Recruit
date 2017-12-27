# Airbnb-New-User-Bookings 
The objective of this project is to use the data provided by Airbnb to predict the most likely location that new customers will choose for their first booking given information about their social background. This solution will help to personalize the Airbnb experience, decrease booking search times, increase efficiency, and predict the general demand across different locations. The data is publicly available on the Kaggle website as a competition hosted by Airbnb. This type of data is significantly important because it will help people understand the categories of countries that people who share with similar backgrounds generally enjoy visiting for their first booking. This analysis will also help Airbnb distribute housing more accurately based on demand, which will allow higher customer satisfaction rates. 

## Get Started
Please follow this instruction to run the code on your local machine.

### Prerequisites
* Python 2.7
* Jupyter Notebook

### Dependency Library
numpy : 0.7.0       
pandas : 0.20.3  
matplotlib : 2.1.0        
seaborn : 0.8.0         
ipywidgets : 7.0.0            
xgboost 

RandomizedLogisticRegression from sklearn.linear_model

RandomForestClassifier from sklearn.ensemble

### Dataset Resource: https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings/data
Note: Please download the data and put them in folder /input

### Install and Run the code
Please download the code from https://github.com/pengzai6666/Airbnb-New-User-Bookings.git

Run Team8_Data_Engineering.ipynb for data engineering part (visualization)

If you are also interested in the prediction part, we provide the preprocessing code at Team8_Preprocessing.ipynb.


### Basic Work Follow
In this project, both data engineering (80 %) and destination prediction (20 %) are done.

##### Data Engineering Part: 
##### Note: most of the plots are implemented in an interactive way as discussed in the class. Please re-run the codes to visualize the iwidgets.

Here is the basic workflow:
- Visualization of Population in Destination Countries
- Visualization of Gender and Destination Related Stuffs
- Country destination booking ratio of [destination] vs [All other countries excluding Not Defined]
- Comparison of different country bookings with a set age threshold
- Visulization of Affiliate Related Stuffs
- Data Analysis of Affiliate Related Stuffs
- Time Interval Analysis (Time Interval is the time one user spends on Airbnb)
- Action Type Analysis (Action Type is the action one user is recorded in his activity log)
- Device Type Analysis (Device Type is the device that one user used to perform his action)
- Action Type Analysis regarding time elapsed
- Destination Distribution regarding to the frequency of the given action type

##### Destination Prediction Part:

Here is the basic workflow:
- Preprocessing the dataset: which can be found in Team8_Preprocessing.ipynb
- Feature Selection: the functions we use are in Team8_Feature_Selection.ipynb
- Predictive Model: we just refer to the code of some users on kaggle, here are the links:
https://www.kaggle.com/svpons/script-0-8655

https://github.com/svegapons/kaggle_airbnb

https://github.com/davidgasquez/kaggle-airbnb/blob/master/notebooks/User%20Data.ipynb


### All the codes are tested on Conda 4.3.29 with Python 2 on Mac

If there is anything wrong during the code testing, please contact s7qin@eng.ucsd.edu directly. Thanks

### Authors: Pryor Vo, Xiangyuan Ren, Peng Chen, Ge Chang, Siqi Qin



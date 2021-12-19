# AI/ML Project: BigMart Sales Prediction 🏪🛍️🛒
<p align="center"><img src="https://user-images.githubusercontent.com/54996245/145608240-38d9cd36-4fb2-4ea6-aaf6-abbc8446fa2d.jpg" style="width: 1000px;"/></p>

### Description:

The data scientists at BigMart have collected 2013 sales data for numerous products across many stores in different cities. Also, certain attributes of each product and store have been defined. 

The aim is to build a predictive model and find out the sales of each product at a particular store.
Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales.

### Acknowledgement: 
The dataset is taken from Kaggle:\
https://www.kaggle.com/yasserh/bigmartsalesdataset

### Objective:
- Understand the Dataset & cleanup (if required).
- Build Regression models to predict the sales of the products.
- Also evaluate the models & compare thier respective scores like R2, RMSE, etc.

### Stractegic Plan of Action:
  
**We aim to solve the current problem statement by creating plan of action, Here are some of the necessary steps:**
1. Data Exploration
2. Exploratory Data Analysis (EDA)
3. Data Pre-processing
4. Feature Selection/Extraction
5. Predictive Modelling
6. Project Outcomes & Conclusion

### Some Visuals of the Project:
**1. Target Variable Distribution**

<p align="left"><img src="https://user-images.githubusercontent.com/54996245/146248720-5c0b43f2-c74b-4c98-b106-09e2c64a7d01.png" /></p>

**2. Categorical Feature-set Distribution**
  
![image](https://user-images.githubusercontent.com/54996245/146248730-2ffb50d3-3f14-4ce8-bfea-c36926165861.png)

**3. Numerical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/146248771-767371ed-a2b4-4a16-ba3e-204b33ce4ad1.png)
![image](https://user-images.githubusercontent.com/54996245/146248787-be1e53df-0c72-4a6a-aa0a-501f919de28b.png)

**4. Relationship between the Feature-set**

![image](https://user-images.githubusercontent.com/54996245/146248804-a738086a-a887-494b-945a-475fe45cd322.png)

**5. Data Retention after preforming preprocessing step**

![image](https://user-images.githubusercontent.com/54996245/146248841-e45ac965-803b-4454-afc5-2646ca1429c7.png)

**6. Correlation Plot**
  
![image](https://user-images.githubusercontent.com/54996245/146248855-54e87d90-57a3-4d7a-83c4-567b0e3baf59.png)

**7. Feature Selection/Extraction - VIF, RFE & PCA Techniques:

![image](https://user-images.githubusercontent.com/54996245/146248879-d1e18afe-9347-4b2b-8af1-18ef7fd4a451.png)
![image](https://user-images.githubusercontent.com/54996245/146248896-40276b9e-821b-408f-976f-fec63686371d.png)
![image](https://user-images.githubusercontent.com/54996245/146248913-97c2bbe5-ec90-4ff4-a4d9-a9f68cce49b7.png)
![image](https://user-images.githubusercontent.com/54996245/146248935-b6f25999-8cec-4bbd-83ce-309f6fcf8a95.png)

**8. Multiple Linear Regression Prediction & Residual Normality Check**
  
![image](https://user-images.githubusercontent.com/54996245/146249029-29146a4e-4c3c-43d8-b4f8-34207c5f4ba4.png)

**9. Polynomial Degrees Comparison**

![image](https://user-images.githubusercontent.com/54996245/146249045-9e785414-b730-49ea-9d40-4c8e9c085faf.png)

**10. Predictions**

![image](https://user-images.githubusercontent.com/54996245/146249065-1cf886ef-2650-4ef0-889f-b41bdbf29ec3.png)

**11. ML Algorithm's Scores Comparison (R2& RMSE) for the Ad Budge Dataset**

![image](https://user-images.githubusercontent.com/54996245/146249091-77a7dee1-5470-4865-8a60-21fec31d4329.png)
![image](https://user-images.githubusercontent.com/54996245/146249109-8bbf8304-0355-4340-9ce1-175fac7de0f6.png)

### Here are some of the key outcomes of the project:
- The Dataset was quiet small with just 8523 samples & after preprocessing 1.7% of the datasamples were dropped. 
- Visualising the distribution of data & their relationships, helped us to get some insights on the feature-set.
- The features had high multicollinearity, hence in Feature Extraction step, we shortlisted the appropriate features with VIF Technique.
- Testing multiple algorithms with default hyperparamters gave us some understanding for various models performance on this specific dataset.
- While, Polynomial Regression (Order-3) was the best choise, yet it is safe to use multiple regression algorithm, as their scores were quiet comparable & also they're more generalisable.

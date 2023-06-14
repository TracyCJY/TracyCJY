# Portfolio
Hello and welcome to my portfolio! My name is Jiaying Cui(Tracy), a skilled and dedicated Data Analyst with a passion for extracting meaningful insights from complex data sets. In this portfolio summary, I will provide an overview of my expertise, highlight key skills, and showcase some of the notable projects I have successfully completed.
# Get to Know Me
With a Master's degree in Electronic Commerce and Internet Computing from The University of Hong Kong and 2 years of experience in the e-commerce field, I have gained my abilities in data analysis, business intelligence, and data-driven decision-making. My technical skill set includes Python, SQL, operational analysis models, and proficiency in data visualization tools like Tableau.
# My Professional Experience
I used to work as Campaign Analyst in Shopee where I played a vital role in the operational activities of shopee’s Poland cross border market site. My responsibilities included end-to-end campaign management, which involved using tools like SQL to acquire data, python and excel to analyze data and conduct business reports. Additionally, I was also in charge of building key metrics system and automated data dashboards.  Prior to this role at shopee, I gained valuable experience as e-commerce operation specialist in Dmall, a company based in Beijing. There, I excelled in managing O2O activities for a major seller and wasr in charge of user management and analysis, and also produced monthly reports focusing on optimizing operational strategies.Furthermore, I had the opportunity to intern as an E-commerce Operation Intern at JD.com.
# My Past Projects
## Python
### Bank Deposit Subscription Prediction 
**Code:** [Bank Deposit Subscription Exploratory Data Analysis](https://github.com/TracyCJY/-Bank-Saving-Deposit-Subscription-Plan-Campaign/blob/main/Bank_Deposit_Subscription_EDA.ipynb)
[Bank Deposit Subscription Prediction](https://github.com/TracyCJY/-Bank-Saving-Deposit-Subscription-Plan-Campaign/blob/main/Bank_Deposit_Subscription_Prediction.ipynb)

**Goal**: To make use of the dataset to predict if the client will subscribe (or not subscribe) to the new term saving deposit plan in order to inform the bank’s management executive.

**Description:** 

**1. Exploratory Data Analysis: **    
- Classify the 17 indicators into 5 parts with more business sense
  - Client Basic Information,
  - Client Financial Information,
  - Client Contact Information,
  - Campaign Information,
  - Target Value.
- Three Dimensional Analysis: univariate analysis, bivariate analysis, multivariate analysis. 
- Through the detailed EDA analysis, provide the data insights to the marketing team with relevant suggestions for the next marketing activities.

**2. Building Models：**
- Focuses on selecting features using RFE method with GradientBoostingClassifier(). Various models （'Logistic Regression','DecisionTreeClassifier','SGDClassifier', 'KNeighborsClassifier', 'SVCModel','Random Forest','XGBoost','GradientBoostingClassifier','LightGBM','MLP'） are then selected and optimized for performance, according to Accuracy,Precision, Recall, F1 Score, AUC.
- Three specific models (Random Forest, LightGBM, and MLP) are compared based on their performance using the AUC metric. 

**3. Fine Tune Models** 
Use Grid Search to choose the best hyperparameters

**4. Alleviate Imbalance Result Analysis**
- **SMOTE** is applied to Model 1-Random Forest to alleviate imbalance issue. 
- **Class Weight Adjustment** is applied to Model 2-LightGBM to alleviate imbalance issue. 
- **Custom Loss Function** is applied to MLP to alleviate imbalance issue.

**5. Ensemble Learning- Voting Classifier**
The Voting Classifier technique is employed to combine the predictions from the three models.

**6. Recommendation**
Recommendations are provided regarding the dataset and marketing campaign strategies, including customer segmentation, expanding marketing channels, refining phone contact skills, targeting potential clients, and adjusting marketing time.

**Skills:** Explorotary Data Analysis, Data Cleaning, Feature Engineering, Imbalance Alleviate

**Technology:** RFE, Random Forest, LightGBM, Neural Network-MLP, Grid Search, Random Search, SMOTE, Voting Classifier

**Result:** The ensemble learning voting classifier was used to combine Random Forest and LightGBM models, resulting in the best performance with a Precision value of 0.56, Recall value of 0.73, F1 Score of 0.64, and AUC value of 0.935.

### Marketing Campaign Analysis Using Uplift Model with Python
**Code:**[Marketing_Promotion_Campaign_Uplift_Modelling](https://github.com/TracyCJY/Uplift-Model/blob/main/Marketing_Promotion_Campaign_Uplift_Modelling.ipynb)    

**Goal:** To perform an uplift analysis for two marketing ways: 'Buy One Get One' and 'Discount'. The analysis aims to understand the effectiveness of different marketing method in generating a positive response from customers.   

**Description:** This project performs an uplift analysis using XGBoost and provides insights into the effectiveness of different offers in generating desired outcomes. The Qini curves help visualize the uplift performance for the treatment groups, allowing for further analysis and decision-making.

**Skills:** Marketing Analysis, Uplift Model,Data Analysis

**Technology:** Python, Pandas, Numpy, Seaborn,Matplotlib, XGBoost

**Result:** Define Uplift Score to evaluate marketing performance, using XGBClassifier() to build model. Calculate and Visualize QINI Curve( Area Under Uplift Curve). The result shows that "Buy One Get One" Campaign has boosted user conversion, however, the "Discount" Campaign‘s effect is not obvious.




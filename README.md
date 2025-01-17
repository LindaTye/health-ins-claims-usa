# Capstone on predicting heath insurance claims in USA

## _Predicting health insurance claims in USA_

[![Image from Gyazo](https://i.gyazo.com/5fc3cefdb31657a4194a9d5054144e3a.jpg)](https://gyazo.com/5fc3cefdb31657a4194a9d5054144e3a)
#

#### Description of Dataset

This dataset contains insightful information related to insurance claims, giving us an in-depth look into the demographic patterns of those receiving them. The dataset contains information on patient age, gender, BMI (Body Mass Index), blood pressure levels, diabetic status, number of children, smoking status and region. Dataset consists of 1,340 rows and 11 columns.

#### Objective
* The main objective of this project is to predict future insurance claims and identify factors that lead to higher healthcare costs, which could result in significant cost reductions for insurance providers in the USA, and the role of artificial intelligence (AI) in machine learning with regards to healthcare insurance claim processing. 

#### Data Cleaning
* 8 rows were removed as the null values from the age and region columns would affect the dataset. The index and patient ID columns were also removed as these were unnecessary for EDA. 

[![Image from Gyazo](https://i.gyazo.com/7b22f20f9d03982d20d0cbe32f1a66d1.png)](https://gyazo.com/7b22f20f9d03982d20d0cbe32f1a66d1)
[![Image from Gyazo](https://i.gyazo.com/2eef2ad583c5c7045f82b1ee85f13d15.png)](https://gyazo.com/2eef2ad583c5c7045f82b1ee85f13d15)
[![Image from Gyazo](https://i.gyazo.com/39fd44628ebc2cb89c6432922ba55c74.png)](https://gyazo.com/39fd44628ebc2cb89c6432922ba55c74)

#### Observations
* Diabetic patients account for 47.5% of the claimants, nearly half, compared to non-diabetic patients at 52.5%
* Male represents 50.3% and females slightly lower at 49.7% suggesting an almost even split in insurance claim ratios between the two genders
* In the smoker category, smokers account for 49.5% and non-smokers 50.5% request for the insurance claim
* Southeast USA region report the highest number of insurance claims, followed by those in the Northwest, Southwest, and Northeast
* Northeast USA is less likely to file insurance claims than other regions
* In the correlation chart for all the variables there is strong correlation between a smoker and claim amount shows that smokers tend to have higher insurance claims 
* We see the moderate correlation with people who smokes and blood pressure
* Random Forest Regressor (RFR) shows the highest R-squared (0.82) and adjusted R-squared (0.81), this high value suggests that the RFR is very effective in capturing the underlying patterns in the data
* Whether someone smokes or not strongly affects their insurance claims. Non-smokers have a significant impact in reducing claims. This is the most important factor by a large margin.

#### Key Insights
Please refer to the [powerpoint pressentation](https://github.com/LindaTye/health-ins-claims-usa/blob/main/Linda_Tye_Capstone_Presentation.pptx) for more information 
* Enhanced Decision-Making with AI: RFR enables better risk assessment, pricing strategies, and targeted health interventions.
* Critical Role of Key Variables: Smoking, BMI, and blood pressure significantly impact insurance claim predictions and policy strategies.
* Improved Efficiency and Cost Savings: AI reduces prediction errors, optimizes claim processing, and drives cost savings.
* Future Opportunities for AI: AI can enhance resource allocation, streamline processes, and ensure fair pricing in USA healthcare insurance.


#### Connect with Me!
Like my work? Send me a DM on [Linkedin!](https://www.linkedin.com/in/linda-tye-johansson-74217642/)

# Heal Me - ( Healing in progress )

## Abstract

The project aimed to tackle the growing challenge of diabetes by leveraging a comprehensive data analytics approach. The core problem addressed was the intricate dynamics of diabetes, marked by the interaction of various health indicators, lifestyle factors, and socio-demographic characteristics. Through detailed analysis, the objective was to reveal key risk factors, enhance the predictability of diabetes occurrences, and formulate targeted health interventions. The methodology encompassed extensive data selection and preprocessing, feature selection and engineering, predictive algorithm selection for model development and evaluation, and deployment and thorough documentation of the processes involved to develop a foundation for follow-on research.

## Introduction

The prevalence of diabetes has been on a consistent rise globally, positioning it as a critical public health concern. As a complex, chronic illness, diabetes requires continuous medical care and patient self-management education to prevent acute complications and reduce the risk of long-term complications. Introducing data analytics into healthcare provides an unprecedented opportunity to address this challenge, leveraging the vast amounts of data generated in medical contexts to gain insights, predict trends, and guide interventions. We have considered a comprehensive dataset aimed at understanding diabetes dynamics through data analytics. The dataset encompasses a wide array of health-related factors, lifestyle choices, socio-demographic information, and self-reported health statuses. With over 250k+ records, it provides a robust foundation for our analysis.

## Dataset Link
[Diabetes Health Indicators Dataset](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)

## Background and Rationale

Diabetes is a leading cause of mortality and a major contributor to the burden of chronic disease worldwide. Its management and prevention necessitate a comprehensive understanding of its dynamics, including how lifestyle choices, socio-demographic factors, and various health indicators contribute to its development and progression. The rationale for this project stems from the potential of data analytics to unravel these complex dynamics, offering a pathway to identify at-risk populations, predict disease onset, and tailor interventions more effectively than ever before. By harnessing the power of data, healthcare providers can move towards a more proactive and personalized healthcare model.

## License
This dataset is provided under the Creative Commons CC0 1.0 Universal license. This means that it is free to use, modify, and distribute the dataset for any purpose, even commercially, without requiring permission from the creator. For more information, please refer to the [full license text](https://creativecommons.org/publicdomain/zero/1.0/).

## Research
The research underpinning this project encompasses a thorough review of existing literature on diabetes and its risk factors, exploring data analytics methods in healthcare, and examining case studies where data-driven approaches have successfully informed health interventions. This foundational research has highlighted the gaps in current diabetes management strategies, particularly identifying high-risk individuals early and customizing preventive measures.

## Project Objectives
The objectives of this project are multifold:
To explore and analyze the relationships between health indicators, lifestyle factors, socio-demographic characteristics, and the prevalence of diabetes.
To identify key risk factors associated with the development of diabetes.
To develop and evaluate predictive models that can accurately forecast the onset of diabetes.
To provide actionable insights and recommendations for healthcare interventions to mitigate the impact of diabetes.
These objectives aim to leverage data analytics to enhance the understanding and management of diabetes, ultimately contributing to better health outcomes for affected populations.

## Problem Space
The problem space of this project is defined by the need to understand the multifaceted dynamics of diabetes within the broader context of rising chronic disease prevalence. Despite extensive research and healthcare efforts, diabetes remains a significant public health issue, with many individuals remaining undiagnosed until complications arise. The challenge lies in effectively integrating and analyzing diverse data sources to uncover the underlying patterns and risk factors of diabetes. Furthermore, developing predictive models that are both accurate and practical for healthcare settings presents its own set of challenges, requiring careful consideration of the models’ interpretability and applicability. This project aims to navigate these complexities, offering a data-driven approach to illuminate the path toward improved diabetes prevention and management.

## Primary User Stories:
Based on the problem space, we designed user stories based on potential customers of our findings to help guide our development of user stories:
1. “As a User, I want to access easy-to-understand visualizations of diabetes data and trends to increase my awareness and knowledge of the disease.” 
2. “As a Patient, I want to understand my risk factors for diabetes, so I can take preventive measures to avoid the disease.”
3. “As a Healthcare Provider, I want to access a dashboard that highlights patients at high risk for diabetes so that I can prioritize early intervention.”
4. “As a healthcare provider, I want to use predictive analytics to forecast potential diabetes complications in patients and improve treatment plans and outcomes.”

Based on the user context and value proposition, we developed the following primary user story to guide our project:
1. “As a data scientist, I want to collect comprehensive datasets on diabetes, including health indicators, lifestyle factors, and socio-demographic characteristics, so that we have a robust foundation for analysis.”
2. “As a data analyst, I want to select the most predictive features and engineer new variables to improve our model's accuracy in predicting diabetes risk.”
3. “As a machine learning engineer, I want to develop and evaluate predictive models to forecast diabetes occurrences and guide interventions accurately.”
4. “As a project manager, I want to ensure the deployment of our predictive models and the completion of comprehensive documentation for future reference and reproducibility.”

## Solution Space
Our development approaches the support to diabetes management and prevention, presenting a cutting-edge solution grounded in the robust analysis of vast datasets. Through machine learning and data analytics integration, our system excels in identifying individuals at heightened risk of developing diabetes. This capability hinges on evaluating various variables, including health indicators, lifestyle choices, and socio-demographic details. This capability is a technical achievement and a gateway to personalized healthcare, offering significant value to a diverse user base encompassing healthcare professionals and patients.

For healthcare professionals, this solution is innovative, enabling the customization of prevention and treatment plans that respond to the unique risk profiles of their patients. This individualized approach not only enhances patient care but also promises to reduce the prevalence of diabetes-related complications, marking a shift towards more effective and efficient healthcare delivery. On the other hand, patients are empowered through personalized insights into their health, guiding them toward informed lifestyle modifications that could significantly lower their diabetes risk. 

Our system is a catalyst for change, aiming to revolutionize diabetes management and the use of machine learning in healthcare by shifting the focus from reactive treatment to proactive prevention. It's designed to foster a deeper understanding of diabetes risk factors among its users, promoting a shift in healthcare practices and lifestyle choices. Delivering precise, actionable predictions encourages a preventative mindset, ultimately striving to improve health outcomes for at-risk individuals and reduce the overall strain on healthcare systems. 

## Product Vision - Sample scenarios

1. Patients
For: Patients Concerned About Diabetes
Who: Are seeking to understand their risk and take preventative action
The: Predictive Diabetes Management System
Is a: User-friendly platform providing personalized risk assessments and recommendations
That: Empowers individuals with actionable insights into their health, guiding them towards lifestyle changes that can significantly reduce their risk of developing diabetes.
Unlike: Generic health advice found online or broad public health recommendations,
Our product: Tailors its guidance to the individual's specific health indicators, lifestyle factors, and socio-demographic characteristics, making prevention strategies more relevant and effective.
Caveats: Success in prevention requires users to actively engage with the system's recommendations and may necessitate lifestyle changes that the individual must be willing and able to make.

2. Healthcare Providers
For: Healthcare Providers
Who: Manage patients at risk of or currently dealing with diabetes
The: Predictive Diabetes Management System
Is a: Comprehensive data-driven solution
That: Utilizes advanced analytics and machine learning to identify individuals at high risk of developing diabetes, enabling early and personalized intervention strategies.
Unlike: Traditional diabetes management approaches that often rely on generalized guidelines and reactive treatments,
Our product: Offers a proactive, personalized healthcare approach, focusing on prevention and early intervention based on individual risk profiles.
Caveats: Effective system use requires access to detailed patient data and ongoing engagement from healthcare providers and patients to ensure the accuracy and relevancy of the predictions and recommendations.

## Scenario #1
A primary care physician in a community health center frequently encounters patients with prediabetes and risk factors for developing type 2 diabetes. Despite her best efforts, providing personalized advice based on traditional risk assessments has been challenging due to her patients' diverse backgrounds and health profiles.
With the Predictive Diabetes Management System. HealMe, the primary care physician, can now input her patients’ health indicators, lifestyle information, and socio-demographic data into the system, which then calculates a personalized risk score and outlines specific intervention strategies. For a patient like John Doe, a 45-year-old with a family history of diabetes, borderline high blood glucose levels, and a sedentary lifestyle, the system suggests a detailed plan that includes dietary changes, a tailored exercise regimen, and regular monitoring of blood glucose levels.
This scenario highlights how healthcare providers can leverage the system to deliver early, personalized interventions to patients at high risk of developing diabetes, potentially preventing the onset of the disease and improving overall health outcomes.

## Scenario #2
A public health official responsible for managing diabetes prevention programs in her city. The rising rates of diabetes, particularly in certain communities, have prompted her to seek more effective strategies for targeting public health interventions.
Using the Predictive Diabetes Management System, HealMe, public health officials can analyze city-wide health data to identify neighborhoods with the highest risk factors for diabetes. The system reveals that communities with limited access to healthy food options and safe exercise facilities have higher incidences of diabetes. Based on these insights, public officials initiate a multi-faceted public health campaign that includes opening new community gardens, organizing free fitness classes in local parks, and partnering with grocery stores to offer discounts on healthy foods.
This scenario showcases how policymakers and public health officials can use the system to identify at-risk populations and implement targeted interventions, thereby addressing the root causes of diabetes at a community level and fostering healthier environments.

## Definition of Terms:
System - Referring to the Predictive Diabetes Management capability: HealMe
Analytics - The systematic computational analysis of data or statistics used here to identify patterns relevant to diabetes risk.
Data Preprocessing - The cleaning and organizing of raw data to make it suitable for a machine learning model.
Diabetes - A chronic condition that affects how the body processes blood glucose (sugar).
Health Indicators - Metrics or measurements that provide insights into the health status of an individual or population, such as blood pressure, cholesterol levels, and body mass index (BMI).
Lifestyle Factors - Behaviors or habits of an individual that impact their health, including diet, physical activity, smoking, and alcohol consumption.
Machine Learning - A branch of artificial intelligence (AI) that focuses on building systems that learn from and make data-based decisions.
Model Deployment - Integrating a machine learning model into an existing production environment to make predictions or decisions based on new data.
Predictive Model - A statistical model or machine learning algorithm that predicts future outcomes based on historical data.
Primary Care Physician - A healthcare professional who acts as the first point of consultation for all patients within the healthcare system.
Public Health Official - An individual responsible for maintaining and improving the health of populations by promoting healthy lifestyles, researching disease and injury prevention, and detecting, preventing, and responding to infectious diseases.
Risk Factors - Attributes, characteristics, or exposures that increase the likelihood of developing a disease or injury.
Socio-Demographic Characteristics - The attributes of a population, including factors such as age, race, employment status, income level, and educational attainment, that influence health outcomes. 

## Data Acquisition
### Overview:
We have considered a comprehensive dataset aimed at understanding diabetes dynamics through data analytics. The dataset encompasses various health-related factors, lifestyle choices, socio-demographic information, and self-reported health statuses. With over 250k+ records, it provides a robust foundation for our analysis.

Sure, here are the serial numbers for the listed items:

1. Data Set Name: Diabetes Health Indicators Dataset
2. Data Set Location: Diabetes Health Indicators Dataset
3. Data Set Description: The dataset provides a comprehensive collection of health-related factors, lifestyle choices, socio-demographic information, and self-reported health statuses. With over 250k+ records, it offers a rich foundation for our analysis aimed at understanding diabetes dynamics.
4. Data Set License: Creative Commons CC0 1.0 Universal License, allowing for free use, modification, and distribution without requiring permission from the creator. License link

Field Descriptions:
5. Response Variable / Dependent Variable:
   - (Ever told) you have diabetes (If "Yes" and respondent is female, ask "Was this only when you were pregnant?". If Respondent says pre-diabetes or borderline diabetes, use response code 4.) --> DIABETE3
6. Independent Variables:
   - High Blood Pressure: Adults who have been told they have high blood pressure by a doctor, nurse, or other health professional --> _RFHYPE5
   - High Cholesterol: Have you EVER been told by a doctor, nurse or other health professional that your blood cholesterol is high? --> TOLDHI2
   - Cholesterol: Cholesterol check within past five years --> _CHOLCHK
   - BMI: Body Mass Index (BMI) --> _BMI5
   - Smoking: Have you smoked at least 100 cigarettes in your entire life? [Note: 5 packs = 100 cigarettes] --> SMOKE100
   - Other Chronic Health Conditions: (Ever told) you had a stroke. --> CVDSTRK3
   - Coronary Heart Disease or Myocardial Infarction: Respondents that have ever reported having coronary heart disease (CHD) or myocardial infarction (MI): --> _MICHD
   - Physical Activity: Adults who reported doing physical activity or exercise during the past 30 days other than their regular job --> _TOTINDA
   - Diet:
     - Consume Fruit 1 or more times per day --> _FRTLT1
     - Consume Vegetables 1 or more times per day --> _VEGLT1
   - Alcohol Consumption: Heavy drinkers (adult men having more than 14 drinks per week and adult women having more than 7 drinks per week) --> _RFDRHV5
   - Health Care: Do you have any kind of health care coverage, including health insurance, prepaid plans such as HMOs, or Government plans such as Medicare, or Indian Health Service? --> HLTHPLN1
   - Was there a time in the past 12 months when you needed to see a doctor but could not because of cost? --> MEDCOST
   - Health General and Mental Health: Would you say that, in general, your health is: --> GENHLTH
   - Now thinking about your mental health, which includes stress, depression, and problems with emotions, for how many days during the past 30 days was your mental health not good? --> MENTHLTH
   - Now, thinking about your physical health, which includes physical illness and injury, how many days during the past 30 days was your physical health not good? --> PHYSHLTH
   - Do you have serious difficulty walking or climbing stairs? --> DIFFWALK
   - Demographics: Indicate the sex of the respondent. --> SEX
   - Fourteen-level age category --> _AGEG5YR
   - What is the highest grade or year of school you completed? --> EDUCA
   - Is your annual household income from all sources: (If the respondent refuses at any income level, code "Refused.") --> INCOME2

## Data Context:
The Behavioral Risk Factor Surveillance System (BRFSS) is an annual health-related survey managed by the Centers for Disease Control and Prevention (CDC). Since its inception in 1984, it has gathered data from more than 400,000 Americans annually. The survey probes into health-related risk behaviors, chronic health conditions, and usage of preventive services. For our project, we utilized the 2015 BRFSS dataset available on Kaggle, which features responses from 441,455 participants across 330 variables. These variables include direct questions posed to participants or calculated variables derived from their responses.

We focused on three specific files from this dataset:
1. diabetes_012_health_indicators_BRFSS2015.csv: This file includes 253,680 responses from the 2015 BRFSS survey. The target variable, Diabetes_012, categorizes responses into three classes: 0 for no diabetes or gestational diabetes only, 1 for prediabetes, and 2 for diabetes. This file, which exhibits a class imbalance, encompasses 21 feature variables related to the survey responses.
2. diabetes_binary_5050split_health_indicators_BRFSS2015.csv: Comprising 70,692 survey responses, this dataset is evenly split between respondents without diabetes and those with prediabetes or diabetes, hence ensuring a balanced dataset. The target variable, Diabetes_binary, is binary: 0 indicates no diabetes, and 1 indicates prediabetes or diabetes. This dataset includes 21 feature variables.
3. diabetes_binary_health_indicators_BRFSS2015.csv: Similar to the previous file, this clean dataset contains 253,680 survey responses from the 2015 BRFSS, with the Diabetes_binary target variable classifying respondents into two categories: 0 for no diabetes and 1 for prediabetes or diabetes. However, unlike the 5050 split dataset, this file is class-imbalanced and includes 21 feature variables.
These datasets were selected for their comprehensive coverage of health indicators relevant to our project's focus on diabetes.

## Data Conditioning
Data conditioning, also known as data preprocessing or data cleaning, is the process of preparing raw data for analysis by addressing issues such as inconsistencies, errors, missing values, and outliers. It involves transforming raw data into a clean, structured format that is suitable for analysis and modeling. Data conditioning aims to enhance the quality, accuracy, and reliability of the dataset, ultimately improving the validity of the insights derived from it.

## Data Quality Assessment:
The Data Quality Assessment conducted on the dataset has yielded several key findings that underscore the high quality and reliability of the data. These findings provide a solid foundation for further analysis, decision-making, and interpretation of results. 
1. Completeness: We conducted a thorough assessment of the dataset to identify any missing values across all columns. The result of this check revealed that there are no missing values present in any of the columns. Each variable in the dataset contains complete data, indicating a high level of completeness. Result : The dataset exhibits no missing values, resulting in a percentage of missing data of 0.00%. 
2. Uniqueness: As part of our data quality assessment, we focused on verifying the accuracy of BMI values within the dataset. Using an expected range of 0 to 100 for BMI values, we compared each value against this range to identify any outliers or inaccuracies. The analysis showed that all BMI values fall within the expected range. Result : There are no incorrect BMI values present in the dataset, as all values are within the expected range of 0 to 100. 
3. Accuracy: To understand the relevance of certain variables to our research questions, we examined the distribution of the 'HighBP' variable. The analysis revealed the following distribution: 144,851 instances of '0' (indicating no high blood pressure) and 108,829 instances of '1' (indicating high blood pressure). This distribution provides valuable insights into the prevalence of high blood pressure within the dataset, which is directly relevant to our research objectives. Result : The distribution of the 'HighBP' variable provides relevant information for our analysis, highlighting the prevalence of high blood pressure among individuals in the dataset.
4. Validity: Finally, we conducted a validity check for the 'PhysActivity' variable to ensure that only valid values of '0' (inactive) or '1' (active) are present. The analysis confirmed that all values in the 'PhysActivity' column adhere to the expected valid values, indicating no inconsistencies or invalid entries. Result : All values in the 'PhysActivity' column are valid, demonstrating the integrity and validity of the dataset.

In summary, the Data Quality Assessment demonstrates that the dataset is of exceptionally high quality, characterized by complete, accurate, relevant, valid, and consistent data. These findings engender confidence in the reliability of the dataset for conducting in-depth analysis, making informed decisions, and deriving actionable insights. The high-quality data serves as a cornerstone for generating sound conclusions and recommendations, thereby empowering stakeholders with the information needed for effective decision-making and strategic planning. 

## Analytics and Algorithms
In addressing the escalating public health challenge of diabetes management and prediction, the project employs sophisticated algorithms to analyze health-related data effectively. The first algorithm, Logistic Regression, categorizes individuals into non-diabetic, pre-diabetic, and diabetic statuses based on various health indicators. It achieves an accuracy of 84.83% and a ROC AUC score of 78.17%. Despite its effectiveness in identifying non-diabetic cases, it exhibits significant limitations in detecting pre-diabetic and diabetic statuses due to its linear nature and the complexity of the dataset. Key predictive features identified by this model include General Health, Age, BMI, High Cholesterol, and High Blood Pressure.
The Decision Trees algorithm, known for its clear interpretative nature, categorizes individuals by creating explicit decision pathways based on similar health indicators. This model excels in detailing the thresholds that lead to diabetes diagnoses, contrasting with the simpler, probability-based classification of logistic regression. However, it faces challenges like overfitting, especially when dealing with complex datasets, necessitating ensemble methods such as Random Forests to enhance prediction accuracy and model reliability.
Further advancing the analytical capability, the Random Forest algorithm aggregates multiple decision trees to mitigate overfitting and improve generalization capabilities on unseen data. With an accuracy slightly lower than logistic regression at 84.17%, it significantly enhances the detection of minority classes, overcoming a notable limitation of the previous models. This algorithm emphasizes the importance of various predictors, including cholesterol checks, gender differences, and socio-economic factors, which are critical in assessing diabetes risk.
The Support Vector Machine (SVM) algorithm is adept at handling the complexities of high-dimensional feature spaces, making it particularly suitable for medical datasets where binary classification is crucial. SVM operates by constructing a hyperplane that maximizes the margin between diabetic and non-diabetic classes, effectively distinguishing between the two. This method is especially beneficial for cases that lie close to these classifications' boundaries, ensuring a clearer and more definitive separation.

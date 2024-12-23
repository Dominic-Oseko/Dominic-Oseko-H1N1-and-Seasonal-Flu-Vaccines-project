# H1N1-and-Seasonal-Flu-Vaccines-project
## 1.  Project Understanding
### Overview
 This project addresses the challenge of suboptimal seasonal flu vaccine uptake, a critical public
 health issue that exacerbates morbidity, mortality, and economic burden annually. Using data
 from the National 2009 H1N1 Flu Survey, which includes demographic, behavioral, and
 attitudinal factors, the project aims to build a predictive model to identify key drivers of vaccine
 uptake. Framed as a binary classification problem, the analysis seeks to uncover actionable
 insights to inform public health strategies, improve vaccination campaigns, and enhance
 preparedness for future pandemics.
 ### Problem Statement
  Seasonal influenza vaccination is a cornerstone of public health efforts to reduce the burden of
 flu-related illness. However, vaccination rates vary significantly across different population
 groups, influenced by factors such as demographics, health behaviors, and personal beliefs.
 Public health officials face the challenge of designing targeted interventions to improve vaccine
 uptake, particularly among populations with historically low vaccination rates.
 ### Key Objective
  1. Identifying Predictors: Determine the most influential factors driving seasonal flu vaccine
 uptake.
 2. Building a Predictive Model: Develop a binary classification model to predict vaccination
 status accurately.
 3. Actionable Insights: Provide evidence-based recommendations to public health officials for
 improving seasonal flu vaccination rates.
### Research Question
 Can we predict whether an individual received the seasonal flu vaccine based on their
 demographic characteristics, health behaviors, and opinions about vaccines?
 ### Metric of Success
  By achieving these objectives, the project will contribute to a deeper understanding of
 vaccination behavior and inform public health campaigns to increase seasonal flu vaccine
coverage. These insights can also be applied to improve public confidence in vaccines and
 enhance overall population health.
 ## 2. Data Understanding
 ### Data source
  The data in use is from Datadriven(https://www.drivendata.org/competitions/66/flu-shot-learning/data/) made up of 26707 rows and 36 columns(12 categorical
 columns and 24 are numerical).
 ### Data description
- 'respondent_id'- Unique id
- 'h1n1_concern'- the concern one has about the virus.
- 'h1n1_knowledge'- knowledge they have about the H1N1 virus.
- 'behavioral_antiviral_meds'- If they believe in anti-vaccination.
- 'behavioral_avoidance'-do they avoid roaming in public.
- 'behavioral_face_mask'- do they wear a face mask.
- 'behavioral_wash_hands'- do they regularly wash their hands.
- 'behavioral_large_gatherings'- do they tend to be in gatherings.
- 'behavioral_outside_home'- are they usually outdoors.
- 'behavioral_touch_face'- do they touch their faces often.
- 'doctor_recc_h1n1'
- 'doctor_recc_seasonal',
- 'chronic_med_condition',
- 'child_under_6_months',
- 'health_worker',
- 'health_insurance',
- 'opinion_h1n1_vacc_effective',
- 'opinion_h1n1_risk',
- 'opinion_h1n1_sick_from_vacc',
- 'opinion_seas_vacc_effective',
- 'opinion_seas_risk',
- 'opinion_seas_sick_from_vacc',
- 'age_group'- their age group.
- 'education'- level of education
- 'race'- their race
- 'sex' - their gender
- 'income_poverty'
- 'marital_status'- whether they are married or not.
- 'rent_or_own'- if they rent or own a house.
- 'employment_status'- whether they are employed
- 'hhs_geo_region',
- 'census_msa'- geographical region
- 'household_adults'-number of adults in the house.
- 'household_children'-number of children in the house.
- 'employment_industry'-industr of employment.
- 'employment_occupation'- what they do for a living.
## 3. Data Preparation
1. Handling missing values
2. Feature selection
3. Encoding Categorical Variables
4. Scaling
5. Handling Class Imbalance
## 4. Modeling and Evaluation
-  The model with the best performance was the Random
 forest classifier. A model with the best parameters was
 instantiated.
-  The accuracy of the final model is at 80.7%.
## 5. Conclusion
 Key conclusions include:
 1. Demographic Influences: Individuals with higher levels of education are significantly more
 likely to receive the seasonal flu vaccine. This suggests that public health campaigns could
 benefit from targeted educational efforts to raise awareness about the importance of
 vaccination among populations with lower education levels. Age plays a critical role, with
 people aged 65 years and older being the most likely to get vaccinated. This reflects
 effective targeting of this high-risk group but also underscores the need to improve
 outreach to younger age groups.
 2. Industry and Occupational Factors: Individuals working in the healthcare industry have a
 higher likelihood of getting vaccinated. This indicates that workplace vaccination programs
 and policies in healthcare settings are effective and could be replicated in other industries
 to boost vaccination rates.
 3. Health and Behavioral Insights: The model’s accuracy in predicting vaccination status
 highlights its potential to identify under-vaccinated groups, allowing public health officials
 to tailor interventions and allocate resources more effectively.
## 6. Recommendation
 1. Targeted Outreach: Develop campaigns focused on populations with lower vaccination
 rates, such as individuals with less formal education or those outside the healthcare
 industry.
 2. Workplace Vaccination Programs: Expand successful healthcare industry vaccination
 programs to other workplaces, emphasizing convenience and accessibility.
 3. Youth Engagement: Create specific initiatives aimed at younger age groups who may not
 perceive the flu vaccine as necessary, using digital media and community events to raise
 awareness.
 4. Education Campaigns: Emphasize the safety, efficacy, and benefits of seasonal flu vaccines
 through tailored educational materials, especially in communities with lower educational
 attainment.
## Repository Guide
The data used for the project can be found here: [data](https://github.com/Dominic-Oseko/H1N1-and-Seasonal-Flu-Vaccines-project/tree/main/Data)

The images from EDA can be found here: [images](https://github.com/Dominic-Oseko/H1N1-and-Seasonal-Flu-Vaccines-project/tree/main/Images)

The notebook that contains the project can be found here: [notebook](https://github.com/Dominic-Oseko/H1N1-and-Seasonal-Flu-Vaccines-project/blob/main/Seasonal_flu_Project.ipynb)

The presentation for this project can be found here: [pdf]()

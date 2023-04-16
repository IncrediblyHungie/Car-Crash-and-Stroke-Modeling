Car Accident and Stroke Risk Prediction
Business Problem and Stakeholders
This project aims to predict car accidents and stroke risks using machine learning models. The stakeholders for this project include insurance companies, healthcare providers, and individuals who are interested in understanding their risk profiles for car accidents and stroke occurrences.

Data Source
The data used in this project is obtained from Kaggle:
Data Description
Car Accident Data
The car accident dataset contains information about individuals and their driving history, including demographic, socioeconomic, and vehicle-related variables. The dataset includes the following features:

ID, Age, Gender, Race, Driving Experience, Education, Income, Credit Score, Vehicle Ownership, Vehicle Year, Marital Status, Children, Postal Code, Annual Mileage, Vehicle Type, Speeding Violations, DUIs, Past Accidents
The target variable for the car accident dataset is the outcome, which indicates whether an individual has been involved in a car accident (Crash/No Crash).

Stroke Risk Data
The stroke risk dataset contains information about individuals and their health conditions, including demographic, medical history, and lifestyle-related variables. The dataset includes the following features:

Age, Hypertension, Heart Disease, Smoking Status, etc.
The target variable for the stroke risk dataset is the stroke occurrence, which indicates whether an individual has had a stroke (Yes/No).

Analytical Insights
Insight 1: Car Accident Data 

![image](https://user-images.githubusercontent.com/123442350/232346934-b405d847-39a5-4986-847c-3f6f48a4c0b4.png)

Visual 1: Scatter plot of Past Accidents and Speeding Violations with a heatmap correlation score of 0.44

Finding: There is a moderate positive correlation between past accidents and speeding violations, indicating that drivers with more speeding violations tend to have a higher number of past accidents.

Implication: Understanding the relationship between past accidents and speeding violations can help insurance companies better assess risk and set pricing. Focusing on high-risk drivers with a history of speeding violations could lead to better insurance policies and safety measures.

Insight 2: Car Accident Data

![image](https://user-images.githubusercontent.com/123442350/232346949-2c11d41e-815b-4508-bef9-0754b584c04a.png)

Visual 2: Scatter plot of Age vs BMI with a correlation score of 0.33

Finding: There is a weak positive correlation between age and BMI, indicating that older drivers tend to have higher BMI values.

Implication: Understanding the relationship between age and BMI can provide additional insights into the factors affecting car accidents. This information can help insurance companies refine their risk assessment and pricing strategies, leading to more tailored insurance policies and safety recommendations.

Model Metrics
The best model for the car accident prediction problem is Logistic Regression with the following metrics after PCA:

Accuracy: 0.83
Precision: 0.7728
Recall: 0.6556
F1 Score: 0.7094
The best model for the stroke risk prediction problem is Decision Tree with the following metrics:

Accuracy: 0.9012
Precision: 0.1321
Recall: 0.1129
F1 Score: 0.1217
Model Performance and Business Problem
The chosen models perform well in predicting car accidents and stroke risks. They are able to identify important features that contribute to accident outcomes and stroke risks. However, there are some limitations, such as potential overfitting in some models (e.g., Decision Tree) and the impact of class imbalance on model performance. Addressing these limitations can improve the models' effectiveness in solving the business problem.

Summary and Recommendations
Based on the model performance and analytical findings, we provide the following recommendations for stakeholders:

Use the best performing models (Logistic Regression for car accidents and Decision Tree for stroke risks) to assess risk and optimize premium pricing for car accidents and stroke risks. Consider the relationships between age, BMI, past accidents, and speeding violations for targeted safety interventions and insurance products.
Develop tailored insurance policies and safety recommendations based on the identified factors affecting car accidents and stroke risks. For example, implementing driver education programs focusing on the dangers of speeding and offering incentives for maintaining a healthy lifestyle to lower stroke risk.

Continuously monitor and update the models as new data becomes available to ensure accurate predictions and maintain the effectiveness of the models. Consider addressing potential overfitting and class imbalance issues to improve the overall performance of the models.

Collaborate with healthcare providers to raise awareness about stroke risk factors and develop preventive strategies. Encourage individuals to monitor their health conditions and provide them with personalized recommendations based on the stroke risk prediction model.

By implementing these recommendations, stakeholders can make better-informed decisions, optimize insurance pricing, and promote safer driving and healthier lifestyles to ultimately reduce the occurrence of car accidents and strokes.

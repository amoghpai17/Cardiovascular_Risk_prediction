# Cardiovascular_Risk_prediction


#Problem Statement-

Analysis to explore the various risk factors that can contribute to Coronary Heart Disease (CHD) and to develop machine learning models to predict the likelihood of CHD in individuals.

#Project Summary -

Coronary Heart Disease (CHD) is a prevalent health condition that affects millions of people worldwide. In this analysis, we explore various risk factors that can lead to CHD and develop machine learning models to predict the likelihood of CHD in individuals.

The analysis begins by pre-processing the given dataset, which contains various demographic and medical attributes of patients. The dataset has several null values, which were handled by replacing them with mean values, and a single row with null values was dropped. To handle outliers, we used log transformation. Furthermore, to handle the imbalanced class, we applied Synthetic Minority Over-sampling Technique (SMOTE), which generates synthetic samples of the minority class.

The dataset was then analyzed to explore the relationship between different attributes and the risk of CHD. It was found that male patients had a higher risk of CHD compared to females. Male patients also smoked more than female patients in the dataset, which can contribute to the higher risk. The risk of heart disease was found to be higher between the ages of 48 to 63, indicating that age is an important risk factor. Additionally, people with heart rates between 60 and 100 were found to have a higher chance of CHD.

After pre-processing the dataset, we developed three machine learning models to predict the likelihood of CHD in individuals. The models used were Logistic Regression, KNearestNeighbors, and Random Forest Classifier. We performed hyperparameter tuning on all three models to get the best parameters and the best score. The Random Forest Classifier was found to have the highest accuracy score among all the models, i.e., 86.945%

The results of the analysis provide valuable insights into the factors that can contribute to the risk of CHD. These insights can be used to identify high-risk individuals and develop preventive measures. For example, male patients with a history of smoking who are between the ages of 48 and 63 and have heart rates between 60 and 100 may need to be monitored more closely. Additionally, the machine learning models developed in this analysis can be used to predict the likelihood of CHD in individuals, which can aid in developing personalized treatment plans.

In conclusion, this analysis provides insights into the risk factors that can lead to CHD and highlights the importance of data pre-processing and machine learning in predicting the likelihood of CHD. The results of the analysis can be used to develop preventive measures and personalized treatment plans, ultimately leading to better health outcomes for patients.


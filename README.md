# Diabetics-Health-Indicators
This is a machine learning model project that was built to classify users into Diabetic or non-Diabetic health conditions based on their lifestyle (eating habits, exercise frequency, e.t.c.) and general information about them (like their income, education, BMI, age e.t.c). 
Three different classification models were used in the building process:
 - XGBClassifier
 - RandomForestClassifier
 - LightGBMClassifier
Their RMSE values all ranged between 0.755146 (XGBClassifier) and 0.756398 (LightGBMClassifier)
Other metrics include:
 - Accuracy: 0.843010 (LightGBMClassifier) - 0.843483 (RandomForestClassifier)
 - Precision: 0.711465 (RandomForestClassifier) - 0.778014 (XGBClassifer)
The LightGBMClassifier model was saved as it is the fastest of all the models and occupies the lease disk space, but the XGBClassifier can be saved also as it is widely adopted and has slightly beter metrics than the other two models used in this case

# Human-activity-detection
A human activity detection algorithm that predicts the activity of a human out of the 6 possible options (standing,laying,sitting,walking,walking up or walking down) given the accelerometer and other useful readings from the smartphones
The classifier used are Logistic Regression and RandomForestClassifier to compare thier accuracy.
# Feature Selection
Since the available features were above 500, selectKbest(filter based) and Recursive Feature Elimination(wrapper based) methods were used to reduce them to best 100 .features.The unseen data was used to test the model that used these 100 features 

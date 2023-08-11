# HeartFailurePrediction
 The data set for the heart diseases is available at this link https://www.kaggle.com/datasets/fedesoriano/heart-failureprediction . This dataset contains 11 features that can be used to predict a possible heart disease.
Analysis:
Most analysis I have provide within the jupyter notebook but as I gradually started the CCP a
week ago I got to know about that High blood cholesterol levels are a risk factor for heart
disease. However, dietary cholesterol has little to no effect on blood cholesterol levels in most
people. More importantly, there is no significant link between the cholesterol you eat and your
risk of heart disease. This told me that Cholesterol having high values or value to zero wont
effect the heart disease in an individuals body. I also found a weak positive correlation of about
0.12, which is an improvement from before at least as before it had shown a negative correlation
when I removed the outliers from many groups. Yes, while analyzing I found out that
cholesterol was ZERO which literally makes no sense and is not logical so I didn’t removed
the value but I did capping to save the data from being lost it might be an error.
I was able to find more information about the dataset on UC Irvine's Machine Learning
Repository and some data on Stat log dataset. Both links contained description of the attributes
included I the dataset Both of the links confirm that serum cholesterol was measured in mg/dl,
as you noted. Also, even though none of the links specify whether the BP is systolic or diastolic,
I think it's safe to assume that the BP is systolic, as the values contained under the "RestingBP"
attribute are too high for diastolic BP. (This is something I discovered not necessary for the
project)
Links:
https://archive.ics.uci.edu/ml/datasets/heart+disease
https://archive.ics.uci.edu/ml/datasets/statlog+(heart)
I descriptively used three models:
1. Logistic Regression:
This model gave an accuracy of 82%
2. Decision Tree Classifier:
This model gave an accuracy of 85%
3. KNeighbors Classifier :
This model gave an accuracy of 75%
Then after I applied PCA to reduce the dimensions I found out that the Accuracy in KNN of a
75% was lesser than the accuracy of 80% I got after reducing the dimensions. Conclusively,
the Best model to use for heart predictions according to the models I have used it DecisionTreeClassifier because after reducing the dimensions it has a more accuracy but not
that much to be overfit.
REST EXPLORATORY DATA ANALYSIS CAN BE CHECKED ON THE PDF FILE
WITH THE ASSIGNMENT BELOW!
THANK YOU!

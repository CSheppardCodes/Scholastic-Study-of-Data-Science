# Decision_Trees readme

## DTRegressor
1. **sklearn DecisionTreeRegressor**
   - Use simple DTR on AutoMPG dataset to familiarize with [SKLearn library](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html)
2. **Visualization**
    - Root node has the most information gain. Text(0.5, 0.875, 'cylinders <= 5.5\nsquared_error = 60.763\nsamples = 392\nvalue = 23.446'
   ![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/94b7efd7-323f-4217-b3d1-101b3679e475)

## Decision_Trees_RF
1. **Data exploration**
   - Choose features and evaluate after training using `clf.feature_importances_` from confusion matrix choose `['pregnant', 'insulin', 'bmi', 'age','glucose','bp','pedigree']`
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/97236d82-704e-4bf2-8d7e-406028e89158)
2. **DecisionTreeClassifier**
   - Train DTC on Training data, Evaluate using Testing Data `Accuracy:  0.7705627705627706`
     ![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/768fb8ff-63dc-4f3f-90bc-af4ae9683a4f)
3. **Evaluate Model**
   - Display Confusion matrix, ROC Curve, and Precision-Recall curve
   - Find out how the features we picked performed using `clf.feature_importances_`. **THIS IS VERY IMPORTANT**
   - Glucose has the highest feature importance score of 0.4409249. Conversely, with a depth of 5, Insulin is never used to classify the label.
   -  `array([0.0556187 , 0.        , 0.24307412, 0.12486261, 0.4409249 ,       0.02471295, 0.11080672])`
<p float="left">
  <img src="https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/a805323d-b6c5-4b77-a3f0-4327a9d8c560" width="300" />
  <img src="https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/cdfb8d2c-c8fe-467a-a77c-82d4214616fa" width="300" />
  <img src="https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/713c485f-3aad-46c7-b455-a039e529768a" width="300" />
</p>

4. **Tree Visualization**
   - We see that `'Glucose'` is at the root node. This confirms from our evaluation that Glucose is the most important feature.
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/f9e8cb1d-d8a2-4451-8350-0b10b694cab2)

5. **BaggingClassifier, RandomForestClassifier, AdaBoostClassifier**
   - Compare the performance of BC, RTC, and Ada to DTC. Random Forest is the highest with an accuracy of 0.79%
<p float="left">
  <img src="https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/e91f305d-dbb1-4c5e-9e6e-42a0804dec56" width="300" />
  <img src="https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/5cfe224f-2b8e-4e8a-8237-ebf0dcfb3fdf" width="300" />
  <img src="https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/0ca4094f-ea3b-42c1-a0b7-b638cee7651a" width="300" />
</p>




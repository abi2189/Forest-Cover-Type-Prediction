# Forest-Cover-Type-Prediction
A Machine Learning Based Project to predict the Cover Type of a Tree based on their respective geographic areas.

Problem Statement
- The data about the tree observations are from 4 different areas in Roosevalut National Forest in Colorado
- Observation are cartographic variable (relating to maps) from 30x30 meter sectionos of forest
- We are given 10 continuous variables, 44 one hot encoded columns with which we are given to predict the `Cover_Type` (Target Variable) of a Tree.

Process Followed
1. Cleaning and Formating the dataset
2. Performing Exporatory Data Analysis and infering from various plots
3. Feature Engineering
4. Comparing and Testing Various Models on the dataset to predict the `Cover_Type`

Conclusion
Upon testing several models and infering from their results, by cross-validation and also fine-tuning the models using grid-search. We are able to conclude that, for our dataset the best models ranked according to F1 Score are
1. Extra Trees Classifier
2. Random Forest Classifier
3. LGBM (Lighht Gradient Boosting Machine)
4. XGBoost
5. Gradient Boosting
6. KNN (K-Nearest Neighbour Classifer)
7. Decision Tree
8. SVM (Support Vector Machines)
9. Naive Bayes
10. Logestic Regression

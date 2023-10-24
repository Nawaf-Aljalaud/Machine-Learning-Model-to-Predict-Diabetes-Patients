# Machine-Learning-Model-to-Predict-Diabetes-Patients

# Introduction:
A well-known and influential machine learning algorithm used for classification and regression tasks is decision trees. They have widespread applications in healthcare, finance, and marketing. The unique feature of decision trees is their ability to learn a hierarchical set of conditions based on input features, enabling them to make predictions or decisions. The trees consist of nodes and branches representing decision rules and potential outcomes. Decision tree algorithms are precious for understanding and visualizing decision-making because they provide clear and intuitive models. They are highly adaptable to a wide range of datasets, as they effectively handle both categorical and numerical data. By utilizing information from different features, decision trees can make precise predictions and offer valuable insights into the relationships between variables in the dataset.

# Dataset Description:
The Diabetes prediction dataset consists of medical and demographic data from patients, along with their diabetes status (positive or negative). Like many others, this dataset includes some attributes, including age, gender, BMI, hypertension, heart disease, smoking history, HbA1c level, and blood glucose level. We were asked to build a machine-learning model to predict the likelihood of diabetes in patients according to their medical history and demographic details.

# Preprocessing Steps:
1. Load the dataset into Panda’s data frame.
2. Replace missing values with the mean or mode for the respective columns.
3. Encode categorical variables using one-hot encoding.
4. Split the dataset into training and testing subsets using a 70/30 split.

# Decision Tree Learning Process:
1. Train a decision tree classifier using the training data.
2. Set the maximum depth of the decision tree to 8 to control the complexity.
3. Fit the decision tree model to the training data.

# Performance Evaluation: 
1. Predict the diabetes labels for the test set using the trained model.
2. Calculate performance metrics, including accuracy, precision, recall, and F1-score.
3. Print the performance metrics.

Results:

The analysis of the diabetes prediction dataset using a decision tree classifier yielded the following results:

• Accuracy: 0.9716
• Precision: 0.9873
• Recall: 0.6741
• F1-score: 0.8012

# Decision Tree Visualization:

The tree shows the splitting criteria at each node based on the selected features.
![image](https://github.com/Nawaf-Aljalaud/Machine-Learning-Model-to-Predict-Diabetes-Patients/assets/148896098/be2dd60b-cc1f-43f5-b076-93a202cbd577)

# Insights and Observations:

1. The decision tree model achieved a high accuracy of 97.16%, indicating its effectiveness in predicting diabetes based on the given features.
2. The precision score of 98.73% suggests that the model performs well in correctly identifying positive diabetes cases.
3. The recall score of 67.41% indicates that the model captures a moderate proportion of positive diabetes cases.
4. The F1-score of 80.12% represents a balance between precision and recall, indicating good performance.
5. The information gain analysis revealed that features like HbA1c and blood glucose levels have the highest importance in the decision tree, followed by age and BMI. Other features, such as gender and smoking history, had negligible information
gain and did not contribute much to the prediction.


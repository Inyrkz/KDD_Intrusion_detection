# KDD_Intrusion_detection
Training machine learning models for intrusion detection on the KDD dataset

## APPROACH 1
Click [here](https://docs.google.com/document/d/15OU9CtQrk2N-KEUqwGFrIGzctesUVN5OEVI2x6q3MD8/edit?usp=sharing) for the full documentation.

* I completed a machine learning project focused on intrusion detection. Using the NSL-KDD dataset from Kaggle, which consists of training and test sets with a total of 125,973 and 22,544 entries respectively, I aimed to predict the target variable, which contains 23 different classes.

* During the exploratory data analysis, I visualized the distribution of classes in the target variable, identified the need for grouping attacks into categories due to insufficient data, and created four attack categories: DoS, Probe, U2R, and R2L. The new target variable, "new_label," consisted of five classes: Normal, DoS, Probe, U2R, and R2L. 

* I also explored the relationships between variables, using violin plots and boxplots. In the data pre-processing phase, I performed one-hot and label encoding techniques, and removed unnecessary variables.

* For model training, I employed five machine learning algorithms: K Nearest Neighbors, AdaBoost + SVM, AdaBoost + Decision Tree, AdaBoost + Logistic Regression, and a Voting Classifier. I used the test set to evaluate the performance of these models, considering metrics such as accuracy, precision, recall, and F1 score.

* The results showed that KNN and the Voting Classifier achieved the highest accuracy scores on both the training and test sets, while AdaBoost + SVM demonstrated strong recall and precision values. These findings highlight the effectiveness of the machine learning models in detecting and classifying intrusions.

## APPROACH 2
Click [here](https://docs.google.com/document/d/1yh8Umfd7Ae4bK6XpgIuCTYTdDmoAilDQDdIvEA_qwP4/edit?usp=sharing) for the full documentation.

* Feature selection was performed to identify the top 20 features for training, reducing complexity and addressing the curse of dimensionality. Recursive Feature Elimination (RFE) and the random forest algorithm will be employed for this purpose.

* Machine learning models such as decision trees, random forests, K Nearest Neighbors, and XGBoost were explored for detecting various cybersecurity threats. The project was developed on a Windows computer with an Intel Core i5 processor and 8GB of RAM.

* Two models were trained. The first one was trained with 43 feature, and the second model was trained with the top 20 features. The second model trained with 20 features performed slightly better than the first model.

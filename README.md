# Predictive-Maintenance

            Predictive maintenance documentation

Problem Statement:
           	In the digital age, optimizing maintenance schedules is crucial for enhancing production efficiency in industries. Predictive maintenance leverages data to create smarter, more digitized facilities, reducing downtime and increasing productivity. The challenge is to predict machine failures using a dataset of 10,000 observations that include variables such as product type, air temperature, process temperature, rotational speed, torque, tool wear, and various failure modes (machine failure, TWF, HDF, PWF, OSF, RNF). Accurate predictions will enable proactive maintenance strategies, minimizing disruptions and improving operational performance.
Steps to follow in the project:
1.   EDA
a. 	Describing the dataset
b.	Cleaning the data
c. 	Checking invalid records
d.	Missing value detection and imputation
e.	Duplicated records
f.  	Outliers
2.   Data Visualization
a. 	Pie chart
B. histogram
C. scatterplot 
D. heatmap
E.box plot
F- corr. analysis
3.   Feature engineering
a. 	Making changes according to eda
 
4.   Model building
 All algorithms to be tested:
1. Logistic Regression
2. Decision Trees
3. Random Forest
4. Gradient Boosting Machines (GBM)
5. Support Vector Machines (SVM).
 
5.   Hyperparameter tuning
6.   Model evaluation
1. Accuracy:
   - The ratio of correctly predicted instances to the total instances.
2. Precision:
   - The ratio of true positive predictions to the total positive predictions (true positives + false positives).
3. Recall (Sensitivity):
   - The ratio of true positive predictions to the actual positives (true positives + false negatives).
4. F1 Score:
   - The harmonic mean of precision and recall, useful when class distribution is imbalanced.
5. ROC-AUC Score:
   - The area under the Receiver Operating Characteristic curve, measuring the ability to distinguish between classes. 
7.   Model Deployment  
-using flask
-Monitoring and Maintenance: after implementing and monitoring to track model performance over time and retrain the model periodically with new data to maintain accuracy.



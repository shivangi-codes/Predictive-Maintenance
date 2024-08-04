# Predictive-Maintenance

            Predictive maintenance documentation

Problem Statement:
           	In the digital age, optimizing maintenance schedules is crucial for enhancing industry production efficiency. Predictive maintenance leverages data to create smarter, more digitized facilities, reducing downtime and increasing productivity. The challenge is to predict machine failures using a dataset of 10,000 observations that include variables such as product type, air temperature, process temperature, rotational speed, torque, tool wear, and various failure modes (machine failure, TWF, HDF, PWF, OSF, RNF). Accurate predictions will enable proactive maintenance strategies, minimizing disruptions and improving operational performance.
Steps to follow in the project:
1.   EDA

a. 	Describing the dataset
b.	Cleaning the data
c. 	Checking invalid records
d.	Missing value detection and imputation
e.	Duplicated records
f.  	Outliers


2.   Data Visualization
a. Pie chart
B. histogram
C. scatterplot 
D. heatmap
E.box plot
F- corr. analysis
3.   Feature engineering
a. 	Making changes according to eda


 
4.   Model building
 All algorithms to be tested:
a. Logistic Regression
b. Decision Trees
c. Random Forest
d. Gradient Boosting Machines (GBM)
e. Support Vector Machines (SVM).


 
5.   Hyperparameter tuning

   
6.   Model evaluation
a. Accuracy:
   - The ratio of correctly predicted instances to the total instances.
b. Precision:
   - The ratio of true positive predictions to the total positive predictions (true positives + false positives).
c. Recall (Sensitivity):
   - The ratio of true positive predictions to the actual positives (true positives + false negatives).
d. F1 Score:
   - The harmonic mean of precision and recall, useful when class distribution is imbalanced.
e. ROC-AUC Score:
   - The area under the Receiver Operating Characteristic curve measures the ability to distinguish between classes.
  
     
7.   Model Deployment  
-using streamlit
-Monitoring and Maintenance: after implementing and monitoring, track model performance over time and periodically retrain the model with new data to maintain accuracy.



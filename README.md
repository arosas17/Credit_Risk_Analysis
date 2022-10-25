# Credit_Risk_Analysis

## Overview 
Using the imbalanced-learn and scikit-learn libraries, multiple supervised machine learning models to predict credit risk were created. To create this machine learning model, many different methods of resampling were tested. For oversampling, the RandomOverSampler and SMOTE algorithms were used and the ClusterCentroids algorithm for undersampling. A combined approach over oversampling and undersampling was done with the SMOTEENN algorithm. Lastly, both BalancedRandomForestClassifier and EasyEnsembleClassifier weretested to see a reduced bias in the results. A total of six methods were used to assess credit risk and judged based on balanced accuracy score, the precision, and recall scores.

## Results

The data below demonstrates how well the machine learning models predict information; specifically, the balanced accuracy score, the precision, and recall scores. The higher score tends to be better but still need to be wary of overfitting the data.

### RandomOverSampler Scores
![ros_bas.png](/Images/ros_bas.png)<br><br>
![ros_report.png](/Images/ros_report.png)<br><br>


### SMOTE Scores
![smote_bas.png](/Images/smote_bas.png)<br><br>
![smote_report.png](/Images/smote_report.png)<br><br>

### ClusterCentroids Scores
![cc_bas.png](/Images/cc_bas.png)<br><br>
![cc_report.png](/Images/cc_report.png)<br><br>

### SMOTEENN Scores
![smoteenn_bas.png](/Images/smoteenn_bas.png)<br><br>
![smoteenn_report.png](/Images/smoteenn_report.png)<br><br>

### BalancedRandomForestClassifier Scores
![brf_bas.png](/Images/brf_bas.png)<br><br>
![brf_report.png](/Images/brf_report.png)<br><br>

### EasyEnsembleClassifier Scores
![ee_bas.png](/Images/ee_bas.png)<br><br>
![ee_report.png](/Images/ee_report.png)<br><br>

## Summary

# Credit_Risk_Analysis

## Overview 
Using the imbalanced-learn and scikit-learn libraries, multiple supervised machine learning models to predict credit risk were created. To create this machine learning model, many different methods of resampling were tested. For oversampling, the RandomOverSampler and SMOTE algorithms were used and the ClusterCentroids algorithm for undersampling. A combined approach over oversampling and undersampling was done with the SMOTEENN algorithm. Lastly, both BalancedRandomForestClassifier and EasyEnsembleClassifier weretested to see a reduced bias in the results. A total of six methods were used to assess credit risk and judged based on balanced accuracy score, the precision, and recall scores.

## Results

The data below demonstrates how well the machine learning models predict information; specifically, the balanced accuracy score, the precision, and recall scores. The higher score tends to be better but still need to be wary of overfitting the data.

### RandomOverSampler Scores
![ros_bas.png](/Images/ros_bas.png)<br><br>
![ros_report.png](/Images/ros_report.png)<br><br>
The RandomOverSampler resulted in: 
* a balanced accuracy score of 65.7%
* a high-risk precision of 1%
* a high-risk recall of 71%

### SMOTE Scores
![smote_bas.png](/Images/smote_bas.png)<br><br>
![smote_report.png](/Images/smote_report.png)<br><br>
The SMOTE resulted in: 
* a balanced accuracy score of 66.2%
* a high-risk precision of 1%
* a high-risk recall of 63%

### ClusterCentroids Scores
![cc_bas.png](/Images/cc_bas.png)<br><br>
![cc_report.png](/Images/cc_report.png)<br><br>
The ClusterCentroids resulted in: 
* a balanced accuracy score of 54.4%
* a high-risk precision of 1%
* a high-risk recall of 69%


### SMOTEENN Scores
![smoteenn_bas.png](/Images/smoteenn_bas.png)<br><br>
![smoteenn_report.png](/Images/smoteenn_report.png)<br><br>
The SMOTEENN resulted in: 
* a balanced accuracy score of 64.5%
* a high-risk precision of 1%
* a high-risk recall of 72%


### BalancedRandomForestClassifier Scores
![brf_bas.png](/Images/brf_bas.png)<br><br>
![brf_report.png](/Images/brf_report.png)<br><br>
The BalancedRandomForestClassifier resulted in: 
* a balanced accuracy score of 78.9%
* a high-risk precision of 3%
* a high-risk recall of 70%


### EasyEnsembleClassifier Scores
![ee_bas.png](/Images/ee_bas.png)<br><br>
![ee_report.png](/Images/ee_report.png)<br><br>
The EasyEnsembleClassifier resulted in: 
* a balanced accuracy score of 93.2%
* a high-risk precision of 9%
* a high-risk recall of 92%

When comparing the different methods above, certain trends occur. The BalancedRandomForestClassifier and EasyEnsembleClassifier also had higher balanced accuracy scores of 78.9% and 93.2%; the other methods had balanced accuracy score from 54-63%. In addition to the accuracy, it is noticeable that all algorithms have a 1% precision for high-risk loans with the exception of the BalancedRandomForestClassifier and EasyEnsembleClassifier scores which managed precisions scores of 3% and 9%. For the high-risk recall scores, most of the methods received a recall score around 70%. The SMOTE method scored a little lower than others at around 63%, but the highest one is with the EasyEnsembleClassifier with a larger percentage of 92%.

## Summary

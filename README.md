# credit_risk

Module 20
Jaspreet Kalsi

Analysis overview
The purpose of the credit risk analysis to illustrate the effectiveness of a machine learning model designed to carry out a specific task. The analysis itself examines the precision, accuracy and recall scores to demonstrate an understanding of the model’s predictive capabilities. It is used to make informed recommendations regarding the model’s suitability for deployment within the company’s operations. 

Results
1.	Model 1
Accuracy: 0.972
Precision: for healthy (0) loans the precision is 1.00, for high risk (1) loans the precision is 0.87
Recall: for healthy (0) loans the recall score is 1.00, for high risk (1) loans the recall score is 0.95

2.	Model 2
Accuracy: 0.996
Precision: for healthy (0) loans the precision is 1.00, for high risk (1) loans the precision is 0.87
Recall: for healthy (0) loans the recall score is 1.00, for high risk (1) loans the recall score is 1.00

Summary

In comparing the performance of Model 1 and Model 2 in the credit risk analysis, it is evident that Model 2 is more likely to predict accurate results, as it achieved a higher overall score. However, a closer examination of the confusion matrices reveals that Model 2 produced more false positives (91) compared to Model 1 (86).

In the context of credit risk analysis, where minimizing the risk of financial losses is crucial, the company's preference is to use a model with fewer false positives. Despite this, the importance of correctly identifying high-risk loans cannot be overstated. Model 2, with its higher recall value, excels in this aspect, making it a better choice for deployment. It not only achieves higher accuracy and precision but also demonstrates a superior ability to identify high-risk loans accurately, addressing the company's primary concern.


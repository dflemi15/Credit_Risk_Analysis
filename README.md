## Credit_Risk_Analysis

# Overview of the analysis

The purpose of this analysis is to analyze the credit card risk for the LendingClub, a peer-to-peer lending service company. In order to do this analysis, a variety of oversampling and statistical modeling techniques were employed. The results were then measured for accuracy to identify the module that performed the best based when it comes to identifying high risk credit card events.

# Results

The following results are a culmination of myriad sample techniques used to illustrate the attempt to understand credit card behavior. The oversampling and under sampling models appear to provide similar accuracy scores (approximately 63-64%). The precision and recall scores were also similar for each model as they appeared to struggle identifying high risk credit events with acceptable precision. 

•	Naïve Random Oversampling

![image](https://user-images.githubusercontent.com/107585908/195464474-4106868f-6900-4fe7-b3d8-d01f12419194.png)

![image](https://user-images.githubusercontent.com/107585908/195464481-2d8eac46-8aa5-48ca-a7ec-2b29789be8b1.png)

•	Smote Oversampling

![image](https://user-images.githubusercontent.com/107585908/195464521-e49f9856-98e1-4ebf-9f94-f4a4c451c5e0.png)

![image](https://user-images.githubusercontent.com/107585908/195464532-065e1f01-097d-452b-a760-be9969d5dca9.png)

•	Under sampling

![image](https://user-images.githubusercontent.com/107585908/195464564-9c8940ae-6969-46cc-97bc-24f62839c90d.png)

![image](https://user-images.githubusercontent.com/107585908/195464571-42529769-a03b-4efa-9e42-a7def6f4f3d0.png)

The accuracy of the combination model appears perform worse than either of the under or oversampling models landing at approximately 51% accuracy.  

•	Combination

![image](https://user-images.githubusercontent.com/107585908/195464621-81da885c-b2e9-4559-9f68-0465d9233d73.png)

![image](https://user-images.githubusercontent.com/107585908/195464639-89a153f9-24b6-4435-ab66-858f3adf584c.png)

The models for the Random Forest AdaBoost Classifier perform significantly better than the previous models with both possessing accuracy scores of over 80% and 90% respectively.

•	Balanced Random Forest

![image](https://user-images.githubusercontent.com/107585908/195464674-e6e8d757-6272-4c08-b8ee-f5ff356f7e6d.png)

![image](https://user-images.githubusercontent.com/107585908/195464681-dd2dbfaa-7e70-4686-97a5-c3ef7ae788bb.png)

•	Easy Ensemble AdaBoost Classifier

![image](https://user-images.githubusercontent.com/107585908/195464705-cc423521-40d6-4f48-8efe-0f0441b006dc.png)

![image](https://user-images.githubusercontent.com/107585908/195464713-c9f7718b-949d-4aa7-be32-bae52970b71a.png)

# Summary

According to the results, the Easy Ensemble AdaBoost Classifier model preformed the best when predicting high credit card risk. This is based solely on the scores obtained in the outputs for this model. More analysis would be required in order to confidently choose this model. This could include the introduction of other independent variables to see how the model responds. 

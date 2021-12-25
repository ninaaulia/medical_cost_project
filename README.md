# Mini Project 
### Medical Cost Prediction

![image](https://user-images.githubusercontent.com/71708747/147376275-d8301925-42aa-4257-86d9-18f6b350156f.png)



## Dataset
the Dataset is available in [Kaggle](https://www.kaggle.com/)

[Insurance Dataset](https://www.kaggle.com/mirichoi0218/insurance) has 1338 rows and 7 columns



| Columns       | Description  |
| ------------- |:-------------:|
| Age           | age of primary beneficiary |
| Sex           | insurance contractor gender, female, male |
| BMI           | Body mass index |
| Children      | Number of children covered by health insurance / Number of dependents |
| Smoker        | Yes/No |
| Region        | the beneficiary's residential area in the US, northeast, southeast, southwest, northwest. |
| Charges       |  Individual medical costs billed by health insurance. |






### Data Preprocessing

1. Removing outliers using Z score
2. Log transformation for data target
3. Label encoding





### Models Comparison



| Method                | Score    | RMSE     |
| ----------------------|:--------:|:--------:|
| Linear regression     | 77%      | 0.193491 |
| Polynomial regression | 76%      | 0.200554 |
| KNN                   | 80%      | 0.178879 |
| Decision tree         | 81%      | 0.176421 |





### Deploying


![image](https://user-images.githubusercontent.com/71708747/147376365-f59dce51-6c6f-47d0-b564-0128128399d9.png)



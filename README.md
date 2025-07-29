# Basics-of-Classification
In this project we use classifcation models to predict whether clients will get their loans approved or not

We used Loan dataset from Kaggle.

Models used in this project:

1.) Logistic Regression
2.) K Neighbors Classifier
3.) K Neighbors Classifier (Manual Tuning)
4.) K Neighbors Classifier (Hyperparameter Tuning)
5.) Random Forest Classifier
6.) ADABoost
7.) XGBoost 

We compare the performances of these models using accuracy score and other metrics:


| Model                                             | Accuracy Score  |
|--------------------------------------------------|-----------------|
| Logistic Regression                              | 0.8617886179    |
| K Neighbors Classifier                           | 0.837398374     |
| K Neighbors Classifier (Manual Tuning)           | 0.8536585366    |
| K Neighbors Classifier (Hyperparameter Tuning)   | 0.6016260163    |
| Random Forest Classifier                         | 0.8292682927    |
| ADABoost                                         | 0.8536585366    |
| XGBoost                                          | 0.8211382114    |

During Hyperparameter tuning with KNN our accuracy scores dropped as Hyperparameter tuning doesnt mean that
the model will necessary perform better, it just optimizises it for the training data + CV data and that
might hurt the generelization if our model overfits.

Logistic Regression performed the best as the dataset might be roughly linear and LR generalizes better on smaller dataset.





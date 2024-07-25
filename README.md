# LoanDefaulterPrediction
Made a Loan Defaulters' Risk Flag System which predicts if a person would default a loan, depending on their financial parameters.

## Image 1: 
Clustered BarChart: People with lower income are marked at risk of defaulting, irrespective of their age.
Treemap: Highest no. of applicants belong to UP and Maharashtra followed by andhra pradesh and west bengal
Doughnut chart: Highest no. Of applicants have rented house.

Image 2:
TreeMap: Uttar pradesh has the highest no. Of possible defaulters followed by west bengal and andhra pradesh
         UP has no. of defaulters 3343

Image 3: Histogram, we check the data distribution
#Only a small part of the target variable consists of people who default on loans.

Image 4: HeatMap
correlation matrix
#we notice there is a fairly strong correlation between experience and current job years, which is self justified.

Image 5: Bargraph
#So, the majority of the people are single.

image 6: #majority of the people have a rented accomodation

image 7: #we see that higher no. of possible defaulters have no car.

image 8: ##we see that higher no. of possible defaulters are single

image 9: 
#we see that higher no. of possible defaulters neither have a rented or own house whearas most of the people who are unlikely to default their loan have their own house.

img 9.25, 9.5: Prediction

# Evaluation:
image 10:

#The precision of 54.31% indicates that when the model predicts a sample as a "yes" (default, positive class), it is correct approximately 54.31% of the time. Higher precision means the model has a low rate of false positives.
#The recall of 53.80% means that the model correctly identifies approximately 53.80% of the actual positive samples (defaults)
#The F1 score of 54.05% is the harmonic mean of precision and recall and provides a balanced measure between them.
#The accuracy of 88.75% indicates the overall correctness of the model's predictions. 

image 11:
#Based on the evaluation metrics , we can plot the  confusion matrix
#The Confusion Matrix shows the performance of the Random Forest model for binary classification. It correctly predicted 41,395 positive instances (True Positives) and 3,335 negative instances (True Negatives). However, it made 2,806 incorrect positive predictions (False Positives) and 2,864 incorrect negative predictions (False Negatives).

image 12:
#"ROC Curve"
#"High AUC Indicates Good Model Discrimination on Imbalanced Data"

image 13:
#relatively higher scores of current house yrs, state and income signifies the high influence of these features in the prediction.

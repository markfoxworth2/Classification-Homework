# Classification

The purpose of this analysis is to determine classification model performance based on each models performance in its balanced accruracy, recall, and geometric mean scores.  

## *Resampling Models:*

## Naive Random Oversampling
![Naive Oversampling](Images/NAIVE_Oversampling.PNG)

## SMOT Oversampling
![SMOT](Images/SMOT.PNG)

## Undersampling (Cluster Centroids)
![Cluster](Images/Undersampling_Cluster.PNG)


## SMOTEEN Combination Sampling
![SMOTEEN](Images/Combination_SMOTEEN.PNG)

## Findings:
 - Which model had the best balanced accuracy score?
    -  Naive Random Oversampling presents a score of .6634 which is higher than the other model outputs.  
 - Which model had the best recall score?
    - SMOT model had the best recall score.  
 - Which model had the best geometric mean score?
    - Best geometric mean was with the Naive Random Oversampling model.  

## *Ensemble Models:*

## Balanced Random Forest Classifier
![Balanced](Images/Balanced_Random_Forest.PNG)

## AdaBoost

![ada](Images/Adaboost.PNG)

## Findings:
 - Which model had the best balanced accuracy score?
    - Best accuracy score was with AdaBoost with .93
 - Which model had the best recall score?
    - Adaboost also had best recall scores.
 - Which model had the best geometric mean score?
    - Adaboost was also best for the geometric mean score. 

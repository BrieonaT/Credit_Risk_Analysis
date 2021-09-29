## Overview
LendingClub is  a peer-to-peer lending services company. This analysis takes a look into their creditcard dataset in order to determine percent of credit risk for the company. To do this, several techniques have been used, and the results of this analysis determine which method is most effective for the company’s current dataset.


## Results
The following are the results of each type of analysis procedure.

- Naive Random Oversampling:

![Naive Random Oversampling](https://github.com/BrieonaT/Credit_Risk_Analysis/blob/main/Resources/Images/Naive_Random_Oversampling.png)

- SMOTE Oversampling

![SMOTE Oversampling](https://github.com/BrieonaT/Credit_Risk_Analysis/blob/main/Resources/Images/SMOTE_Oversampling.png)

- Undersampling

![Undersampling](https://github.com/BrieonaT/Credit_Risk_Analysis/blob/main/Resources/Images/Undersampling.png)

- Combination Over and Under Sampling

![Combination Over and Under Sampling](https://github.com/BrieonaT/Credit_Risk_Analysis/blob/main/Resources/Images/Combination_Sampling.png)

- Balanced Random Forest Classifier

![Balanced Random Forest Classifier](https://github.com/BrieonaT/Credit_Risk_Analysis/blob/main/Resources/Images/Balanced_Random_Forest_Classifier.png)

- Easy Ensemble AdaBoost Classifier

![Easy Ensemble AdaBoost Classifier](https://github.com/BrieonaT/Credit_Risk_Analysis/blob/main/Resources/Images/Easy_Ensemble_AdaBoost_Classifier.png)

## Summary
In conclusion, the results show which are the most accurate and least accurate models to use. The most accurate model is the Easy Ensemble AdaBoost Classifier, at a 0.93 or, 93% accuracy, whereas the rest of the techiques fall into the 60s-range. With this in mind, it's safe to say out of all the models, the Easy Ensemble AdaBoost Classifier is the most accurate and the suggested one to use for this example. 

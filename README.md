# Credit_Risk_Analysis (Supervised_Machine_Learning)
## Overview
This projetc is aimed to predict one's credist risk result in either low or high risk status. Methodology-wise, the data is being examined through imbalanced-learn and scikit-learn. By creating training and testing sets, modelling data with various of samplings and draw conclusions from them. On the other hand, compare data via two decision classifiers (balanced-forest-classifier and easy-ensemble-classifier) to minimize bias.

## Results
- ##### RandomOverSampling
  ![](https://github.com/WilliamBHW/Credit_Risk_Analysis/blob/main/Supports/RandomOverSampling.png)
- ##### SMOTE
  ![](https://github.com/WilliamBHW/Credit_Risk_Analysis/blob/main/Supports/SMOTE.png)
- ##### ClusterCentroidUnderSampling
  ![](https://github.com/WilliamBHW/Credit_Risk_Analysis/blob/main/Supports/ClusterCentroidUnderSampling.png)
- ##### SMOTEEN
  ![](https://github.com/WilliamBHW/Credit_Risk_Analysis/blob/main/Supports/SMOTEEN.png)
- ##### BalancedRandomForestClassifier
  ![](https://github.com/WilliamBHW/Credit_Risk_Analysis/blob/main/Supports/BalancedRandomForest.png)
- ##### EasyEnsembleClassifier
  ![](https://github.com/WilliamBHW/Credit_Risk_Analysis/blob/main/Supports/EasyEnsembleClassifier.png)
<br>

## Summary
By comparing all models, random forest classifier and adapted boost (easy ensemble) classifier have higher accuracy since resamplings have uncertainty on creating the data model. In this case, forest decision trees are perfoming overwhelmingly better with high sensitivity (recall) with both criterias. Since oversampling involves random sample with replacement, it is clear that data may be drawn multiple times to increase sample size resulting low accuracy. Similarly, undersampling recuces trained data that may not be large enough for decision making. Thus, multiple decision trees are outperforming with low bia, high accuracy, high precision and high sensitivity. EasyEnsembleClassifier having the highest balance between all criterias indicating it is the best analysis method for this model.

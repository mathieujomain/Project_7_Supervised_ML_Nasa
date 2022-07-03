<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Project 7 - Machine/Supervised learning - 

*Mathieu*
*[DA, Paris & 07/03]*

## Description 

In Module 3 we started with a new topic: machine learning. The first week focused on supervised learning models and using these to predict and classify given data correctly. The challenge in this weeks project was to use data about different comets, created by NASA, including ultiple measurement details such as velocity, mean radius, perimeter etc. and create a supervised learning Model that can determine if a comet should be seen as a danger to earth (going to breach the atmosphere and hit earths surface) or not.

We begin by cleaning and preping the data to be ready for model firring and application. We dealt with missing values, performed exploratory data analysis, checked for outliers, and encoded if necessary. Next step on te way was feature selection. Using multiple tests such as RFE, SFM etc. (for details see slides) we selected different features being categorized as most important to have the opportunity of testing multiple feature combinations and seeing which will give us the best results from the models. The last step before stating with testing different models we went through the hyper parameter tuning process to see which parameters for the different models will give us the best results.

With all of the necessary information and our cleaned, prepared data we thenn applied following eight supervised learning models.
- RidgeClassifier (http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.RidgeClassifier.html)
- SVC (https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html)
- CategoricalNB (https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.CategoricalNB.html)
- ExtraTreesClassifier (https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.ExtraTreesClassifier.html)
- Gradient Boosting (https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html)
- Linear Discriminant Analysis (https://scikit-learn.org/stable/modules/generated/sklearn.discriminant_analysis.LinearDiscriminantAnalysis.html)
- LinearSVC (https://scikit-learn.org/stable/modules/generated/sklearn.svm.LinearSVC.html)
- KNeighborsClassifier (https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)

To recieve the best possible outcome of our model (also regarding the precious business in this case --> importanc f finding all dangerous comets in stead of pure accuracy) we tried out different sampling methods to allow the models to perform different classification processes.

## Plan
- Create Trello workflow visualization 
- Create repo on GitHub
- Data cleaning and preparation
- EDA and encoding of data
- Feature selection
- Hyper parameter tuning
- Application of models
- Experimenting with different sampling methods to recieve best possible result
- Prepare presentation

## Deliverables

- Original data in csv format
- Cleaning code
- Clean data in csv format
- Slides for presentation

## Links to deliverables and additional links

[Repository](https://github.com/mathieujomain/Project_7_Supervised_ML)  
[Trello] ()






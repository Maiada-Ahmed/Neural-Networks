# Neural-Networks
# Prediction of Obesity Levels Based on Eating Habits and Physical Condition

## Introduction:
In 2020, there was a rapid increase (39%) of overweight adults with a BMI over 25. Moving forward, the obesity problem is expected to get worse and is estimated to reach 50% if it continues to increase by the same rate in 2030. There has been an ever-increasing interest to study obesity due to the massive impact on health-related consequences and clinical complications.

Moreover, obesity reduces life expectancy and negatively impact the quality of life. Initially, obesity was more dominant in developed countries. However, now it is observed in developing countries as well, alongside other complications such as hunger and poverty. There is a limitation of this dataset to develop neural networks. However, many researchers and coders used it in the area of machine learning.

Below are two recent examples in one of the previous studies that tried to predict obesity levels by experimenting on four models (Decision Trees, Random Forest, SVM and K Nearest Neighbours). Random Forest was identified as an initial model with an accuracy of around 79% and concluded after hyperparameter tuning that the accuracy reached 92%. Another model that also looked into predicting obesity was using multiple models by identifying the most suitable model with parameters using GridSearchCV between the following models (SVM, Random_Forest, Logistic_Regression, etc. Decision_Tree, KNN). Initially, SVM achieved 96% accuracy and then the model was improved by obtaining an optimized train-test split using Variance Bias Tradeoff. Accordingly, the model was able to predict obesity levels with an accuracy of 98%.

## Dataset Description:
Data was collected through a web page using a survey applied to undergraduate students of universities in Colombia, México and Perú, which evaluated their eating habits and some aspects that helped identify their physical condition. Dataset is available in UCI Machine Learning Repository and accessible from the following link (here)

The dataset contains data for estimating obesity levels based on their eating habits and physical condition. The data include 17 variables (16 inputs and 1 target variable) with 2,111 records. Based on the dataset structure, a supervised learning technique will predict the output. The chosen model is a single label, multiclass classification.

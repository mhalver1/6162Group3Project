# 6162 Group 3 Project
# Prediction of Quality of Soil
We want to work with soil, which has many parameters that can affect what model can be used. We asked ourselves "what models can be used when using these different parameters?" These parameters include things like texture and porosity. The problem question we would like to solve is which model is best used analyze and describe soil quality datasets. These datasets will consist of different soil parameters. We will perform data analysis and use learning techniques to accomplish analyzing which models are best used to analyze soil. The problem question we would like to solve is how accurate is the data we analyze and if the data is trustworthy.

The new file added shows many visualizations of each step, including the data before and after compression and preprocessing and the training and testing set. For example, there are two box plots, which show before and after compression and preprocessing. These visualizations include decision trees, scatter plots, and box plots. We wanted focus on crop rotation by helping farmers better analyze soil. The classifiers have also been added and visualized. For example, classification reports and confusion matrices are used to visualize the classifiers. This uses matplotlib, pandas, numpy, and seaborn. This helped us learn about the different models and classifiers we can use to analyze compatibility. From our data, we concluded that a random forest classifier is the best solution for soil as many decision trees can come from this, giving farmers different visualizations. Future work can include more examples and visualizations

The data is entirely unique because of its features which are very environmental and needs to be recorded through sensors or satellites. There were certain fields of data which were empty and needed to be cleaned and also the range of the feature values  were to be adjusted to make them more generalized and understandable. 

We haven’t created any new variables or features but we correlated and got the coefficients to find out the dependent and independent variables.

We have used a split database to train and test the classifiers and also evaluate by calculating the precision, f1-score and accuracy for each classifier. We found out using Random Forest Classification is the best approach.

We took a lot of time in cleaning and preprocessing the data but we transformed and visualized the data using boxplot to get a clear picture of the situation.

We have the sample dataset that we were dependent on and we would like to know the results for a larger version of the dataset.

Try to use the jupyter notebook with python 3 on the windows platform to analyse the code we have presented.
Major Packages used: sklearn, matplotlib, pandas
Keywords: Decision Tree Classifier, Random Forest Classifier, correlation matrix, confusion matrix, clarification report, precision, f1-score

https://data.world/datasets/soil
https://www.researchgate.net/profile/Mayank-Champaneri/publication/340594772_CROP_YIELD_PREDICTION_USING_MACHINE_LEARNING/links/5e935f8da6fdcca789119eba/CROP-YIELD-PREDICTION-USING-MACHINE-LEARNING.pdf

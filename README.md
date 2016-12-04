# Paste Kaggle solutions from winners
This is a collection of solutions for Kaggle competitions and a summary of useful skills I learned from those solutions. I divided the contents into two sections, the first section is my summary of those winner solutions and the second section is the collection of those solutions and some useful tutorials.


  
  
---
## Section one: my summary of those winner solutions

#### General workflow  
1. Computing environment setup
2. Exploratory data analysis 
2. A quick benchmark run
2. Data	preprocessing
3. Feature enginnering
4. Feature selection
5. Model evaluation and selection
6. Parameter turning
7. Model ensembling
8. Prediction and submission


#### Computing environment setup
1. Use Google Cloud or Amazon AWS as computing platform



#### Exploratory data analysis 
1. Calculate summary statistics.  
-. total number of samples and variables  
-. number of missing values and zeros  
-. mean, sd, min, max values for continuous variables  
-. number of unqiue values/categories for categorial and ordinal variables  
2. Plot 


  
#### A quick benchmark run
1. Use Random Forst (100 trees) without any feature enginnering to generate a quick submission. This submission can be used as a benchmark for further improvement. Plot the importance of the feaures to get a sense what are the most important features for prediction.
2. Train a simple Random Forest model and plot the confusion matrix for classfication or true-prediction-value-scatter-plot for regression. Find out where most the prediction errors come from. For example, it may come from certain categories. Need to split original training data into training and testing data. 


---
## Section two: Kaggle winner solutions and some useful tutorials

1. [Beating Kaggle the easy way by Ying Dong](https://www.ke.tu-darmstadt.de/lehre/arbeiten/studien/2015/Dong_Ying.pdf)

2. [How to get into the top 15 of a Kaggle competition using Python by Vik Paruchuri](https://www.dataquest.io/blog/kaggle-tutorial/)

3. [Awesome XGBoost](https://github.com/dmlc/xgboost/blob/master/demo/README.md)

4. [1st Place Solution for Search Results Relevance Competition on Kaggle](https://github.com/ChenglongChen/Kaggle_CrowdFlower)


5. [Kaggle Competition Past Solutions](http://www.chioka.in/kaggle-competition-solutions/)

6. [Learning Predictive Analytics: Kaggle Competition Solutions](http://analyticscosm.com/learning-predictive-analytics-kaggle-competition-solutions/)

7. [No Free Hunch](http://blog.kaggle.com/)

8. [Kaggle past solutions](https://www.kaggle.com/wiki/PastSolutions)

9. [Winning solution of Kaggle Higgs competition: what a single model can do?](https://no2147483647.wordpress.com/2014/09/17/winning-solution-of-kaggle-higgs-competition-what-a-single-model-can-do/)


more

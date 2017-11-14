# My_Projects
This repository contains my academic projects. I've used R, Perl, Python, SQL to build these projects 
<img src="https://user-images.githubusercontent.com/33647156/32763206-53ebad44-c8cc-11e7-8721-6ebdb576ee26.png" width="100" height="100" align="right" />

# R Projects

<img src="https://user-images.githubusercontent.com/33647156/32764181-2d969388-c8d2-11e7-8293-69def84b3421.jpg" width="200" height="100" align="right" />

## Analysis on golub dataset in multtest package using R 
* Performed hypothesis testing on Gd5 gene and t-test for testing population mean
* Applied two-sample t-test and Wilcoxon Sign test and Outlier testing on CD33 and CCND3 cyclin D3
* Fit a regression model on gene expression values from two probes for the expression values of the MCM3 gene
* Performed fisher's exact test for 2 by 2 contingency table

## Analysis on Iris data set using R
* Performed clustering analysis like Hierarchical Clustering to see which species are closely related

* Visualized different species using 3-D scatter plot and used different colors to indicate them

<img src="https://user-images.githubusercontent.com/33647156/32763896-801be290-c8d0-11e7-8b3b-8d5285ec465f.png" width="500" height="500" />

## Performed visualization and transformation on nycflights13 and mpg datasets using R  
* Used tidyverse packages like dplyr, ggplot2, tidyr for the analysis
* Used ggplot to find the relation between engine size and fuel efficiency of cars in mpg data frame
* Found relationship between distance and average delay of flights for each location
* Performed filters to find all the flights that had an arrival delay of two or more hours
* Used functions like arrange, select and mutate to reorder and retrieve specific information like arrival or delay of flights on 1st Jan

<img src="https://user-images.githubusercontent.com/33647156/32764010-4938123e-c8d1-11e7-822a-8fc69eacfaf2.PNG" width="400" height="300" />

## Multiple regression analysis State.x77 data using R 
* Data sets contain information about 50 states of US where 4 factors were found to be related 
* Considered the prediction of the life expectancy by the murder rates, high-school graduates and mean frost days
* Observed total variation in life expectancy across states
* Checked the model assumptions using the residuals plots on the state.x77 data

<img width="445" alt="capture" src="https://user-images.githubusercontent.com/33647156/32764182-2dab3310-c8d2-11e7-9ede-f0612c1d444a.PNG">

## Prudential Life insurance assessment using R
* Performed data pre-processing on prudential life insurance data sets
* Performed SVM, linear and decision tree regression analysis techniques and predicted the results
* Found accuracy and correlations
* Visualized predictions using histograms and pie charts 

### Data Preprocessing
1. Fill missing values using Mean, Mice

<img width="400" height="300" alt="capture" src="https://user-images.githubusercontent.com/33647156/32765231-7f1113b4-c8d7-11e7-851f-009fcafe1a3e.jpg">

2. Dimension Reduction
3. Eleminate Noise

<img width="400" height="300" alt="capture" src="https://user-images.githubusercontent.com/33647156/32765230-7efdc3f4-c8d7-11e7-8ac9-e763b9014e23.jpg">

### Generated Decision Tree 

* Splitting of training dataset in 80:20 training and testing data sets
* Build the model on training data set
* Use Rpart- Recursive partitioning for classification, regression
* Predicting model on to test data
* Measuring the model performance using Mean Absolute Error
* Improved the performance:
* Rweka- Weka is a collection of machine learning algorithms for data mining tasks, containing tools for classification, regression, clustering. Package 'RWeka' contains the interface code Package: install.packages("Rweka") Library used :library(RWeka)

#### When CP=0.01

![picture4](https://user-images.githubusercontent.com/33647156/32765539-eafc6c94-c8d8-11e7-99a2-b15f3697c71d.png)

#### When CP=0.001

![picture5](https://user-images.githubusercontent.com/33647156/32765549-f5ed3598-c8d8-11e7-9ac8-799ff160828d.png)

#### Final result prediction

![picture6](https://user-images.githubusercontent.com/33647156/32765557-ff2d1cc2-c8d8-11e7-8b61-63fcaf87f3ec.png)

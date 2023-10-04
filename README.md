# Logistical_Regression
In this project we will be working with the UCI adult dataset. We will be attempting to predict if people in the data set belong in a certain class by salary, either making <=50k or >50k per year.

## 1.0 Introduction
> The data and the description has been adapted from the University of Caliornia, Irvine...
> 

## 2.0 Solution Strategy


#### Step 01.Data Description:
- In this first section the data will be collected and studied. The missing values will be threated or removed.  First, all the '?' values are changed to N/A's and then deleted. Using the Amelia package we can create a missing map, essentially a heat map pointing out missing values.  Finally, a initial data description will carried out to know the data. Therefore some calculations of descriptive statistics will be made, such as kurtosis, skewness, media, fashion, median and standard deviation.
- ![Screenshot 2023-10-04 103218](https://github.com/pimicah/Logistical_Regression_Proj1/assets/144563378/dcc0f6f8-ae92-4b0a-808f-2d2a7c7c568b)


#### Step 02. Feature Engineering:
- In this section, a mind map will be created to assist the creation of the hypothesis and the creation of new features. These assumptions will help in exploratory data analysis and may improve the model scores.

#### Step 03. Data Filtering:
- There are a lot of columns that are cateogrical factors, however a lot of these columns have too many factors than may be necessary. In this data filtering section we'll try to clean these columns up by reducing the number of factors.

#### Step 04. Exploratory Data Analysis:
- Using GGplot2 a histogram is made to visualize the count of those with an income 50,000 and above on the Y axis and their ages on the X axis.  Those with the color red are earning less than or equal to 50k per year.  Those around 25 to 30 are rarely making over 50k but those numbers increase as the age increases.  Next, a histogram is made to visualize the count of those who work a certain amount of hours per week and a bar plot is made of regions displayed by their income class.
  ![Screenshot 2023-10-04 102639](https://github.com/pimicah/Logistical_Regression_Proj1/assets/144563378/26d04888-fc19-4bbb-8c7f-2824a7100742)
![Screenshot 2023-10-04 102741](https://github.com/pimicah/Logistical_Regression_Proj1/assets/144563378/6e0b1bb9-d8f0-4206-8c04-18b04405693e)


#### Step 05. Model Deployment:
A logical regression model is used to predict the outcome of categorical dependent variables, using one or more independent variables.  The independent variable can be either categorical or numerical.  Logistic regression is based on the logistic function, which always takes values between 0 and 1. Replacing the dependent variable of the logistic function with a linear combination of dependent variables we intend to use for regression, we arrive at the formula for logistic regression.

#### Step 06. Conclusion:
After calculating the performance in measurements of recall and precision we can see that that the percentage is .97 and .93 percent.  Given the information, there is no real way to get a correct evaluation of how good this model is.  The main factor that we need to determine is the cost associated with accuracy, precision, and recall.  Because we have no intention for this model and data as a final product/process we don't actually have a good opinion on whether this was a good model.  We don't know what we have to maximize. 


## 3.0 References
Dobson, A. J. (1990) An Introduction to Generalized Linear Models. London: Chapman and Hall.

Hastie, T. J. and Pregibon, D. (1992) Generalized linear models. Chapter 6 of Statistical Models in S eds J. M. Chambers and T. J. Hastie, Wadsworth & Brooks/Cole.

McCullagh P. and Nelder, J. A. (1989) Generalized Linear Models. London: Chapman and Hall.

Venables, W. N. and Ripley, B. D. (2002) Modern Applied Statistics with S. New York: Springer.


## 4.0 Lessons Learned
- Data Cleansing
- Logical Regression

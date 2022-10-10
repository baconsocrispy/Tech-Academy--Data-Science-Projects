DISCRETE DISTRIBUTIONS

Uniform Distribution - All events are equiprobable (Coin Toss/Card Dealt/Die Rolled)

Bernoulli Distribution - Events have binary outcome (True/False, 1/0)

Binomial Distribution - Binary outcome per iteration, many iterations

Poisson Distribution - Events / Time Interval


CONTINUOUS DISTRIBUTIONS

Normal Distribution - Symmetric distribution / Bell Curve

Student's T Distribution - 
A small sample approximation of normal distribution. 
(Accomodates extreme values significantly better)

Chi-Square Test - 
Asymmetric, Only consists of positive values. 
Typically does not mirror reality. Used for Hypothesis testing 
and goodness of fit.

Exponential Distribution - Time Intervals Between Events

Logistic Distribution - Likelihood of extreme events occuring

Bimodal Distribution - Distribution with 2 modes (Median/Mean fall in between)


FORMULAS

Probability Density Function

Variance: variance is the measure of dispersion in a data set. It 
measures how spread out a data set is. It is the average squared 
deviation of values from the mean. It is used to find the standard 
deviation that is represented by the Greek letter sigma in it’s 
lowercase form

Standard Deviation

Sample Deviation

Central Tendency - Where does center of data tend to be most (measured by
mean, median mode)

Z Score - Measures exactly how many standard deviations above or below
the mean a data point is
mu = mean | sigma = standard deviation
z = (x - mu) / sigma
The score is then looked up in the z-score positive or negative table
to get percentile

R value - range from -1 to +1 Determines the strength of how 
variables are related. The closer to zero, the less correlated they are.

Pearson's Correlation Coefficient (same as r): Measures correlation between two 
continuous variables x and y. The value will fall between -1 and 1. If the value is 1 or near 1 it is said to be perfect
correlation. Negative correlation is not necessarily bad. .5-1 is strong correlation.
Moderate correlation between .3 and .5. .3 and less is low correlation. 0 = no correlation.

*Simple Linear Regression: Regression with only one independent variable,
used to predict a dependent variable. Need to remove outliers for more 
accurate predictions.
b = r * Sy/Sx
Slope = Correlation Coefficient * Stand. Dev. y / Stand. Dev. x
function: y = mx + b

*Least Squares Regression Line: Calculation to make the variance of data from
the regression line as small as possible. 

DEFINITIONS

Descriptive Statistics - Help explain larger body of information (Mean, 
Median, Mode, GPA, etc.)

Inferential Statistics - Making conclusions about overall population from 
sample data

Coefficient is the number used to multiply a variable.

Response variable: variable outcome that is being considered in a study.

Explanatory variable: variable used to describe the reasons for the response outcomes.

B0 (Beta-naught) / B1 (beta-one): standardized regression coefficients. Estimates
resulting from regression analysis - measure how strong predictor (independent) variable
in linear regression influences dependent variable. Measured in units of standard deviation.
Beta-naught denotes y-intercept and b1 denotes slope of the line.

Epsilon: error term or random error component. Describes how a predicted value for y,
the dependent variable, may actually vary from the predicted regression line. Difference
between observed and expected.

Hat Operator (^): Placed over variables to denote that they are predicted or estimated.

Residual: measure of how well a data point matches its predicted value. Measure the
distance of a data point to the line on the graph

RMSE: Root Mean Squared Error - the standard deviation of the residuals. Smaller 
the RMSE the closer the observations are to predicted values. 1. Square the residuals,
2. find the average of the residuals. 3. Get the square root of that total. 

ANOVA: Analysis of variance. Comparing a subject group under different circumstances
to test if given circumstances had an effect on the group.

One-Way ANOVA: Determines if there is statistical significance between the means of
two or more independent groups. 

F Statistic: Higher numbers mean correlation is more likely

MAE / Mean Absolute Error: average disparity between a mean and its variation.

Standard Error: a measure of spread in statistics. The higher the number, 
the more spread out the data is. used when working with sample data. Tells you
how far sampe mean or median deviates from actual population. Estimate of the
standard deviation of the population.

T Test: a test of whether or not your sample average is statistically 
consistent with a hypothesized  population average.

T Statistic: the ratio of the departure of the estimated value of a parameter 
from its hypothesized value compared to its standard error. The purpose of the 
t-statistic is to determine whether to accept or reject a null hypothesis.

SYMBOLS

Mean - X-Bar, an x with a bar over it. Any variable with a bar
over it can represent a mean, when more than 1 mean is in an equation. 


P - probability

p̂ - p-hat
x̄ - x-bar - sample mean of x
Xi - collection of x-coordinates
ȳ - y-bar - sample mean of y
Yi - collection of x-coordinates

Δ - uppercase delta - change
δ - lowercase delta 
ε - epsilon - error term / random error component
μ - Mu - population mean
Σ - uppercase sigma - sum of collection
s - lowercase s - standard deviation of sample
σ - lowercase sigma - standard deviation of population

MACHINE LEARNING MODELS

Logistics regression: Used to find the probability of success or failure in 
an event or events. It is used when the dependent variable is binary 
(TRUE/FALSE, 1/0, etc.), while one or more of the independent variables 
could be nominal, ordinal, interval or a ratio.

Linear discriminant analysis: A method that takes a set of data that has 
been separated into multiple classes and reduces that number of classes. 
Analysis is then performed on the data within this reduced number of classes.

K-nearest neighbors (KNN): A supervised machine learning algorithm that 
can be used to solve classification and regression prediction problems. 
Its purpose is to predict the classification of new data by analyzing data 
that has been previously separated by classification.

Classification and regression tree (CART): A decision tree algorithm – 
similar to boolean function that asks whether something is true or false. 
CART is an instance of supervised machine learning.

Gaussian naive Bayes (NB): A family of probabilistic classifier models 
based on Bayes’s Theorem. Every pair of features being classified is 
independent of each other.

Support vector machine (SVM): A supervised machine learning algorithm 
that is used to separate data into classes.

TOOLS
SAS - Statistical Analysis System

SPSS - Statistical Product and Service Solutions - Widely used program for 
statistical Analysis

MACHINE LEARNING

Train Data - Data given to the algorithm to learn from
Test Data - Data given to the algorithm to test if it learned what it's supposed to

PCA / Principal Component Analysis: reduction of random variables or the 
number of features in a data set or sets, while retaining variation present
in the data. Done by transforming variables to a new set of variables that are 
known as principal components

Classifier - 

Confusion Matrix - makes note of correctly predicted outcomes vs. actual outcomes:
True Positives vs. False Positives && False Negatives vs. True Negatives

Precision and Recall: measurement of the correctness of classification in data
Precision: aims to answer what proportion of positive identifers was correct
Recall attempts to answer what proportion of actual positivies was correctly identified.

Precision = True Positives / (TP + False Positives) "Machine is correct x% of the time"
Recall = TP / (TP + False Negatives) "Machine correctly identifies x% of targets" 
If false negatives is 0, then machine is correct 100% of the time.

F1 Score / F-Score: is a measure of test accuracy. It uses Precision and Recall to find the score.

F1 = 2 * (Precision * Recall) / (Precision + Recall)

Support: Number of occurences of the true response in a class of data








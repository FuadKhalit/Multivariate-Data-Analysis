# Multivariate-Data-Analysis
Using dataset from kaggle dataset 'Football Data: Expected Goals and Other Metrics' and utilize SPSS to find which metrics is significant to improve goal scoring output. Technique used in this analysis included Stepwise Multiple Linear Regression (including ANOVA, homoscedasticity & multicollinearity test) to establish causal relationship between dependent and independent variable. Then Factor Analysis technique (correlation metric, PCA, Varimax) to reduce dimension of independent variable.
<br></br>
Dataset Link : https://www.kaggle.com/slehkyi/extended-football-stats-for-european-leagues-xg
## Multivariate Normality
Normality of the error term distribution
<br>![result](image/normality1.png)
<br>![result](image/normality2.png)
<br>![result](image/normality3.png)

<br></br>
## Linear relationship 
where it assumes there is linear relationship between independent variable and dependent variable
<br>![result](image/linear.png)

<br></br>
## Homoscedasticity (equal variance) 
Constant variance of the error terms where it assume of error term are similar across the value of independent variable
<br>![result](image/homo.png)

<br></br>
## Minimum Multicollinearity 
Independence of the error term where it assumes that all independent variable are not highly correlated with each other 
<br>![result](image/coll.png)

<br></br>
## Analysis of Variance (ANOVA) 
Determine whether there are any statistically significant differences between the means of three groups.
<br>![result](image/anova.png)

<br></br>
## Coefficients of Regression 
Y = 0.210+0.989X1-0.049X2+0.150X3
+ Y=Goal scored against opponent (scored)
+ X1=Expected Goal (xG)
+ X2= Passes completed within an estimated 20 yards of goal (deep)
+ X3= Number of goals missed in games (missed)


<br>![result](image/coef.png)

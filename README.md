# OLS-Linear-Regression-of-GDP-towards-Inflation-Germany-

I try to find the correlation between GDP (Billions of Dollars) and inflation(%) in Germany using simple linear regression OLS method in Python. The period used in this data is from 1960-2018. Using Python libraries such as numpy, pandas, and seaborr, we could see the correlation through table and graphic.

1. import related libraries and extracting data into pandadata frames [macrodataDE](https://github.com/altheanabila/OLS-Linear-Regression-of-GDP-towards-Inflation-Germany-/blob/main/macrodataDE.xlsx)

![image1](https://github.com/altheanabila/OLS-Linear-Regression-of-GDP-towards-Inflation-Germany-/blob/main/macrodataDE1.png)


2. entry this code for OLS `import statsmodels.api as sn`

3. Define X variable and y variable, see the summary. We can see that the correlation through R squared 27% and significantly correlated as the p Value stood at 0.000

![image1](https://github.com/altheanabila/OLS-Linear-Regression-of-GDP-towards-Inflation-Germany-/blob/main/macrodataDE2.png)


4. The other way, you could see the linear regression coefficient and the X prediction faster through this Python code:

`from sklearn.linear_model import LinearRegression`

![image1](https://github.com/altheanabila/OLS-Linear-Regression-of-GDP-towards-Inflation-Germany-/blob/main/macrodataDE3.png)

5. Visualize the graph! ;)

![image1](https://github.com/altheanabila/OLS-Linear-Regression-of-GDP-towards-Inflation-Germany/blob/main/MacroDE5.png)

![image1](https://github.com/altheanabila/OLS-Linear-Regression-of-GDP-towards-Inflation-Germany/blob/main/MAcroDE6.png)

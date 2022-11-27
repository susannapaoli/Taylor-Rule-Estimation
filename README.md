# Taylor Rule Estimation

In this R notebook, I carry out a statistical and econometric analysis for the Taylor Rule estimation for the evaluation of short-term interest rates in the United States in the period 1970:1 - 2020:4. 

After some exploratory data analysis techniques, I implement a first regression to evaluate the effects of inflation and output gap on the interest rates. 
After this regression, to evaluate validity of the model I implement some tests:
1. RESET - Ramsey test for linearity
2. BREUSCH-PAGAN test for homoskedasticity
3. JARQUE-BERA test for normality of the error term
4. BREUSCH-GODFREY test for uncorrelation

In the second part, I carry out a second regression, adding also the unemployment rate as a regressor. Same tests are used to evaluate the validity level of the second model. 

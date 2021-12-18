# MLR
In multiple linear regression we will have multiple inputs(independent variables) and one output(dependent variable).
Considering assumptions under MLR model we proceed.
Dataset: https://www.kaggle.com/swetapadmadalai/cars-data
**#Assumptions related to inputs and outputs:**
1. There should be a linear relationship b/w x or (input) and y or (output).     
2. Inputs should not be correlated.
   If it is correlated, we call it (multicolinearity)
     
**#Assumptions related to errors(residuals):  Error=actual-predicted**
1. Residuals or errors shd be normally distributed. (Bell shape curve). You can plot and check.
2. Errors shd be independent shd not be correlation.
   If they are correlated, it is called as (autocorrelation).
3. Homoscadesticity: 
     It means that errors shd hv constant variance.Plot scatter plot to check it. If you dont have it is called heteroscadesticity.
     
**Steps:**
1. Import libraries
2. Import Dataset
3. Check missing values
4. Exploratory Data Analysis
5. Model Building

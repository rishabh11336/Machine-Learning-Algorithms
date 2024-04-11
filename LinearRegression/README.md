# Linear Regression

## Remember the line equation all of us learned in High School  
![2](https://github.com/rishabh11336/Machine-Learning-Algorithms/blob/main/LinearRegression/Linear%20Regression%20Slides/2.png)

## Let’s take a data consist of year and income per capita of Canada. And find intercept and slope by plotting all point on graph by keeping `x-axis` for `year` and `y-axis` for `per capita income`.  
![3](https://github.com/rishabh11336/Machine-Learning-Algorithms/blob/main/LinearRegression/Linear%20Regression%20Slides/3.png)

## In equation of line `y = mx + b` “m is slope or coef_” and “b is intercept_”. For this dataset we will take years in x variable and per capita income in y variable
![4](https://github.com/rishabh11336/Machine-Learning-Algorithms/blob/main/LinearRegression/Linear%20Regression%20Slides/4.png)

## After plotting all the data points on x-y plane we can see data has a linear pattern per capita income is increasing with increasing years. After running linear regression we get straight line which is a best fit line with least amount of error with respect to data as trained model. Which we can see in below image
![5](https://github.com/rishabh11336/Machine-Learning-Algorithms/blob/main/LinearRegression/Linear%20Regression%20Slides/5.png)

## least amount of error can be calculated by using various metric such as
- Mean Absolute Error(MEA)
- Mean Squared Error(MSE)
- R² Score
- [various other metrics](https://scikit-learn.org/stable/modules/model_evaluation.html)
![6](https://github.com/rishabh11336/Machine-Learning-Algorithms/blob/main/LinearRegression/Linear%20Regression%20Slides/6.png)

## R² score is coefficient which explain the variation of predicted value from actual value. Commonly Mean Squared Error(MSE) is also known as Least Squared Error.

## Yes there is extension of linear regression known as multi variable linear regression. The main difference here, this has multiple features in dataset.
![7](https://github.com/rishabh11336/Machine-Learning-Algorithms/blob/main/LinearRegression/Linear%20Regression%20Slides/7.png)

## As we have already seen above after training with Linear Regression Model we get best fit line as model or the equation of line. In case of multi variable linear regression or regression with multiple dimension data(more than one feature excluding target[y]) we get best fit plane or tensor.
![8](https://github.com/rishabh11336/Machine-Learning-Algorithms/blob/main/LinearRegression/Linear%20Regression%20Slides/8.png)

## We can imagine 3-Dimension but we cannot imagine 4-D or higher, their were attempts to present higher dimension but they are still very complex to talk about for now. Best way is to see them in terms of mathematical equation as we can represent line and plane or tensor (3-D matrix or higher).
![11](https://github.com/rishabh11336/Machine-Learning-Algorithms/blob/main/LinearRegression/Linear%20Regression%20Slides/11.png)

![12](https://github.com/rishabh11336/Machine-Learning-Algorithms/blob/main/LinearRegression/Linear%20Regression%20Slides/12.png)
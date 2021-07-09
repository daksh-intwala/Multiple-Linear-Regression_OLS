# Multiple-Linear-Regression_OLS
Ordinary Least Squared method was implemented to analyze an MLR problem. 
____________________________________________________________________________

# Steps: 
1.	Importing Relevant libraries:
	    a. Matplotlib	 b.	Numpy
      c. Pandas	     d. Scipy
	    d. Seaborn	   e.	Statsmodel
	    f. Sklearn	
2.	Reading the Data Set:
    It was done using padans lib’s function read_csv()
3.	Training the DataSet: 
    Divided the DataSet into 4:1 ratio where 80% data is reserved for training purpose and 20% data is reserved for testing purpose. 
4.	Applied Model:
    OLS (Ordinary Least Squares Method) was used to make the model.
    The reason to select this method is because according to the given data, we have 6 parameters (independent variables) 
    that are available to predict the result (dependent variable). More than one number of independent variable makes our model to be an MLR, 
    therefore, to implement MLR we are using OLS to make a multilinear regression model here.
5.  *Dependent Variable:
    1.  Total no. of persons Killed in 2019 (Y)
		*Independent Variables:
    1.	Persons Killed due to Bridge (x1)
    2.	Persons Killed due to Culvert (x2)
    3.	Persons Killed due to Potholes (x3)
    4.	Persons Killed due to Steep Grade (x4)
    5.	Persons Killed due to Under Construction Sites (x5)
    6.	Persons Killed due to Other reasons (x6)
    
# Remember:
  - Type Error in defining X : Solve it by using np.ndarray(dtype="int/float")
  - This is the case of Multicollinearity, evident by OLS Regression Result. Understand it here,
      https://statisticsbyjim.com/regression/multicollinearity-in-regression-analysis/
      
      


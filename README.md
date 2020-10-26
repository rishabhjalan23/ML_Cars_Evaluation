# ML_Cars_Evaluation
This is my first machine learning model. 
The dataset I have used is famous mpg dataset of UCI machine learning repositry.
In this notebook, I have started with data preprocessing, in which I have processed the missing data by dropping them. I'm still learning how to handle missing data, will try to encorparate that in future analysis.
After that, I have done basic eda, starting with descriptive statistics and finally concluded it with correlation matrix.
While building a model, initailly I dropped 3 highly correlated variables and the origin column and ran the linear regression with two variables. To immprove the overall score I also ran it with 5-fold cv.
Later, I added all the 3 correlated variable one at a time, to check the overall improvement in the model score.
Finally, I encoded origin as dummy varaibles and used linear regression to build the model. This method gave the highest r-square and lowest mse.
I'm still learing and new in this field. Looking forward to valuable suggestion to improve my understanding. Thankyou.

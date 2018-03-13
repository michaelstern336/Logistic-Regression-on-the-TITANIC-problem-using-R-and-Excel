# Logistic-Regression-on-the-TITANIC-problem-using-R-and-Excel
The famous dataset and kaggle-project predicting the fate of the doomed passengers on the RMS TITANIC-and so my experiments with regression modeling continues!
Hi. So I've reimplemented this logistic regression model to predict the fate of every passenger on the ship using R on R Studio- a function called 'glm' or generalized linear modeling (family-binomial; link-logit (as this is logistic regression). A family is the description of the error distribution. glm is used to fit generalized linear models or basically generate the best fit graph which is closest to the residuals. 
After evaluating the coefficients, you need to summarize the model before keeping or rejecting explanatory variables (refer to p-value). Of course, before you perform regression, you need to modify the dataset-remove data-that's not required at all, or decide on hwo to treat blank data (hint: NA) etc. 
I have implemented the model on excel, just to prove its versatility. Of course, the data was treated a bit differently on excel than on R-Studio. Rather than rejecting the 'NA' values on excel for Age, we replaced it with the mean of all ages (this is an example). 

The performace was approximately the same accross both platforms (around 80% of the predictions were correct). Refer to comments on the project to get more clarity. 

Welcome to all kinds of suggestions and improvements!

# About  
---
This code compares SGD regression and OLS regression performance and best fit values on the abalone dataset from UCIMLrepo. The dataset can be found [here](https://archive.ics.uci.edu/dataset/1/abalone) and imported using the code provided in the .ipynb. 
It contains 8 features used to predict the number of Rings or Age (number of rings +1.5 years) of abalone including its height, shell weight, etc. From the models, it can be concluded that in this case, the OLS Regression model out performed the SGD Regression model as it produced a higher R^2 value despite the fact that GridSearchCV was utilized to find the best hyperparameters for the model.
That being said, the dataset in general was insufficient in building a good model to predict our target variable in general as the R^2, which tells us how much variation of the target variable can be explained by the independent variables, was relatively low in both models (just under 0.5 at best).
After standardizing and choosing the best variables to fit into the models, it can still be concluded that OLS regression was the better model to predict the number of ring in an abalone.

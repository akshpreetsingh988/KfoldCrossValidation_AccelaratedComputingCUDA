# MachineLearning 
K_Fold_Cross_Validation_CUDA.ipynb file content  : 
Done using GPU accelarated Computing 

Download the dataset regarding USA House Price Prediction from the following link:

https://drive.google.com/file/d/1O_NwpJT-8xGfU_-3llUl2sgPu0xllOrX/view?usp=sharing

Load the dataset and Implement 5- fold cross validation for multiple linear regression (using
least square error fit).
Steps:
1. Divide the dataset into input features (all columns except price) and output variable (price)
2. Scale the values of input features.
3. Divide input and output features into five folds.
4. Run five iterations, in each iteration consider one-fold as test set and remaining four sets as
training set. Find the beta (β) matrix, predicted values, and R2_score for each iteration using least
square error fit.
5. Use the best value of (β) matrix (for which R2_score is maximum), to train the regressor for
70% of data and test the performance for remaining 30% data.

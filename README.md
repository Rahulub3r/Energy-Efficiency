# Energy-Efficiency-Project

## Regression and Classification

### Regression

Data Transformation, Single Output and Multioutput regression were performed to calculate **heating and cooling loads** on data which use features like roof area, orientation, glazing area, glazing area distribution, relative compatcness, surface area and overall height

#### Models
1) Linear Regression
2) Lasso Regression
3) Ridge Regression
4) Polynomial Regression
5) KNN Regressor
5) Support Vector Regressor
6) Random Forest Regressor
7) Gradient Boosting Regressor (finally chose this)

Best train accuracy ~ 99.8% and Best validation accuracy ~ 99.2%

### Classification
Nerual network were used to perform classification of the overall load
Network contained one input layer, one hidden layer and one output layer
Grid Search was difficult to run on my pc so Grid Search was done manually using for loops
KERAS package was used for this task

#### Tuned parameters
1) Epochs (200)
2) Batch size (20)
3) Optimizer (Nesterov Adam optimizer)
4) Learning rate of the optimizer (0.1)
5) Initialization mode of weights (normal)
6) Activation function (softsign)
7) Drop out rate and weight constraint (0.3, 3)
8) Number of neurons in the hidden layer (5)

Best train accuracy ~ 96% and Best validation accuracy ~ 94%




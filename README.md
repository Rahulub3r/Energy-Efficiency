# Energy-Efficiency-Project

**Description:** The [energy efficiency](http://archive.ics.uci.edu/ml/datasets/energy+efficiency) dataset analysis is done using 12 different building shapes simulated in Ecotect.<br>
**Software:** Python 3.7 <br>
**Presentation:** Jupyter Notebook <br>
**Goal:** Predicton of **Heating** and **Cooling Loads** for various buildings<br>

## Tasks
1. Load libraries
2. Data Cleaning and Transformation
3. Modeling <br>
&nbsp;&nbsp;&nbsp;&nbsp; 3.1 Regression<br>
&nbsp;&nbsp;&nbsp;&nbsp; 3.2 Classification<br>

### Details on Regression and Classification

#### 3.1 Regression
**Targets:** Two kinds; heating load, and cooling load <br>
**Explanatory Variables:** relative compactness, surface area, wall area, roof area, overall height, orientation, glazing area, glazing area distribution<br>

##### Models
1) Linear Regression (Single Output and Multiple Output)
2) Lasso Regression
3) Ridge Regression
4) Polynomial Regression
5) KNN Regressor
5) Support Vector Regressor
6) Random Forest Regressor
7) Gradient Boosting Regressor (finally chose this)

**Best train accuracy ~ 99.8% and Best validation accuracy ~ 99.2%**

#### 3.2 Classification
**Model:** Artificial Neural Network (One input layer, one hidden layer, and one output layer)<br>
**Classes:** 3 categories for both loads, broken down by looking at histograms<br>
**Parameter tuning:** Using grid search<br>
**Package:** KERAS<br>

##### Tuned parameters
1) Epochs (200)
2) Batch size (20)
3) Optimizer (Nesterov Adam optimizer)
4) Learning rate of the optimizer (0.1)
5) Initialization mode of weights (normal)
6) Activation function (softsign)
7) Drop out rate and weight constraint (0.3, 3)
8) Number of neurons in the hidden layer (5)

**Best train accuracy ~ 96% and Best validation accuracy ~ 94%**




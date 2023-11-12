# Gradient Descent

This section presents a **custom** implementation of various 
**gradient descent algorithms** for solving **regression tasks**:

* **[descents.py](./descents.py)**: **efficient implementation of gradient descent**:
  * for the following **loss functions** (with and without regularization):
    * _MSE_
    * _MAE_
    * _LogCosh_
    * _Huber-loss_
  * and **gradient descent algorithms**:
    * Full Gradient Descent (_FGD_)
    * Stochastic Gradient Descent (_SGD_)
    * Momentum-based Gradient Descent (_Momentum_)
    * Adaptive Step Gradient Descent (_Adam_)
* **[linear_regression.py](./linear_regression.py)**: software **implementation 
of linear regression**:
  * with regularization
  * without regularization
* **[practice-03-gd-Rubanov.ipynb](./practice-03-gd-Rubanov.ipynb)**: 
  * _comparison_ of implemented algorithms across various parameters
  * exploratory data analysis (_EDA_) 
  * _visualization_ of the results of the algorithms.

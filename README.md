## E-Commerce Shopper Intentions
E-Commerce Shopper Intentions: Logistic regression to predict purchase/revenue

Aiming to predict the outcome of an instance resulting either in purchase or no purchase. Series of "instances" or observations of 12,330 sessions of online shopping/e-commerce. Each observation belonged to a different user within 1 year.

### What needs to be done
The final logistic regression model needs to be conducted.

June 10th update: I cannot seem to run a reliable logistic model. I keep getting this issue:

Inverting hessian failed, no bse or cov_params available
  'available', HessianInversionWarning)
/opt/anaconda3/lib/python3.7/site-packages/statsmodels/base/model.py:548: HessianInversionWarning: Inverting hessian failed, no bse or cov_params available
  'available', HessianInversionWarning)
/opt/anaconda3/lib/python3.7/site-packages/statsmodels/discrete/discrete_model.py:3409: RuntimeWarning: divide by zero encountered in double_scalars

The data seems to be fine... need to figure out if the data is the problem, the code is the problem, or the variable modeling itself is the problem.

https://www.kaggle.com/roshansharma/online-shoppers-intention

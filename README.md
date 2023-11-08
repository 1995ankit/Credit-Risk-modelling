# Credit-Risk-modelling
### This code creates features on credit risk data using the Weight of Evidence.

#### The project contains two Jupyter Notebook files - Feature_engineering.ipynb and PD_modelling.ipynb
  
#### The file 'Feature_engineering' uses existing variables to create new relevant features:
* Extracted numerical and date features from sting features by using replace() and datetime() functions.
* One-hot encoding was used to create dummy variables for categorical features. A reference dummy variable is removed from every such feature.
* Features with missing values are either removed, or the missing values are replaced with zero, mean, maximum, or value from some other feature.
* As creating dummy variables for every categorical feature resulted in lots of features, features were then grouped based on their weight of evidence using coarse classification
* Similarly, continuous variables were grouped using their W.O.E by coarse classification.

#### The file 'Feature_engineering' uses existing variables to create new meaningful features.
* SKlearn logistic regression is used for the modeling.
* ROC curve is used to decide the threshold below which the model classifies a customer as default. The threshold is decided based on the need of the bank, i.e, whether to reject more applications or give more loans.



###### The project is done as a capstone project of course - Credit Risk Modelling.

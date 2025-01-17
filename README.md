# PowerCo-s-Customer-churn-problem

PowerCo, a major gas and electricity provider, faces a churn issue with many customers switching to competitors. We believe price sensitivity is a major factor and propose a data-driven approach to analyze customer behavior and find the connection between price and churn.


In order to test the hypothesis of whether churn is driven by the customers’ price sensitivity, we would need to model churn probabilities of customers, and derive the effect of prices on churn rates. 

We would need the following data to be able to build the models.

Customer data - which should include characteristics of each client, for example, industry, historical electricity consumption, date joined as customer etc.
Churn data - which should indicate if customer has churned
Historical price data – which should indicate the prices the client charges to each customer for both electricity and gas at granular time intervals

Once we have the data, the work plan would be:

We need to define what price sensitivity is and calculate it
We need to prepare the data and engineer features 
Then, we can test our hypothesis using a binary classification model (e.g. Logistic Regression, Random Forest, Gradient Boosted Machines to name a few)
We would choose a model from one of the tested algorithms based on the model complexity, the explainability, and the accuracy of the models.
With the trained model, we would be able to extrapolate the extent to which price sensitivity influences churn

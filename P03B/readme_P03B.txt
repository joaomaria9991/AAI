-- Problem ID -- 
P03B

-- Description --
The dataset is an example of product sales at a korean company for a small set of spare parts products between 2018-01-02 and 2020-12-30. 
Notice that products have quite different sales behaviour.

-- Fields --
productID: the unique identifier of a product
quant: the demand quantity
dt: day of the sale

-- Proposed Problem --
Given the sales in the previous 3 days, we want to predict the sales of today. 
For that you should first determine the set of unique productIDs and consider its alphabetic order in a vector called P. 
Let X(t) be the vector of total sales corresponding to P. The challenge is given X(t-3),X(t-2),X(t-1) find X(t) where t is any day in the period.

You may use any technique learned in AIA but should include a LSTM.

-- Keywords --
sales
time series
machine learning / deep learning
regression
prediction

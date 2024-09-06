# Cost Function

Cost function measures the performance of a model by quantifying the difference between the predicted values and the actual values. The goal of a machine learning model is to minimize the cost function.

For example, in [linear regression](../algorithm/supervised/linear-regression.md), the training data is used to fit the parameters $w$,$b$ by minimizing a measure of the error between the predictions $f_{w,b}(x^{(i)})$ and the actual data $y^{(i)}$. During training we measure the cost over all the training samples $x^{(i)},y^{(i)}$. The cost function is defined as:

$$J(w,b) = \frac{1}{2m} \sum\limits_{i = 0}^{m-1} (f_{w,b}(x^{(i)}) - y^{(i)})^2$$
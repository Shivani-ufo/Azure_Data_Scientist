## Poisson Regression

Poisson regression is intended for use in regression models that are used to predict numeric values, typically counts. Therefore, you should use this module to create your regression model only if the values you are trying to predict fit the following conditions:
The response variable has a Poisson distribution.

_Counts cannot be negative. The method will fail outright if you attempt to use it with negative labels._
_A Poisson distribution is a discrete distribution; therefore, it is not meaningful to use this method with non-whole numbers._
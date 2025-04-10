# learning_Optimization_techniques_ML

Optimization Methods
Until now, you've always used Gradient Descent to update the parameters and minimize the cost. In this notebook, you'll gain skills with some more advanced optimization methods that can speed up learning and perhaps even get you to a better final value for the cost function. Having a good optimization algorithm can be the difference between waiting days vs. just a few hours to get a good result.

By the end of this notebook, you'll be able to:

Apply optimization methods such as (Stochastic) Gradient Descent, Momentum, RMSProp and Adam
Use random minibatches to accelerate convergence and improve optimization
Gradient descent goes "downhill" on a cost function  𝐽
 . Think of it as trying to do this:

Figure 1 : Minimizing the cost is like finding the lowest point in a hilly landscape
At each step of the training, you update your parameters following a certain direction to try to get to the lowest possible point.
Notations: As usual,  ∂𝐽∂𝑎=
  da for any variable a.

Let's get started!

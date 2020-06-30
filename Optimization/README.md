###### Background Information

>  This repository a collection of my works on __numerical optimization__, with a primary focus on *convex optimization*.

>  Most of the algorithms were introduced in the `Math 173 A-B - Optimization for Data Science` classes at UCSD. We studies the motivations (ie. the problems we want to solve) and the algorithms, both their theoretical results and actual performance.

***

<br/>

#### Main Topics

1.  __Unconstrained__ vs. __Constrained__ optimization:
    1.  Objective: minimize f(x)
    2.  Equality conditions, for example h(x) = 0
    3.  Inequality conditions, for example g(x) <= 0

2.  __First-order__ methods:
    1.  Gradient descent
        1.  __[Standard Gradient Descent](https://nbviewer.jupyter.org/github/thn003/optimization_num_analysis/blob/master/Optimization/Gradient%20Descent%20Algorithm.ipynb#Helper_Functions)__
        2.  GD with Momentum
        3.  GD with Nesterov
    2.  Stochastic gradient descent
    3.  Conjugate descent
    4.  __[Dual ascent](https://nbviewer.jupyter.org/github/thn003/NumAnalysis_Optimization/blob/master/Optimization/Dual%20Ascent.ipynb)__
    5.  Method of multipliers

3.  __Second-order__ methods:
    1.  Newton's method

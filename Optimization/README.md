###### Background Information

>  This repository a collection of my works on __numerical optimization__, with a primary focus on *convex optimization*.

>  Most of the algorithms, or their vanilla versions, were introduced in the `Math 173 A-B - Optimization for Data Science` classes at UCSD. We study the motivations (ie. the problems we want to solve) and the algorithms, both their theoretical results and actual performance.

***

<br/>

#### Main Topics

1.  __Unconstrained__ vs. __Constrained__ optimization:
    1.  Objective: minimize f(x)
    2.  Equality conditions, for example h(x) = 0
    3.  Inequality conditions, for example g(x) <= 0

2.  __First-order__ methods:
    1.  Gradient descent
        1.  __[(Standard) Gradient Descent](https://nbviewer.jupyter.org/github/thn003/NumAnalysis_Optimization/blob/master/Optimization/Gradient%20Descent.ipynb)__
        2.  GD with Momentum
        3.  GD with Nesterov
    2.  Stochastic Gradient Descent
    3.  Conjugate Descent
    4.  __[Dual Ascent](https://nbviewer.jupyter.org/github/thn003/NumAnalysis_Optimization/blob/master/Optimization/Dual%20Ascent.ipynb)__
    5.  __[Method of Multipliers](https://nbviewer.jupyter.org/github/thn003/NumAnalysis_Optimization/blob/master/Optimization/Method%20of%20Multipliers.ipynb)__

3.  __Second-order__ methods:
    1.  Newton's method



An example of the convergence rate across different variants of Gradient Descent on the MNIST dataset.

<center>
<img src="https://github.com/thn003/NumAnalysis_Optimization/blob/master/Optimization/MNIST%20Digits%20-%20Algorithms%20convergence%20rates.png" width="60%" height="60%" class="center">
</center>

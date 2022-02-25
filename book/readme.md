Computational Methods for Physics & Astronomy
===================================

## Book version at:
https://restrepo.github.io/ComputationalMethods

by: **Sebastian Bustamante** *2014/2015* **Diego Restrepo ** 2017/...**

![](https://raw.githubusercontent.com/sbustamante/ComputationalMethods/master/material/figures/Collage.png)

This course is intended for students of Astronomy and Physics at the Universidad de Antioquia
and will cover some numerical methods commonly used in science and specially in
astronomy. These topics will be addressed from a formal context but also keeping
a practical and computational approach, illustrating many useful applications in
problems of physics and astronomy.


The practical component will be almost entirely developed in *Python* and
slightly less in *C* (when computational performance is required).
However students with knowledge in other programming languages (except
privative languages like MatLab, Mathematica) are also aimed to use them.


In this repository it can be found all the related material of the course,
including the detailed program, notes and presentations, examples (ipython
notebooks) and homeworks. (This repository may be subject to changes continuously
as the course advances).

[Submodules help](https://git-scm.com/book/en/v2/Git-Tools-Submodules)

[**SYLLABUS**](https://github.com/sbustamante/ComputationalMethods/raw/master/syllabus/Programa_M%C3%A9todos_Computacionales.pdf):
detailed description of the program of the course, including a brief motivation and presentation,
topics to be covered, evaluation and bibliography.


Contents
--------

### 1. **Python** *(1 week)*

**Topics**
- [Overview of python](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/overview-python.ipynb)
- [Basic scripting](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/basic-scripting.ipynb)
- [Implementation of scientific libraries](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/scientific-libraries.ipynb)
- [Plotting with matplotlib](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/matplotlib.ipynb)
- [Ipython notebooks](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/ipython-notebooks.ipynb)

**Activities**
- *Activity 01:* Solve the problems in the section [Exercises](https://github.com/sbustamante/ComputationalMethods/blob/master/material/Basic_exercises.ipynb).

### 2. **Mathematical Preliminaries** *(1 week)*

**Topics**
- [Computer arithmetics and round-off methods](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/computer-arithmetics.ipynb)
- [Algorithms and convergence](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/algorithms-convergence.ipynb)

### 3. **One Variable Equations** *(2 weeks)*

**Topics**
- [Bisection method](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/one-variable-equations.ipynb#Bisection-Method)
- [Fixed-point iteration](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/one-variable-equations.ipynb#Fixed-point-Iteration)
- [Newton-Raphson method](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/one-variable-equations.ipynb#Newton-Raphson-Method)
- [Secant method](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/one-variable-equations.ipynb#Secant-Method)

### 4. **Interpolation Techniques** *(2 weeks)*

**Topics**
- [Linear interpolation](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/interpolation.ipynb#Linear-Interpolation)
- [Lagrange polynomials](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/interpolation.ipynb#Lagrange-Polynomial)
- [Divided differences](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/interpolation.ipynb#Divided-Differences)
- [Hermite interpolation](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/interpolation.ipynb#Hermite-Interpolation)

### 5. **Numerical Calculus** *(2 weeks)*

**Topics**
- [Numerical differentiation](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/numerical-calculus.ipynb#Numerical-Differentiation)
- [Numerical integration](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/numerical-calculus.ipynb#Numerical-Integration)
- [Composite numerical integration](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/numerical-calculus.ipynb#Composite-Numerical-Integration)
- [Adaptive quadrature methods](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/numerical-calculus.ipynb#Adaptive-Quadrature-Methods)
- [Improper integrals](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/numerical-calculus.ipynb#Improper-Integrals)

**Activities**
- *Activity:* [ Derivative exercise ](http://nbviewer.jupyter.org/github/sbustamante/ComputationalMethods/blob/master/activities/T-profile-bar.ipynb)

### 6. **Linear Algebra** *(2 weeks)*

**Topics**
- [Linear systems of equations](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/linear-algebra.ipynb#Linear-Systems-of-Equations)
- [Gaussian elimination](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/linear-algebra.ipynb#Gaussian-Elimination)
- [Pivoting strategies](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/linear-algebra.ipynb#Pivoting-Strategies)
- [Matrix inversion](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/linear-algebra.ipynb#Matrix-Inversion)
- [Determinant of a Matrix](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/linear-algebra.ipynb#Determinant-of-a-Matrix)
- [LU factorization](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/linear-algebra.ipynb#LU-Factorization)

### 7. **Differential Equations** *(2 weeks)*

**Topics**
- [First order methods](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/differential-equations.ipynb#First-Order-Methods)
- [High order methods](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/differential-equations.ipynb#High-Order-Methods)
- [Two-Point boundary value problems](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/differential-equations.ipynb#Two-Point-Boundary-Value-Problems)

### 8. **Statistics** *(1 week)*

**Topics**
- [Data adjust](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/statistics.ipynb)
- [Random Numbers](http://nbviewer.ipython.org/github/sbustamante/ComputationalMethods/blob/master/material/statistics.ipynb#Random-Numbers)


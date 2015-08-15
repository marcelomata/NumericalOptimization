## Overview

This repository has MATLAB package for linear and nonlinear optimization,
implemented by me based on Simplex method and modified Newton method; 

## Linear Optimization

For Linear programming, the function mylinprog(A,b,c): 
           minimize        c'*x,
          subject to     A*x >= b, x >= b

## Nonlinear Optimization

For Nonlinear part, the function myzerofinder(F) computes the root of
the equation F(x) = 0; the function unconopt(f,x0) calculates the local
minimizer of f around moving from x0.

Implemented by Zhiwei Jia. Welcome to visit my [person website](http://zhiweijia.website).


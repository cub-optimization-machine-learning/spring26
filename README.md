# CUB Optimization Methods in Machine Learning, Spring 2026

Optimization methods underlie in solution of many problems in computer science. In machine learning, one needs to solve an optimization problem during fitting of some prediction model on data, and efficiency in solving such optimization problems directly influences practical applicability of the correspondent machine learning approaches. This course aims to provide students with theoretical knowledge and practical skills in understanding both classic and recent continuous optimization methods (including optimization of non-convex functions) and important features in application of such methods for solving machine learning and deep learning problems. The course supposes a detailed discussion of practical aspects in implementation and usage of optimization routines. As the result of the course students will be able to choose and customize optimization method with better fit for their applied problems.

**Instructor**: Dmitry Kropotov

**Timetable**: the classes are scheduled on Mondays 14:15 - 17:00 in WH-8.

**Telegram chat for questions and discussion**: [link](https://t.me/+TBVX-k4r8MpkZjIy)

**Assignments**: All assignments are given and checked in the corresponding Teams space

## Course assessment

Assessment Component 1: written examination, Duration: 60 min, Weight: 50 %

Assessment Component 2: Practical assessments, Weight: 50 %

Completion: To pass this module, the examination of each module component must be passed with at least 45%.

## Exam

The written exam will be offline on campus. Test exam from the previous years: [formulation](Materials/test_exam.pdf), [reference solution](Materials/test_exam_reference.pdf)

## Lectures

| Date | Number | Topic | Materials |
| :---: | :---: | --- | --- |
| 09.02.26 | 01 | Introduction to the course. Function classes for optimization. Finding Hessians using second differentials. Convergence speed of optimization algorithms. Armijo/Wolfe conditions for non-exact one-dimensional minimas.	| NW, sections 3.1, 3.5<br> [Lecture notes](Materials/Ch1.pdf)<br> [Notes on convergence speed (in russian)](Materials/convergence_speed.pdf) |
| 16.02.26 | 02 | The algorithm for finding non-exact 1d minimas. Gradient Descent, its convergence speed for different function classes. Examples. Finite-difference methods.	| NW, sections 3.2, 3.3<br> [Lecture notes](Materials/Ch2.pdf)  |
| 23.02.26 | 03 | Newton method. Invariance to linear scaling. Global and local convergence. Matrix decompositions for solving linear systems. Hessian correction schemes.	| NW, sections 3.3, 3.4<br> [Lecture notes](Materials/Ch3.pdf)  |
| 02.03.26 | 04 | Convex sets, convex functions, convex optimization problems. 	| [Lecture notes](Materials/Ch4.pdf)<br> BV, sections 2.1-2.3; BV, sections 3.1, 3.2   |
| 09.03.26 | 05 | Conjugate Gradient method for solving linear systems, its convergence properties. Non-linear CG. Hessian-Free Newton (Newton-cg), its convergence speed.	| NW, sections 5.1, 5.2; NW, section 7.1;<br> [Presentation](Materials/nonlinear_cg.pptx)<br> [Lecture notes](Materials/Ch5.pdf)  |
| 16.03.26 | 06 | Quasi-Newton methods SR1, BFGS and L-BFGS. 	| NW, sections 6.1, 6.2, 7.2;<br> [Lecture notes](Materials/Ch6.pdf)   |
| 23.03.26 | 07 | Constrained optimization problem, KKT theorem (first and second order necessary and sufficient conditions). Dual optimization problem. Epigraph and reparameterization reformulations.	| NW, chapter 12;<br> [Lecture notes 1](Materials/Ch7.pdf)<br> [Lecture notes 2](Materials/Ch8.pdf)   |
| 30.03.26 | -- | *Semester break, no classes*
| 06.04.26 | -- | *Public holiday, no classes*
| 13.04.26 | 08 | Revised simplex method for Linear Programming. Log-Barrier method for constrained convex programming.	| NW, chapter 13; BV, sections 10.2, 11.1-11.4  |
| 20.04.26 | 09 | Non-smooth convex optimization: examples, subgradient method. Subdifferential calculus. | [Presentation](https://web.stanford.edu/class/ee364b/lectures/subgrad_method_notes.pdf)<br> [Lecture notes](Materials/Subgradients.pdf)
| 27.04.26 | 10 | Proximal methods for composite function minimization. ADMM with examples. | [Presentation](https://www.stat.cmu.edu/~ryantibs/convexopt/lectures/prox-grad.pdf)
| 04.05.26 | 11 | Closed functions, Fenchel conjugate functions and conjugate (dual) norms. Projections and proximal operators. |  
| 11.05.26 | 12 | Stochastic optimization methods for convex finite-sums minimization. Differentiation through optimization methods. | [paper 1](https://arxiv.org/abs/1309.2388), [paper 2](https://proceedings.neurips.cc/paper/2013/file/ac1dd209cbcc5e5d1c6e28598e8cbbe8-Paper.pdf), [paper 3](https://arxiv.org/abs/1401.7020), [paper 4](https://proceedings.mlr.press/v48/rodomanov16.html), [paper 5](https://arxiv.org/abs/1703.00443), [paper 6](https://arxiv.org/pdf/1502.03492)


## Literature
1. J. Nocedal, S. Wright. [Numerical Optimization](https://www.math.uci.edu/~qnie/Publications/NumericalOptimization.pdf). Springer, 2006.
1. S. Boyd, L. Vandenberghe. [Convex Optimization](https://stanford.edu/~boyd/cvxbook/). Cambridge University Press, 2004.

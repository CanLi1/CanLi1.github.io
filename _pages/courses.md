---
title: "Li Group - Courses"
layout: textlay
excerpt: "Courses"
sitemap: false
permalink: /courses
---

## CHE 597: Computational Optimization, Spring 2024

**Instructor:** Can Li 
**Email:** canli@purdue.edu

---

### Course Description:
This is a graduate-level introductory course to mathematical optimization. We will cover the theory and algorithms of linear programming, mixed-integer linear/nonlinear programming, conic programming, global optimization of nonconvex problems, and decomposition algorithms for mixed-integer programs. Special focus will be given to using the APIs of modern computational software including CPLEX, Gurobi, Mosek, Pytorch with implementations in Python. We will motivate the algorithms using modern applications in chemical engineering, transportation, energy systems, machine learning, and control.

The course lectures will be 30% proofs, 50% algorithms and computation, and 20% modeling and applications in engineering. The homework will keep a similar portion. However, we will not have proofs in the exams since this is a class targeted at engineering students. 

| Date       | Topic                                                                       | Slides     | Homework | Handouts |
|-------------------------------|--------------------------------------------------------|---------------------|-------------------|-------------------|
| Tue Jan 9  | Introduction to Course                                                      |  |      |         [Pyomo Tutorial]() |
| Thu Jan 11 | Convex sets, functions                                                      | |          |          |
| Tue Jan 16 | Unconstrained optimization                                |  |          |          |
| Thu Jan 18 | Linear Programming Applications                                                             | |          |          |
| Tue Jan 23 | Polyhedron Theory                                |  |     |          |
 | Thu Jan 25 |   Linear Programming Duality                                                     |  |          |          |
<!---| Tue Jan 30 | Applications                                                                | [Slides]() | HW 3     |          |
| Thu Feb 1  | Basics of polyhedral theory, LP duality                                     | [Slides]() |          |          |
| Tue Feb 6  | SOCP                                                                        | [Slides]() | HW 4     |          |
| Thu Feb 8  | SDP, Goemans-Williamson                                                     | [Slides]() |          |          |
| Tue Feb 13 | Applications                                                                | [Slides]() | HW 5     |          |
| Thu Feb 15 | Optimality conditions                                                       | [Slides]() |          |          |
| Tue Feb 20 | Barrier algorithm, interior point algorithm                                 | [Slides]() | HW 6     |          |
| Thu Feb 22 | Review for Midterm                                                          | [Slides]() |          |          |
| Tue Feb 27 | **Midterm Exam**                                                            |            |          |          |
| Thu Mar 1  | Modeling of discrete and continuous decisions                               | [Slides]() | HW 7     |          |
| Tue Mar 6  | Propositional logic, modeling of disjunctions                               | [Slides]() |          |          |
| Thu Mar 8  | Applications                                                                | [Slides]() | HW 8     |          |
| Tue Mar 13 | **Spring Break (No Class)**                                                 |            |          |          |
| Thu Mar 15 | **Spring Break (No Class)**                                                 |            |          |          |
| Tue Mar 20 | Branch and bound                                                            | [Slides]() | HW 9     |          |
| Thu Mar 22 | Cutting planes                                                              | [Slides]() |          |          |
| Tue Mar 27 | Disjunctive programming                                                     | [Slides]() | HW 10    |          |
| Thu Mar 29 | Applications                                                                | [Slides]() |          |          |
| Tue Apr 3  | Convex relaxations, McCormick Inequality                                    | [Slides]() | HW 11    |          |
| Thu Apr 5  | Spatial branch and bound                                                    | [Slides]() |          |          |
| Tue Apr 10 | Mixed-integer nonlinear programming                                         | [Slides]() | HW 12    |          |
| Thu Apr 12 | Benders decomposition, stochastic programming                               | [Slides]() |          |          |
| Tue Apr 17 | Dantzig Wolfe decomposition, column generation, vehicle routing problems    | [Slides]() | HW 13    |          |
| Thu Apr 19 | Lagrangian decomposition                                                    | [Slides]() |          |          |
| Tue Apr 24 | ADMM                                                                        | [Slides]() | HW 14    |          |
| Thu Apr 26 | Numerical linear algebra                                                    | [Slides]() |          |          |
| Tue Apr 27 | Advanced solver callbacks, Parallel computing, GPU computing                | [Slides]() |          |          | --->


### Topics Covered (tentative)
#### Optimization basics
- Convex sets, functions
- Unconstrained optimization, gradient descent, Newton's method
- Simple applications of optimization models
- Modeling using pyomo

#### Linear and conic programming
- Applications
- Basics of polyhedral theory, LP duality
- Second-order cone programming (SOCP)
- Semidefinite programming (SDP), Goemans-Williamson

#### Nonlinear programming
- Applications
- Optimality conditions
- Barrier algorithm, interior point algorithm

#### (Mixed)-integer linear programming
- Modeling of discrete and continuous decisions
- Propositional logic, modeling of disjunctions
- Applications
- Branch and bound
- Cutting planes
- Disjunctive programming


#### Global optimization of nonconvex problems
- Applications
- Convex relaxations, McCormick Inequality
- Spatial branch and bound
- Mixed-integer nonlinear programming

#### Decomposition algorithms
- Benders decomposition, stochastic programming
- Dantzig Wolfe decomposition, column generation, vehicle routing problems
- Lagrangian decomposition
- ADMM 

#### Advanced topics on computation
- Numerical linear algebra
- Advanced solver callbacks
- Parallel computing
- GPU computing

### Recommended Textbooks:
This class will not exactly follow any textbook. But we may cover some of the content in the following textbooks.
1. Grossmann, I. E. (2021). Advanced optimization for process systems engineering. Cambridge University Press.
2. Wolsey, L. A. (2020). Integer programming. John Wiley & Sons.
3. Bertsimas, D., & Tsitsiklis, J. N. (1997). Introduction to linear optimization (Vol. 6, pp. 479-530). Belmont, MA: Athena scientific.
4. Ben-Tal, A., & Nemirovski, A. (2001). Lectures on modern convex optimization: analysis, algorithms, and engineering applications. Society for industrial and applied mathematics.
5. Conforti, M., Cornuéjols, G., Zambelli, G (2014). Integer programming. Graduate Texts in Mathematics
6. Boyd, S. P., & Vandenberghe, L. (2004). Convex optimization. Cambridge university press.

### Software
We will use the following software 
- [Pyomo](https://www.pyomo.org/) is a collection of Python software packages for formulating optimization models. Tutorial: [ND Pyomo Cookbook](https://jckantor.github.io/ND-Pyomo-Cookbook/README.html)
- [Gurobi](https://www.gurobi.com/documentation/) and [Cplex](https://www.ibm.com/products/ilog-cplex-optimization-studio) are both high-performance mathematical programming solver for linear programming, mixed integer programming, and quadratic programming.
- [Mosek](https://www.mosek.com/) is a software package for the solution of linear, mixed-integer linear, quadratic, mixed-integer quadratic, quadratically constraint, conic and convex nonlinear mathematical optimization problems.
- [Pytorch](https://pytorch.org/) PyTorch is a machine learning framework based on the Torch library, used for applications such as computer vision and natural language processing, originally developed by Meta AI and now part of the Linux Foundation umbrella.

### Prerequisite

Some familiarity with linear algebra, calculus, and programming in python is required.
- YouTube videos review of linear algebra and calculus by [3Blue1Brown](https://www.youtube.com/@3blue1brown/courses)
- [Linear algebra review](https://www.cs.cmu.edu/~zkolter/course/linalg/index.html)  videos by Zico Kolter
- General mathematical review: Appendix A of  [Boyd and Vandenberghe (2004)](https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf)

### Related courses
- [Convex optimization](https://www.stat.cmu.edu/~ryantibs/convexopt/) by Ryan Tibshirani 
- [Convex analysis](https://ocw.mit.edu/courses/6-253-convex-analysis-and-optimization-spring-2012/pages/syllabus/) by Dimitri Bertsekas
- [Linear programming](https://www2.isye.gatech.edu/~sdey30/CourseLinearProgramming.html) by Santanu Dey
- [Integer programming](https://coral.ise.lehigh.edu/~ted/teaching/ie418/) by Ted Ralphs
- [Linear and convex optimization classes](https://www2.isye.gatech.edu/~nemirovs/) by Arkadi Nemirovski

**Last updated:** October 12, 2023
<br /><br /><br /><br /><br /><br /><br /><br />
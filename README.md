# Optimization methods course
Lectures for Optimization methods course @ Yandex School of Data Analysis, Fall 2026.

| Lecture | Topics | Notebook |
|---|---|---|
| 1. Introduction and why this course exists | Notation (vectors, inner products, gradients, norms, duals, the problem template); $\ell_1$ magic and when basis pursuit fails (RIP, NSP); Goemans–Williamson MaxCut; how iterative methods and convergence bounds work; Nesterov vs first-order lower bounds (and Adam) | [lecture1.ipynb](lecture1.ipynb) |
| 2. Convex set, functions and how to construct them | Convex sets; operations that preserve set convexity; convex functions, strict and strong convexity; convexity criteria; how to build convex functions; disciplined convex programming as a grammar; ellipsoidal robust constraints and nuclear-norm matrix completion | [lecture2.ipynb](lecture2.ipynb) |
| 3. Optimality conditions and KKT | Variational inequality; equality constraints via curves on the feasible manifold; KKT and the sign of inequality multipliers; sufficiency and Slater's condition; halfspace and simplex projections | [lecture3.ipynb](lecture3.ipynb) |
| 4. Duality and applications | Dual function and dual problems. Strong and weak duality, duality gap as an optimality certificate. Conic problems and conic duality. Dual cones and notion of barriers for them. DCP and reduction of the convex problem to the conic form. Example of NP-hard convex optimization problem. | [lecture4.ipynb](lecture4.ipynb) |
| 5. Modeling with CVXPy | Expression tree, DCP check, canonicalization to a cone program, primal-dual recovery. Problems accepted as written; equivalent rewrites (the right atom, a geometric program); the MaxCut spectrahedron as a relaxation of a refused constraint; problems with no rewrite. Total-variation denoising, the graphical lasso, and pre-cooling an office ahead of an electricity price spike. | [lecture5.ipynb](lecture5.ipynb) |
| 6. Introduction to numerical methods | Oracles, residuals, and rates. Gradient descent on $L$-smooth, $L$-smooth convex, and $L$-smooth strongly convex functions; what each bound guarantees and where it stops. Constant steps, exact line search, Armijo, diminishing steps, Polyak. A quadratic, logistic regression, and a nonconvex function with several minima. | [lecture6.ipynb](lecture6.ipynb) |
| 7. Accelerated first-order methods | Lower bounds and the resisting chain in the smooth convex class. Conjugate gradients on a quadratic, finite termination, and nonlinear CG with a Wolfe line search. Heavy ball: the quadratic rate, the transient, and a smooth strongly convex cycle. Nesterov acceleration, the $1/k^2$ potential, and the ripple a restart removes. | [lecture7.ipynb](lecture7.ipynb) |
| 8. Newton and quasi-Newton methods | Newton from the quadratic model, the root-finding reading, and the basins of $z^3-1$. Quadratic convergence, and why it is local. Damped Newton, and an indefinite Hessian. Inexact Newton: CG, forcing terms, and Hessian-vector products. The secant equation, BFGS, and Barzilai–Borwein. L-BFGS and the two-loop product. | [lecture8.ipynb](lecture8.ipynb) |
| 9. Proximal gradient methods | Proximal map, implicit Euler, and Levenberg–Marquardt as a proximal step on the Gauss–Newton model. Trust region, dogleg, and the augmented Jacobian. Closed-form proximal maps. Composite proximal gradient, the $1/k$ gap and the linear rate, FISTA. Sparse logistic regression and nuclear-norm matrix completion. | [lecture9.ipynb](lecture9.ipynb) |
| 10. Penalty methods and ADMM | | |
| 11. Interior point methods | | |
| 12. Stochastic first-order methods | | |
| 13. Introduction to federated learning | | |
| 14. TBD | | |
| 15. Project presentations | | |


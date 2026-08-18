---
title: "Fast numerical solvers for parameter identification problems in mathematical biology"
collection: publications
permalink: /publication/paper1
excerpt: PDE-constrained optimization for parameter identification in mathematicall biology
date: 2026-03-16
venue: 'Journal of Scientific Computing'
paperurl: 'https://doi.org/10.1007/s10915-025-03170-y'
citation: 'KB, John W. Pearson, Mariya Ptashnyk (2026)'
---
In this paper, we consider effective discretization strategies and iterative solvers for nonlinear PDE-constrained optimization models for pattern evolution within biological processes. Upon a Sequential Quadratic Programming linearization of the optimization problem, we devise appropriate time-stepping schemes and discrete approximations of the cost functionals such that the discretization and optimization operations are commutative, a highly desirable property of a discretization of such problems. We formulate the large-scale, coupled linear systems in such a way that efficient preconditioned iterative methods can be applied within a Krylov subspace solver. Numerical experiments demonstrate the viability and efficiency of our approach.
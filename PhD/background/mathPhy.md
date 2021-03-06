% Notes in Math and Physics
% Jinming LYU
% 22 mars 2016

# Harmonic function #
 A harmonic function is a twice continous differntiable function $f:U\rightarrow \mathbf{R}$ (where $U$ 
 is an open subset of $\mathbf{R}^n$) which satfies Laplace's equation.
 $\nabla ^2 f = 0$

# Stokeslets #
 [Cortez 2005 PoF]The formulation of the boundary element method for Stokes flow is based on the numerical evaluation of 
 distributions of Stokeslets (the velocity field induced by a point force in an unbounded region) along surfaces.

 The *method of regularized Stokeslets* is based on the computation of the velocity field due to a distribution 
 of modified expressions for the Stokeslet in which the singularity has been removed. The
 regularized expression is derived as the exact solution to the Stokes equations consistent with forces given by regularized
 delta functions.

 The force of an organism on the fluid is a delta-function layer of force supported only by the region of fluid that 
 coincides with material points along the surface of the organism; away from these points, this force is zero.

 the flow generated by regularized forces is given by an integral with nonsingular kernel. One advantage of this
 formulation is that it leads to stable numerical computations since there is no need to evaluate nearly-singular integrals of
 the type that arise in the presence of a singular (but integrabl) kernel. Another advantage is that the solutions are well defined
 everywhere even when the forces are not applied on a closed surface but along curves or even discrete points.
 *Those cases cannot be approached with the traditional boundary-integral formulation, since they lead to singular nonintegrable kernels.*

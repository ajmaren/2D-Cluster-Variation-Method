# 2D-Cluster-Variation-Method
Code, documentation, V&amp;V, and experimental results for the foundational 2-D Cluster Variation Method network

The Cluster Variation Method (CVM) provides a free energy formalism that includes contributions not only from node activations (x1 & x2, for a bistate system), but also in terms of configuration variable contributions: the nearest-neighbors (y(i)), next-nearest-neighbors (w(i)), and triplets (z(i)). There is an analytic solution when x1 = x2 = 0.5. For non-equiprobable (x1, x2) values, the free energy minima must be computed via simulation. The free energy and other thermodynamic variables can be computed for various h-values, where h is an interaction enthalpy parameter. (When h = 1, epsilon-1, the actual interaction energy coefficient, = 0.) There is also an influence of a second enthalpy coefficient, epsilon-0, on the total fraction of active nodes (x1); this can not be directly computed; however, it influences x1. 

The V&V for this code establishes that the values calculated using probabilistic initial distributions, and then cascading to free energy minima, are correct. It also validates that the counting of the different configuration variables is correct. 

The V&V summary results will be published separately on arXiv. 

For more information, contact Dr. A.J. Maren at: alianna@aliannajmaren.com.

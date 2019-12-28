# corr_ot_geom

### optimal_transport_corr
Study Frechet barycenter w.r.t Wasserstein distance for correlation matrix metric using corr_lib module:
* compute the metric induced on the covariance manifold by the 2-Wasserstein distance on Gaussian measures,
* compute geodesic on the covariance manifold using weighted Frechet barycenter, and show that it is not a geodesic on the correlation manifold (matrices on the geodesic path between two correlation matrices within the covariance manifold need not be correlation matrices themselves).
* compute the metric induced on empirical correlations by a Wasserstein distance on the discrete measures, by solving Frechet barycenter problem as a linear program using CVXPY.

Examples on synthetic, random matrices and historical SPX correlations.

### corr_lib
Utility lib for correlation matrix manipulation and optimal transport metric.

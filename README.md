# PC Analysis Results
These files provide the results of the principal component analysis conducted on the 8-dimensional space of resolved ISM properties sampled at a scale of 1kpc from the TNG50 volume of the IllustrisTNG suite for various samples of galaxies.

Each file contains the results for galaxies drawn from a particular redshift and decade in stellar mass, as specified in the file name (for e.g., "..z0_m1e9-10.."). The fields present therein are as follows:

'/loading_matrix' : Principal component loading factors, returned as a N-by-8 matrix, where each column contains loadings for one principal component. The values                       are corrected for the weighted-variance of each of the original parameters. All columns are orthogonal to each other.

'/explained_variance' : Percentage of the total variance explained by the eight principal components.

'/PCn_bin_centres' : Central values of the binned PCn axis (n = 0,1,2) at which the trivariate distribution of principal component scores (see next field) is   	                      provided.

'PC0-2_distribution' : Trivariate probability distribution generated from the first three principal component scores. This distribution is not weighted by any                            parameter.

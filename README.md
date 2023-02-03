# Physics-188
Homework 3:
Linear Algebra - Gaussian Elimination, SVD, Polynomial Regression, PCA, KNN, and Data Modeling

Parameter optimization of chi^2. A, b matrix to create alpha = A.A^t, beta = A^t*b, and solve alpha*coeffs=beta for coeffs using gaussian elimination pivot and LU decomposition.

Decomposing design matrix A using single value decomposition.
Polynomial_fit to fit a polynomial of n degrees to the data and then use these polynomial for fitting linear regression models.

Principal component Analysis on quasar spectra data. take eigenvalues that describe the variance of the data the best. reduces dataset into several eigenvectors and eigenvalues. Take mean centered data from the main data table and form a covarinace data table from it. Reconstruct values of spectra from first 6 principal components. Use SVD to find eigenvalues. 

Using PCA(finding minimum num variables to keep max vvariance using correlation between dimensions) for MINST data set. Using KNN you can guess the number based on the principal component breakdown of first two components.

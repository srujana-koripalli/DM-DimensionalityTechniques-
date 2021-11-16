# DM-Assignment-2 DM-DimensionalityTechniques 

# PCA

- Principal component analysis (PCA) can be used in the dimensionality reduction task—reducing the number of features of a dataset while maintaining the essential relationships between the points. While PCA is flexible, fast, and easily interpretable, it does not perform so well when there are nonlinear relationships within the data; 

- To address this deficiency, we can turn to a class of methods known as manifold learning—a class of unsupervised estimators that seeks to describe datasets as low-dimensional manifolds embedded in high-dimensional spaces. 

# tSNE
t-SNE is the most popular visualization method for single cell RNA-sequencing data. The method was first introduced by Laurens van der Maaten in 2008 in the aptly named article "Visualizing High-Dimensional Data Using t-SNE". The goal of t-SNE is to produce a two or three dimensional embedding of a dataset that exists in many dimensions such that the embedding can be used for visualization.

# UMAP
Even though UMAP is not a part of scikit-learn, the syntax for UMAP is identical to t-SNE: umap.UMAP().fit_transform. UMAP is relatively fast, so you won't need to use the subsampled data.

# ISOMAP
Isomap is a nonlinear dimensionality reduction method. It is one of several widely used low-dimensional embedding methods.

# SVD
The singular value decomposition (SVD) provides another way to factorize a matrix, into singular vectors and singular values. ... The SVD is used widely both in the calculation of other matrix operations, such as matrix inverse, but also as a data reduction method in machine learning


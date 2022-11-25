# This is nviz.

Visualizations of factorizations of numbers, inspired by [this post](https://johnhw.github.io/umap_primes/index.md.html).

I wasn't able to run up to 1,000,000 but I was able to get up to 100,000, and
plotted results using [UMAP](https://umap-learn.readthedocs.io/en/latest/index.html), [T-SNE](https://scikit-learn.org/stable/modules/generated/sklearn.manifold.TSNE.html) and [PCA](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.TruncatedSVD.html#sklearn.decomposition.TruncatedSVD) (actually TruncatedSVD, because sklearn's PCA implementation does not work for sparse matrices).
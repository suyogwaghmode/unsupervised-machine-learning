# Unsupervised Learning Explorations

This project is a small exploration notebook that demonstrates unsupervised learning techniques using the Iris dataset (from scikit-learn) and synthetic datasets.

It contains:
- PCA: dimensionality reduction and explained variance
- k-means: elbow method and cluster analysis
- DBSCAN: density-based clustering and noise detection
- t-SNE: nonlinear dimensionality reduction for visualization
- UMAP: modern manifold learning for visualization

Notes
- The notebook scales features with `StandardScaler` before applying PCA and clustering.
- Tweak `perplexity` (t-SNE) and `n_neighbors` / `min_dist` (UMAP) to explore different visualizations.
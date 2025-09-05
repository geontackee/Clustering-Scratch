# Clustering Algorithms from Scratch

This repository demonstrates the implementation of **clustering algorithms** (K-means and K-means++) from scratch in Python.  
It covers dataset generation, clustering implementation, model fitting, and visualization of results, providing a hands-on understanding of unsupervised learning.

---

## 📌 Features
- Synthetic dataset generation with `sklearn.datasets.make_blobs`
- Implementation of:
  - **K-means clustering**
  - **K-means++ initialization**
- Cluster assignment using distance minimization
- Iterative centroid updates until convergence
- Visualizations of clusters in 2D and 3D
- Comparison between K-means and K-means++ performance
- Bonus: image clustering demonstrations with **PIL** and **OpenCV**
- Exploration of hierarchical clustering (via `scipy.cluster.hierarchy`)


## ⚙️ Requirements
Make sure you have the following dependencies installed:

```bash
pip install numpy pandas matplotlib scikit-learn pillow opencv-python scipy
```
Have Python 3.8+

## How to Run
1. Clone this repository
2. Open the notebook
3. Run all cells

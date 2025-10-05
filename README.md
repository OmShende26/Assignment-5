### Student: Om Vijay Shende
### Roll No: CE22B083

Contains
- Assignment 5.ipynb: contains code of the assignment
- README.md - Description of the repository

# DA5401-A5-Manifold-Visualization

## Overview

This document is an assignment outline for **DA5401 A5: Visualizing Data Veracity Challenges in Multi-Label Classification**. Its central focus is to use advanced non-linear dimensionality reduction techniques—**t-SNE** and **Isomap**—to visually explore and identify common issues in real-world, multi-label biological datasets, using the **Yeast Dataset** as an example[1].

## Objectives

- **Understand Data Veracity Issues:** Identify noisy/ambiguous labels, outliers, and hard-to-learn samples in multi-label classification settings.
- **Practically Implement Dimensionality Reduction:** Apply and compare t-SNE and Isomap on standardized gene expression data.
- **Develop Insights through Visualization:** Use scatter plots to highlight regions that pose classification challenges due to data quality issues.
- **Relate Visualization to Model Performance:** Discuss how the observed manifold structure and data issues affect the feasibility and accuracy of classification tasks.

## Assignment Flow

- **Data Preparation:** Load and standardize the Yeast Dataset, focusing on both feature (gene expression) and target (functional category) matrices.
- **Simplified Labeling:** Select the two most frequent single-label classes and the most frequent multi-label combination for clearer visualization.
- **Dimensionality Reduction:** Implement both t-SNE and Isomap, tuning hyperparameters (like perplexity for t-SNE) for effective visualization.
- **Visual Analysis:** Generate 2D scatter plots and color-code points by category. Visually identify regions with ambiguous labels, outliers, and mixed categories.
- **Manifold Learning & Data Structure:** Discuss the differences between t-SNE (local structure) and Isomap (global structure), and how the data manifold’s complexity relates to classification difficulty.


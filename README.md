# karate-club-graph-mining

# Graph Mining in Machine Learning

This repository contains the implementation of a **Graph Mining project** based on the famous **Zachary’s Karate Club dataset**.  
The project applies fundamental graph mining techniques, node embeddings, clustering, and link prediction to analyze and visualize the dataset.

---

## 📊 Dataset
- **Zachary’s Karate Club**: A social network of friendships between 34 members of a karate club, often used in graph mining and network analysis tasks.

---

## 🚀 Project Tasks

### 1. Graph Exploration
- Construct the graph using **NetworkX**.
- Visualize the graph with nodes colored by their real club affiliation.
- Compute graph properties such as:
  - Number of nodes and edges
  - Average degree
  - Clustering coefficient

### 2. Node Embedding & Clustering
- Compute node embeddings using **Node2Vec**.
- Apply **K-Means** clustering on embeddings.
- Reduce dimensions using **t-SNE** for visualization.
- Evaluate clustering purity against ground-truth labels.

### 3. Link Prediction
- Randomly remove **20% of edges** as the test set.
- Predict missing edges using **Adamic-Adar similarity**.
- Visualize:
  - Correctly predicted edges (green)
  - Incorrectly predicted edges (red)
  - Training edges (gray)
- Evaluate performance using a **Precision-Recall curve**.

---

## 🛠️ Dependencies
Make sure to install the following Python packages before running the project:

```bash
pip install networkx numpy matplotlib scikit-learn node2vec

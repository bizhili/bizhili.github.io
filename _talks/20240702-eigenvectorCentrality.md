---
title: "Eigenvector centrality"
collection: talks
type: "Talk"
permalink: /talks/20240702-eigenvectorCentrality
venue: "Math application on engineering"
date: 2024-7-2
location: "Earth"
---

Peoblem definition: 
In a network $G(n, m)$, the importance of a node equals to the portion sum of importance of its neighbors. How to calculate the importance?


Solve:

We use function $Cen()$ denote the importance of a node.
Form the description we have:

$$Cen(node_i)=\frac{1}{\lambda}\sum_{j\in neighbors(node_i)} Cen(node_j)$$

We let matrix $A$ as its adjacency matrix, and we can write above in a matrix form:

$$\lambda \cdot Cen(nodes)=A \cdot Cen(nodes)$$

We find $Cen(nodes)$ is the eigenvector corresponding to the eigenvalue $\lambda$.

The choosing of $\lambda$ should satisfy that: $Cen(nodes)$ are positive.


Next: Perron–Frobenius theorem for choosing $\lambda$.


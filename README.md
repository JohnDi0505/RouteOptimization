# Route Planning Optimization
Mobile terrestrial (laser scan based) surveying & delivery tasks are typical TSP (Travelling Salesman Problems) which are costly to solve due to their high computational complexity.

A well-known algorithms, the Hopfield Neural Network, is an unsupervised approach to solve TSP. This algorithm works but also requires extra efforts to tune all four parameters in its main equation. In contrast, the Christofides Algorithm also provides an efficient network based solution for TSP but is more understandable in terms of its geometrical meanings.

This project focuses on implementing Python based network analysis (networkx) and the Christofides Algorithm to optimize route planning for terrestrial mobile surveying tasks at county scale (Middlesex).

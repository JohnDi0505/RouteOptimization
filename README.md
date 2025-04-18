# Route Planning Optimization
Mobile terrestrial (laser scan based) surveying & delivery tasks are typical TSP (Travelling Salesman Problems) which are costly to solve due to their high computational complexity.<br>

A well-known algorithms, the Hopfield Neural Network, is an unsupervised approach to solve TSP. This algorithm works but also requires extra efforts to tune all four parameters in its main equation. In contrast, the Christofides Algorithm also provides an efficient network based solution for TSP but is more understandable in terms of its geometrical meanings.<br>

This project focuses on implementing Python based network analysis (networkx) and the Christofides Algorithm to optimize route planning for terrestrial mobile surveying tasks at county scale (Middlesex).<br>

### Problem Statement
The objective of the Traveling Saleman Problem (TSP) is to figure out a most efficient path (shortest total distance) to visit all target locations once given the distances between each pair of locations. Similar to TSP, in ground based laser mapping or delivery tasks the location-to-visit is already known and the operators may want know how to plan their routes to achieve highest efficiency. However, what's different from a TSP is that TSP describes a very theoretical situation (each target only allows to visit onece) while it doesn't matter if we visit a place twice or even more times due to local traffic conditions in a real-life operation. Therefore, to solve for the real-life route optimization for ground based mobile mapping survey or delivery tasks, we don't need our algorithm to have as strict constraint as to solve a TSP. Additionally, with the recent advancements in GIS (Geographic Information System) a wide variety of road or traffic information (e.g. road congestion, traffic light, street directionality) can be obtained even in real-time. All this information can be used for more informative variable input to improve the accuracy of the route planning and such procedure requires a lot of geospatial data processing techniques.

### Framework

![WeChat Screenshot_20250406203300](https://github.com/user-attachments/assets/66697cbf-733d-460f-b823-9c8816214d23)

### Future Work


### Reference

1. Fleischer, R., 2003. IT Fundamentals CSIT570. World Wide Web: http://www.cs.ust.hk/˜rudolf/Courses/Msc03/Script/week2.pdf.

2. Sharma, O., et al. (2005). "Traveling salesperson approximation algorithm for real road networks." ISPRS WG II/1 2(7).

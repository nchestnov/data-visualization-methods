# Data Visualization Methods. Course Homework

This repository contains my homework solutions for MIPT course "Data Visualization Methods" by [prof. Alex Dainiak](https://github.com/dainiak).

## Tasks

1. **Tree Visualization**
   
   **Input:** a tree as a directed graph  (all edges directed from root to leaves)

   **ToDo:** implement HV-approach or Layered-Tree-Draw algorithm.

2. **Acyclic Graph Visualization**
    
    **Input:** acyclic directed graph and maximum layer width W (optional)

    **ToDo:**

    - if W is present, implement the layer distribution with Graham-Koffman algorithm
    - if W is absent, implement an algorithm for minimizing the number of dummy-vertices
    
    After stacking in layers, add the dummy-vertices and minimize (using heuristics) the number of edge intersections between adjacent layers.

3. **Label Placement**

    **Input:** a set of pair of integer coordinates of points in range of 0 and 500, the size of label (width and height) for each point and a subset of possible label locations

    **ToDo:**

    Create a picture with points and non-overlapping labels (in particular, not going beyond the 500 × 500 canvas) or an indication that such an arrangement is impossible. 

    There are two variations of this task:
    1. no more than two placement options for each label - implement your own 2-SAT solver
    2. no limits for label placement options - use external SAT-solver

4. **Multidimensional Data Visualization**

    **Input:** any dataset

    **ToDo:**   
    Implement any of the following algorithms:
    - LLE
    - IsoMap
    - t-SNE
    - Hessian LLE (optional)
    - UMAP (optional)

5. **Free Choice**
   
   I have chosen to implement "ForceAtlas 2" graph layout algorithm 
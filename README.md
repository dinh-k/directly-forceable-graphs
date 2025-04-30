# An Algorithm for Directly Forceable Graphs
This repository supports the ongoing research "Directly Forceable Graphs". The algorithm and data in this repository aim to classify graphs by their directly forceable properties, provide evidence for theorems, and support conjectures stated in the manuscript.

*Tools: [Minimum Rank Sage Library](https://github.com/jasongrout/minimum_rank), SageMath 10.6 on [CoCalc](https://cocalc.com/), Python via Sage’s Jupyter Notebooks.*
## Contents
- [brute-force-algo.ipynb](brute-force-algo.ipynb): This notebook introduces a brute-force algorithm in SageMath to determine whether a graph is directly forceable.
- [database/](database): A collection of CSV files classifying small graphs by their direct forceability, organized by graph order, zero forcing number, and regularity. These files are the output of the brute-force classification. Each CSV contains rows representing individual graphs in graph6 format.

  `n_k_df.csv`: Graphs of order n with zero forcing number Z(G) = n - k that are directly forceable.

  `n_k_not_df.csv`: Same as above, but graphs that are not directly forceable.

  `regular_n.csv`: All regular graphs with n vertices.

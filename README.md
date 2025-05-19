# Crash course on *graphs*

Jupyter notebook version of the awesome [graph tutorial](https://iaee.substack.com/p/graphs-intuitively-and-exhaustively) from the [intuitively and exhaustively explained blog](https://iaee.substack.com). Fixed a couple of typos in the text and code.


## Notebooks TBD

[Notebook 1](1-Defining_and_plotting.ipynb): Defining and plotting a graph.

[Notebook 2](2-Types.ipynb): Types of graphs. Various ways of defining one.

[Nb 3](3-Basic_manipulation—key_metrics.ipynb): Subgraphs. Merging graphs. Islands. | Key metrics: Degree, in-degree, out-degree,

<br>• nx.shortest_path + length<br>• Eccentricity & Radius (longest-shortest path)

[Nb 5](5-Centrality.ipynb):	• Degree, Betweenness, Closeness, Eigenvector centrality <br>• Side-by-side plots with variable node sizes

[Nb 6](6-Graph-Structure-Motifs.ipynb):	• Cliques (find_cliques)<br>• k_core and connected-component extraction<br>• Bridges (nx.bridges) & Local bridges<br>• Strongly / Weakly connected components in directed graphs

[Nb 7](7-Paths_Weights.ipynb):	• Eulerian path (has_eulerian_path, eulerian_path)<br>• Weighted graphs: adding weights, drawing labels<br>• Weighted shortest vs longest path demo

[Nb 8](8-Graph-Coloring.ipynb):	• Four-color story<br>• nx.coloring.greedy_color examples<br>• Chromatic number extraction

[Nb 9](9-Real-World-Applications.ipynb):	1. Traveling-Salesman (approximation.traveling_salesman_problem)<br>2. Exam scheduling (graph coloring revisited)<br>3. PageRank (nx.pagerank)<br>4. Influence maximization using centrality (Les Mis example)
# Graph-Coarsening-For-Graph-Neural-Networks-Using-Python
 Designed and implemented a graph coarsening algorithm to enhance the scalability and performance of Graph Neural Network (GNN) training on large-scale
 graphs. The approach preserves spectral properties and node feature integrity by computing spectral distances and merging low-distance node pairs using
 partitioning. Converted input graphs into weighted forms based on neighborhood feature similarity and adjacency structure. Integrated the coarsened graphs
 into GraphSAGE-based GNN models using PyTorch and DGL, achieving over 30% reduction in memory usage and significantly faster training times across
 benchmark datasets (Cora, Citeseer, Actor, Chameleon) with minimal loss in accuracy. Demonstrated potential for real-time, resource-efficient GNN
 deployment in applications like fraud detection, social networks, and knowledge graphs.

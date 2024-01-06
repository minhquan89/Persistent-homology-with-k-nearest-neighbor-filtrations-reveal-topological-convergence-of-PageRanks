# Persistent homology with k-nearest neighbor filtration reveals topological convergence of PageRanks
We provide the code for the paper Persistent-homology-with-k-nearest-neighbor-filtration-reveals-topological-convergence-of-PageRanks.

The following Jupyter notebooks contain:

1. Stability for Sec 2.ipynb--the codes are used to illustrate the the stability theorem for persistent diagram.

2. Dolphin network.ipynb--the codes describe our experiment woth dolphin data. We also compare the convergence with respect to the geometric pointview and topological convergence. 

3. Random_Graph_Exps--the codes are used to depict our method with some typical random graphs: ER network, scale-free network and small random world network. 

4. Teleportation_Effects_Exp.ipynb--the codes are the exploration of the affect of teleportation parameter to the convergence.





The following python files included:
EVC_util.py--codes that utilize Gudhi to implement edge-valued clique (EVC) filtrations of functions defined on network edges 

util.py--codes used to implement experiments and plot results 

NNO_util_minh.py defines simplex tree, and creates persistent diagram as well as three types of symmetrization of our filtration.


# Optimal-Location-Placement

Included in this repository is a project in the form of an IPython notebook (.ipynb) and a .PDF of the notebook. The code uses the Julia language and requires installation of JuMP (Julia Mathematical Programming) and Gurobi packages.

The general idea of this project is to find an optimal placement of objects under various costs and restrictions. For example, one could use this algorithm to find the optimal placements of hospitals, fire stations, and police stations in a given city.

This project will be specifically dealing with finding an optimal configuration of a network of routers with varying ranges and costs. The network of routers are all based around a central backbone source chosen by the user. The algorithm is a binary integer linear program (ILP).

Inputs:
  - A maximum number of routers and their corresponding ranges and costs.
  - A location grid of 1s and 0s where the 1s represent points that must be covered by a router.
  - A location for the backbone of the network.
  - A cost associated with each unit length of fiber-optic cable.

Output:
  - A location grid with cost-optimal configuration of the routers.

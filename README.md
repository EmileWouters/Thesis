
This repository contains the code and supporting excel file developed for my MSc thesis at Delft University of Technology. The project investigates the potential for shifting freight transport from road to rail within the Dutch railway network using graph theory and network optimisation techniques. The code is used to construct the railway network as a graph and perform optimisation algorithms. This repository consists of three files.

- **Algorithms.ipynb**: This is the main file and contains the code for the construction of the graph and the functions for running different optimisation algorithms
- **Modal_Shift.ipynb**: This file is used to calculate the modal shift potential. To run this code the data from Speth et al. (2022) are needed, but these files were to big for this repository. They can be found at: https://data.mendeley.com/datasets/py2zkrb65h/1 
- **graph_final.xlsx**: This is the supporting excel file containing all node and edge information of the graph. It consist of four sheets:
  -**Nodes**: This sheet contains all node information, including all demand scenarios
  -**Edges**: This sheet contains all edge information
  -**Edges_night**: This sheet contains all information to calculate night time capacity. The collumn max_cap_n contains the night capacity, this value is calculated in the Algorithms.ipynb file
  -**Edges_night**: This sheet is used to calculate all the demand scenarios




  ```

                                            # TSP_A*_algorithm

Problem : 
  In the traveling salesman Problem, a salesman must visits n cities. We can say that salesman wishes to make a tour or Hamiltonian cycle,
  visiting each city exactly once and finishing at the city he starts from. There is a non-negative cost c (i, j) to travel from the 
  city i to city j. The goal is to find a tour of minimum cost. We assume that every two cities are connected. Such problems are called
  Traveling-salesman problem (TSP).
  
  TSP returns a tour whose cost is never more than twice thecost of an optimal tour. The idea is to use Minimum Spanning Tree (MST)


	Steps: 

	  1. Compute a MST T of G;  
    2. Select any vertex r is the root of the tree;  
    3. Let L be the list of vertices visited in a preorder tree walk of T;  
    4. Return the Hamiltonian cycle H that visits the vertices in the order L;  

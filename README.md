# GraphColoringGA
Graph Coloring optimization problem using Genetic Algorithm

 <img width="508" alt="Screen Shot 2022-04-02 at 14 00 31" src="https://user-images.githubusercontent.com/36630821/161386643-8a82a17d-9c71-4bd2-b940-0e6dfd2487ab.png">

## Introduction 
The graph coloring problem, a classical problem in graph theory. In its simplest form, the graph coloring problem consists in assigning a color to each of its vertices so that two vertices connected by an edge are of different color. We often seek to use the minimum number of colors, called chromatic number or we set a fixed number of colors and we seek the best coloring for a graph. The field of applications of graph coloring covers in particular the problem of frequency allocation in telecommunications, the design of electronic chips or the allocation of registers in compilation, Timetabling.

## Genetic algorithm 
The goal of the algorithm is to improve the fitness of the population by mating its fittest individuals to produce superior offspring that offer a better solution to the problem. This process continues until a termination condition is reached, i.e. the total number of generations has been run or some other parameter such as fitness improvement over a certain number of generations or a solution to the problem has been found.

This code is based on the Genetic Algorithm Applied to the Graph Coloring Problem paper by Musa M. Hindi and Roman V. Yampolskiy.
you can find this paper for more details in this link : http://ceur-ws.org/Vol-841/submission_10.pdf

## Approach 
Representation of the graph:
Each graph is represented by a dictionary where the keys are the nodes of the graph and the values contain a list of adjacents of the vertex.

Representation of coloring:
The coloring is a list where the indices represent the nodes of the graph and the values represent the colors of each node at the index.

Input :
Text file as a binding between nodes separated by spaces and EOLs.

Output :
Graphical display of coloring by the NetworkX library and display of iterations and the optimal solution on the console.

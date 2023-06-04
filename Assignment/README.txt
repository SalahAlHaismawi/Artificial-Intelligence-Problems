Overview
This Jupyter Notebook provides a comparison of two algorithms: Breadth-First Search (BFS) and A* (A-star). The goal of the analysis is to evaluate the performance, advantages, and limitations of these algorithms in solving a maze navigation problem.


Installation
To run this Jupyter Notebook, you need to have Python installed on your system along with the following dependencies:

Jupyter Notebook
pymaze Library
PriorityQueue Library
matplotlib.pyplot library
pandas library
datetime library 
timeit library

To install the required dependencies for running this Jupyter Notebook, you can use the following pip commands:
$ pip install jupyter
$ pip install pymaze
$ pip install PriorityQueue
$ pip install matplotlib
$ pip install pandas
$ pip install datetime
$ pip install timeit


Usage
Download the file in your local repository.
Launch Jupyter Notebook.
Open the notebook file Assignment.ipynb.
Run each cell in the notebook sequentially to execute the code and generate the results.


Algorithms

Breadth-First Search (BFS)
Breadth-First Search is an algorithm used for traversing or searching tree or graph data structures. In the context of maze navigation, BFS explores all possible paths in a breadth-first manner, visiting all neighboring cells before moving to the next level of neighbors. It ensures the shortest path from the start to the goal.

A* (A-star)
A* is an informed search algorithm that combines elements of Dijkstra's algorithm and Best-First Search. It uses a heuristic function to estimate the cost of reaching the goal from a particular cell. In the context of maze navigation, A* evaluates the potential paths based on both the cost of reaching a cell and the estimated cost of reaching the goal. It strikes a balance between optimality and efficiency.



Results
Based on the findings, A* algorithm generally outperforms BFS in terms of search time, taking between 0.001009s to 0.007217s, while BFS ranges from 0.001534s to 0.091769s. However, both BFS and A* algorithms yield similar path lengths for each maze, indicating their effectiveness in finding the shortest path from start to goal. In summary, the performance of both algorithms remains consistent across different maze sizes, with A* algorithm demonstrating slightly faster search times. These algorithms offer reliable solutions for maze navigation, with BFS ensuring the shortest path and A* striking a balance between optimality and efficiency.

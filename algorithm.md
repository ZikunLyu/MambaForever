# Algorithm
* [Backtracking](#Backtracking)
  * [m Coloring Problem](#m-Coloring-Problem)
 
### Backtracking
#### m Coloring Problem
Given an undirected graph and a number m, 
determine if the graph can be colored with at most m colors 
such that no two adjacent vertices of the graph are colored with the same color.

<details>
<summary>展开</summary>
The idea is to assign colors one by one to different vertices, 
starting from the vertex 0. Before assigning a color, 
we check for safety by considering already assigned colors to the adjacent vertices. 
If we find a color assignment which is safe, we mark the color assignment as part of solution. 
If we do not find a color due to clashes then we backtrack and return false.
</details>

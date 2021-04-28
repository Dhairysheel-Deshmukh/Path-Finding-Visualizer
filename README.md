# Path-Finding-Visualizer

Visualization of how program finds path between starting node and ending node by using  different color coding.
It is actually very short demo of how google maps work to find path between source and destination.

Algorithm Used :-  

Dijkstra’s Algorithm  –  Finding shortest path

A* Algorithm  –  Finding  quickest path (path need not to be shortest)


DIJKSTRA’S ALGORITHM


![ezgif-1-54c497cb7a46](https://user-images.githubusercontent.com/57897489/116426337-a72cf400-a860-11eb-8dbe-76067170a9eb.gif)



Dijkstra's algorithm to find the shortest path between a and b. It picks the unvisited vertex with the lowest distance, calculates the distance through it to each unvisited neighbor, and updates the neighbor's distance if smaller. Mark visited (set to red) when done with neighbors.




A* Search Algorithm


![ezgif-1-64c3c2a743f0](https://user-images.githubusercontent.com/57897489/116426545-d04d8480-a860-11eb-8b9b-11dd5b835e51.gif)



A* search algorithm is one of the best and popular technique used in path-finding and graph traversals.

Informally speaking, a* search algorithms, unlike other traversal techniques, it has “brains”.

In a*, we will use heuristics to overcome this problem. A heuristic is a function that informs the algorithm to enable a more directed search. 
In A*, heuristics are used to decide which node to consider at each step. Unlike dijkstra that selects nodes only by the total distance to the source node, A* combines the same criteria with a heuristic function.


OUTPUT

![22](https://user-images.githubusercontent.com/57897489/116426676-f2df9d80-a860-11eb-87c8-dd62011c0c88.JPG)

![23](https://user-images.githubusercontent.com/57897489/116426698-f83ce800-a860-11eb-8054-125e2ddfc2d4.JPG)



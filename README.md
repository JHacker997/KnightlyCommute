# Computer Graphics group project at the University of Central Florida. #<br />
Group : Shelby Basco, Julia Berger, John Hacker, Nestor Montejo

This project is a visual representation of Shortest path calculation using Dijkstra's algorithm.
The algorithm works on a map representing UCF and the nearby surrounding areas and calculates the shortest path from any given intersection on the map to another.

The weight of each edge is a scalar representing the distance it takes to get from one intersection to the next, and the algorithm is shown taking each road, and backtracking when its not on the shortest path.

The letter and number belowjavas any given node represent the index of the node (the letter) and the current shortest distance(the number) to get from the start node to that node. By default the distance is set to infinity.

To start the algorithm, you simply hit the start button after having selected the proper start and end nodes. You can choose any start node and end node on the map and the algorithm will properly find the shortest path between the two, and light that path once it terminates. We included a speed slider which accelerates the speed of the animation.

Upon completion of the algorithm, hitting clear will reset the colors of all the edges as well as ensure that the distance represented on each node have been reset to infinity, so that the next time start is pressed, values will have been properly restored to their defaults.

Also, our algorithm doesn't normally complete Dijkstra's on the whole graph, it only goes until its guaranteed that the path from start to end is the shortest possible, then terminates. If you wish to see the entire graph be solved, you can set the start and end nodes to be the same node, and the algorithm will solve the whole graph.

# A-star_path_finder
A Python project, primarily using pandas, to identify the shortest distance between two points on a 2D Grid

1. Initialise the start and end point of the graph alongside the obstacle placements

2. Turn the surrounding spaces into nodes and find the distance from the start node
   to each one plus the distance from the end node to each one called the A* distance.
3. Expand upon the node with the shortest A* distance alongside keeping track of where each node came from.

4. Go back to step 2 and repeat until the final node is reached.

5. Back trach through the path from start to begging to find the shortest path between the two points.

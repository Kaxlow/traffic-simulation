# traffic-simulation

In this project, traffic between selected locations in Los Angeles is simulated using a graph and Dijkstra's algorithm. Locations are represented as nodes in the graph. The travel routes between locations are represented as edges between the nodes and the travel times for the routes are represented as the edges' weights. Dijkstra's algorithm is used to determine the shortest path from one node to another.

The shortest travel route and travel time is calculated and compared across several scenarios. First, there is the base scenario where the edges' weights represent the travel time for smooth traffic. Second, there is a rush hour scenario where a random multiplier is applied to each edge's weight, reflecting a longer travel time between locations. Third, there is a scenario where random routes either experience a severe delay or a blockage. We apply this scenario to both the base and rush hour scenarios.

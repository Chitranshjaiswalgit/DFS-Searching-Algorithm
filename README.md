# DFS-Searching-Algorithm

The python code shows the usage of Depth-First Search (DFS), an algorithm which helps to find the solution for the problem of the Romania map traversal. It begins from the starting point, Arad, and systematically searches the available paths that may lead it to the desired goal, Bucharest. The algorithm uses optimization in the form of a priority function to guide for which nodes to expend the most efforts first. If backtracking is required, input does so and forms the graph as a set of cities and links.

The internal structure of the problem domain, including the graph representation, certain functions for the initial state, consequent test of achievement, and calculation of action costs is encapsulated by the RomaniaProblem class. The code has global_node_id that has a unique symbolic identifier to each node whenever it is explored.

During the figure of the processing, the algorithm continues to print data on processing node, state dictionary (D), and the priority queue (Q). The priority_function use the distance from the initial state to define priorities, having a heuristic that would result in the sooner reach for the goal city as the priority.

This broad implementation highlights the ability to navigate between graph traversal algorithms, maintain the priority queues, and create classes that can effectively meet the challenges of problem solving.

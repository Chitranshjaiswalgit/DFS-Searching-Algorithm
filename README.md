# DFS-Searching-Algorithm

The provided Python code demonstrates the application of the Depth-First Search (DFS) algorithm to solve the Romania map traversal problem. It starts from the initial state, "Arad," and systematically explores possible paths to reach the goal state, "Bucharest." The algorithm employs a priority queue, ensuring efficient node exploration based on a priority function. Backtracking is utilized when necessary, and the graph is represented as a collection of cities and connections.

The RomaniaProblem class encapsulates the specifics of the problem domain, including the graph structure and relevant functions such as initial_state, isGoal, children, and actionCost. The code maintains a global_node_id to assign unique identifiers to nodes during exploration.

Throughout the execution, the algorithm prints information about the processing of nodes, the state dictionary (D), and the priority queue (Q). The priority_function determines the priority of a state based on its distance from the initial state, with a heuristic to prioritize reaching the goal city sooner.

This comprehensive implementation showcases proficiency in graph traversal algorithms, priority queue management, and the design of problem-specific classes to tackle complex problem-solving scenarios.

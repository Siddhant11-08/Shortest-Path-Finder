Project Statement: BFS Shortest Path Finder

🎯 Problem Statement


The core problem addressed is the need for an efficient and visually understandable solution to find the shortest path between a designated starting point (S) and a goal state (G) within a two-dimensional, unweighted grid environment (a maze). While many search algorithms can find a path, the requirement is specifically for a method that guarantees optimality (the shortest path in terms of steps) and allows for step-by-step visualization of the search process for educational purposes.


🧭 Scope of the Project


The scope of this project is focused and highly defined:

1.	Environment: The application operates within a terminal environment using Python's curses library for rendering.
2.	Data Structure: The maze is a static, predefined 2D list (array) of characters.
3.	Algorithm: The exclusive pathfinding technique used is Breadth-First Search (BFS), which ensures the calculated path is the shortest possible route.
4.	Functionality: The primary function is to:
5.	Locate the 'S' and 'G' nodes.
6.	Execute the BFS search, visualizing the expansion of the search frontier.
7.	Upon reaching the goal, display the final shortest path.
8.	Exclusions: The project does not include:
9.	Support for weighted graphs (Dijkstra's or A* algorithms).
10.	Maze generation functionality (the maze is hardcoded).
11. Graphical User Interface (GUI) or web interface.
12. Multi-user functionality or persistent storage.


👥 Target Users
The primary target audience for this project is highly focused on learning and demonstration:
1.	Computer Science Students: Individuals studying graph theory, search algorithms, and data structures who need a clear, working example of BFS.
2.	Educators/Instructors: People who require a simple, visual tool to demonstrate the mechanics and optimality guarantee of the BFS algorithm in a controlled environment.
3.	Developers: Those looking for a concise, practical implementation of BFS in Python as a reference or learning resource.
 

✨ High-Level Features

1. Guarantees the path found between 'S' and 'G' is the minimum number of steps.
2. Provides a clear, non-distracting interface suitable for algorithm demonstration.
3. Allows users to observe the level-by-level exploration behavior inherent to BFS.
4. Ensures robust and safe traversal within the defined grid limits.
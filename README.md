# Pathfinding Visualizer https://ayushman-tarang.github.io/Algo_Pathfinder/

Welcome to Algo_Pathfinder Visualizer created by Ayushman Tarang.
I built this application because I was fascinated by pathfinding algorithms, and I wanted to visualize them in action. I hope that you enjoy playing around with this visualization tool just as much as I enjoyed building it. You can access it here (use Google Chrome!):


## Meet the Algorithms

This application supports the following algorithms: 

**Dijkstra's Algorithm** 

**Greedy Best-first Search** 

**Swarm Algorithm** 

**Convergent Swarm Algorithm**

**Bidirectional Swarm Algorithm** 

**Breath-first Search**

**Depth-first Search** 

## More about the Swarm Algorithm

The Swarm Algorithm is an algorithm that I - at least presumably so (I was unable to find anything close to it online) - co-developed with a good friend and colleague, Hussein Farah. The algorithm is essentially a mixture of Dijkstra's Algorithm and A* Search; more precisely, while it converges to the target node like A* , it still explores quite a few neighboring nodes surrounding the start node like Dijkstra's. The algorithm differentiates itself from A* through its use of heuristics: it continually updates nodes' distance from the start node while taking into account their estimated distance from the target node. This effectively "balances" the difference in total distance between nodes closer to the start node and nodes closer to the target node, which results in the triangle-like shape of the Swarm Algorithm. We named the algorithm "Swarm" because one of its potential applications could be seen in a video-game where a character must keep track of a boss with high priority (the target node), all the while keeping tracking of neighboring enemies that might be swarming nearby. 

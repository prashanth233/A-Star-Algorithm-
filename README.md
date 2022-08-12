# A-Star-Algorithm

The most common pathfinding object is Astar algorithm since it is versatile and may be applied in a variety of situations. Astar may be used to determine the shortest path, much like Dijkstra's Algorithm. Astar can utilise a heuristic to steer itself, similar to Greedy Best-First-Search. The key to its success is that it combines the information that Greedy Best-First-Search and Dijkstra's Algorithm employ, prioritising vertices that are near to the beginning point (favoring vertices that are close to the goal). According to accepted nomenclature, h(n) stands for the heuristic-estimated cost from vertex n to the target, while g(n) indicates the actual cost of the path from the starting point to any vertex n. As it advances from the beginning point to the objective, a star balances the two. Every time the main loop is executed, the vertex with the lowest f(n) = g(n) + h is examined (n).


<img width="800" alt="Screenshot 2022-08-12 at 2 21 32 PM" src="https://user-images.githubusercontent.com/56962753/184319984-2731afa3-df01-41a5-96b3-be9b56deae92.png">

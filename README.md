<!DOCTYPE html>
<html>

<head>
    <title>Pathfinding Algorithms - A* and Dijkstra</title>
</head>

<body>

    <h1>Pathfinding Algorithms - A* and Dijkstra</h1>

    <p>This project contains Python implementations of the A* and Dijkstra algorithms used for pathfinding and graph traversal.</p>

    <h2>About A* and Dijkstra Algorithms</h2>

    <h3>Dijkstra's Algorithm</h3>
    <ul>
        <li>Dijkstra's algorithm is a graph search algorithm used to find the shortest path between nodes in a weighted graph.</li>
        <li>It explores all possible paths from the start node to all other nodes and selects the path with the minimum total cost.</li>
        <li>Dijkstra's algorithm guarantees that it will find the shortest path, making it optimal.</li>
        <li>However, it does not consider any heuristic, so it may not be the fastest option for large graphs.</li>
    </ul>

    <h3>A* Algorithm</h3>
    <ul>
        <li>A* (A star) is also used for finding the shortest path in a weighted graph but includes a heuristic component.</li>
        <li>It combines the advantages of both uniform cost search (like Dijkstra's) and greedy search (using a heuristic).</li>
        <li>A* uses a heuristic function to estimate the cost from the current node to the goal, helping it prioritize paths that are likely to be shorter.</li>
        <li>It guarantees an optimal path if the heuristic is both admissible (never overestimates the true cost) and consistent.</li>
        <li>A* is often faster than Dijkstra's algorithm because it can quickly eliminate paths that are unlikely to be optimal due to its use of heuristics.</li>
    </ul>

    <h2>Why A* is Preferred</h2>
    <p>A* is often preferred over Dijkstra's algorithm because it can significantly reduce the number of nodes visited during the search, leading to faster pathfinding in many cases. It achieves this by using the heuristic to prioritize nodes that are more likely to lead to a shorter path.</p>

    <h2>Demo</h2>
    <p>A Python graphical demo program is provided to animate the progress of path searching, and the two resulted paths for comparison.</p>

    <h2>Pathfinding Demo Images</h2>
    <img src="URL_TO_YOUR_A_STAR_IMAGE" alt="A* Algorithm">
    <img src="URL_TO_YOUR_DIJKSTRA_IMAGE" alt="Dijkstra's Algorithm">

</body>

</html>

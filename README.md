**Path Finder Visualization using Pygame**

This Python script demonstrates a pathfinding visualization using the Pygame library. The program allows the user to create barriers, set the start and end points, and find the shortest path between them using the A* search algorithm.

**Requirements:**
- Python (3.x recommended)
- Pygame

**Installation:**
Make sure you have Python installed on your system. You can install the required library using `pip`:

```bash
pip install pygame
```

**How to Use:**
1. Run the script.
2. A window will open displaying a grid.
3. Left-click on any grid cell to create barriers.
4. Right-click on a barrier cell to remove it.
5. Press the left mouse button on a cell to set it as the start point (orange).
6. Press the left mouse button on another cell to set it as the end point (turquoise).
7. Press the "Space" key to start the pathfinding algorithm and find the shortest path between the start and end points. The algorithm uses the A* search algorithm.
8. Press the "C" key to clear the grid and start over.

**Note:**
- The grid is represented by a 50x50 matrix, and you can modify this value as needed in the `main` function.
- The orange cell represents the start point, and the turquoise cell represents the end point.
- The barriers (black cells) prevent the pathfinding algorithm from traversing through them.
- The algorithm finds the shortest path and highlights it in purple.

**Enjoy exploring pathfinding algorithms with this interactive visualization tool!**

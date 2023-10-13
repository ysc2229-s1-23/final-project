# Graph Algorithm Visualizer

## Description

Develop a visualization tool for graph traversal algorithms, focusing on Dijkstra and A* algorithms, utilizing Python and Pygame.

## Project Structure

- **algorithms**
  - `dijkstra.py`: Implementation of Dijkstra's algorithm.
  - `a_star.py`: Implementation of A* algorithm for pathfinding.
- **components**
  - `spot.py`: Definition and management of a spot/node in the grid.
  - `grid.py`: Handling grid functionality, drawings, and updates.
- **assets**
  - `demo.mov`: A demonstration video providing an example of expected outcomes.
- **main.py**: Main script to execute the application.
- **pyproject.toml**: Configuration file for Poetry, outlining project dependencies.

## Prerequisites

- **Python** (3.x recommended)
- **Poetry**
- **Pygame**

To install dependencies, utilize Poetry:
```bash
poetry add pygame
```

Ensure the virtual environment is active when running the project.

## Requirements

### Core Features

- Implement and visualize **Dijkstra and A* algorithms** using Pygame.
- Display pathfinding statistics.
- **Path Tracing**: Implement a smooth animation to trace the final path.
- Allow users to:
  - Define **start** and **end** nodes.
  - **Draw barriers** and **clear** them.
  - **Select** an algorithm to execute.
  - **Reset** the grid or **clear** the previously found path, while retaining barriers. Make sure you can run the algorithm again after clearing the path.
- The pathfinding algorithm should **terminate once the start node finds the end node**.

### [Optional] (For Groups Only)

- Implement two additional graph traversal algorithms.

### Note

Feel free to modify the given template code according to your project needs.

### [Optional] Additional Features (Bonus Points)

Features for bonus points (up to a maximum) might include:
- **Algorithm Speed Control**: Enable users to control visualization speed.
- **Algorithm Comparison**: Offer a side-by-side comparison of different algorithms on the same grid.

### Implementation Details

- Use ```Pygame``` for GUI creation.
- Visualize pathfinding in real-time on the GUI.
- Ensure intuitive and user-friendly interactions.

### Your README

In your ```README.md```, include:
- Descriptions of algorithms implemented.
- Encountered issues or challenges.
- Instructions on code execution.

## Grading Rubric

1. **Algorithm Implementation and Visualization**: 50%
   - Effective implementation and visualization of **Dijkstra and A* algorithms**.
2. **Statistics Display**: 5%
   - Accurate display of pathfinding statistics. Statics include at least the time taken to find the path and the number of nodes visited. Please include any other statistics you find relevant. At least two more statistics are required for groups.
3. **Code Quality and User Interaction**: 15%
   - Maintain code quality and ensure intuitive user interactions.
4. **Additional Algorithm(s) Implementation**: 10% 
   - Implement two more graph traversal algorithms (for groups only).
   Note: If you are working individually, you can skip this requirement. This means **1.** will be worth 60%.
5. **Testing and Validation**: 20%
   - Validate algorithm’s correctness and efficiency through testing.

## Submission

Ensure to push your final code to your designated repository before the deadline.

Wishing you the best of luck, and happy coding!

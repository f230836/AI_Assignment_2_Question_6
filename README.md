# Dynamic Pathfinding Agent

This repository contains a dynamic pathfinding agent implemented with a Tkinter GUI. The application allows users to visualize and interact with pathfinding algorithms such as A* and Greedy Best-First Search (GBFS) in a grid environment.

## Features
- **Pathfinding Algorithms**: Supports A* and GBFS.
- **Dynamic Obstacles**: Simulates dynamic obstacles that appear during the agent's movement.
- **Customizable Grid**: Adjust grid size, wall density, and more.
- **Interactive GUI**: Place start/goal points, draw walls, and visualize the search process.

## Prerequisites
- Python 3.8 or higher
- No additional dependencies are required as `tkinter` is included in the Python standard library.

## How to Run
### Option 1: Run from Jupyter Notebook
1. Open the `question#6.ipynb` file in Jupyter Notebook.
2. Run the following command in a code cell:
   ```python
   %run pathfinding.py
   ```

### Option 2: Run Directly
1. Open a terminal and navigate to the project directory.
2. Run the following command:
   ```bash
   python pathfinding.py
   ```

## Usage
1. **Start the Application**: Follow the steps above to launch the GUI.
2. **Keyboard Shortcuts**:
   - `S`: Start the search.
   - `A`: Switch to A* algorithm.
   - `G`: Switch to GBFS algorithm.
   - `M`: Use Manhattan heuristic.
   - `E`: Use Euclidean heuristic.
   - `D`: Toggle dynamic mode.
   - `R`: Generate a random map.
   - `C`: Clear the current search.
   - `X`: Reset the grid.
   - `1`: Place the start point.
   - `2`: Place the goal point.
3. **Mouse Interaction**:
   - Left-click: Draw walls.
   - Right-click: Erase walls.
   - Drag: Draw/erase walls continuously.

## File Structure
- `pathfinding.py`: Main application script.
- `question#6.ipynb`: Jupyter Notebook for running the application.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

Enjoy exploring pathfinding algorithms with this interactive tool!

# 🎮 Maze Solver Project

Welcome to the Maze Solver Project! 🚀 This project implements different search algorithms to find a path through a maze. The algorithms include Breadth-first search, Uniform-cost search, Iterative deepening search, Greedy-best first search, and A* search.

for the demo video  (https://drive.google.com/drive/folders/13wnM5kbXzYDVj1eSpnxkDS2l-eeOYrIK)
## 🌟 Features

✅ **Multiple Search Algorithms**: Implement and visualize different search algorithms.  
✅ **Interactive Interface**: Use buttons to choose and run different algorithms.  
✅ **Visualization**: Watch the robot navigate through the maze and see the path taken.  
✅ **Customizable Maze**: Edit the input file to create your own maze configurations.  

## 📝 Project Description

This project is designed to help you understand and visualize how different search algorithms work in pathfinding. You can load a maze configuration, choose an algorithm, and see the robot find its way from the start point to the goal point.

## 🛠️ Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.x 🐍
- NumPy 📊
- Turtle Graphics 🎨

## 📁 File Structure

📁 **environment.py**  
- Defines the Maze and FileSystem classes to handle maze creation and input file reading.

📁 **main.py**  
- Main execution file that sets up the environment, initializes the maze, and provides the interactive interface.

📁 **search_algorithm.py**  
- Contains the SearchAlgorithm class with implementations of different search algorithms.

📁 **visualization.py**  
- Handles the graphical representation of the maze, robot, and interface elements.

📁 **input.txt**  
- Configuration file where you can define the maze size, start and goal points, and obstacles.

## 🚀 Getting Started

1. Clone the repository:  
   `git clone <repository-url>` 📋

2. Navigate to the project directory:  
   `cd maze-solver` 📂

3. Install the required packages:  
   `pip install numpy` 📦

4. Run the project:  
   `python main.py` 💻

## 🎯 How to Use

1. Edit the `input.txt` file to customize your maze:  
   - Define the maze size, start point, goal point, and obstacles. 📝

2. Run the `main.py` file to start the application. 🏁

3. Use the buttons in the interface to select and run a search algorithm:  
   - **Breadth-first search**: Explores all neighboring nodes at the present depth level before moving to nodes at the next depth level.  
   - **Uniform-cost search**: Explores paths in the order of their cost from the start node.  
   - **Iterative deepening search**: Performs a series of depth-limited searches with increasing depth limits.  
   - **Greedy-best first search**: Explores paths that seem to lead closer to the goal based on a heuristic.  
   - **A***: Uses a combination of path cost and heuristic to explore paths efficiently.  

4. Watch the arrow navigate the maze and see the path taken!  and complexity of the algoritms🤖

## 🎨 Customization

You can customize the maze by editing the `input.txt` file. The file format is as follows:

```
<maze_width> <maze_height>
<start_x> <start_y> <goal_x> <goal_y>
<number_of_obstacles>
<obstacle_1_point_1_x> <obstacle_1_point_1_y> ... <obstacle_1_point_n_x> <obstacle_1_point_n_y>
...
<obstacle_m_point_1_x> <obstacle_m_point_1_y> ... <obstacle_m_point_n_x> <obstacle_m_point_n_y>
```


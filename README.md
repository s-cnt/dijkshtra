# Pathfinding Visualizer

This project is a **Pathfinding Visualizer** implemented using **OpenGL (GLUT) and C++**. It allows users to create a grid, place start and destination points, add obstacles, and visualize the pathfinding process.

## Features

- **Grid-based Pathfinding**: Uses a **40x40 grid** where users can place nodes and obstacles.
- **Mouse Interaction**:
  - Left-click to place **Source, Destination, and Walls**.
  - Right-click to remove placed nodes.
- **Visualization**:
  - Press `S` to **start pathfinding**.
  - Press `R` to **reset** the grid.
  - Press `Enter` to **start the application**.
  - Press `ESC` to **exit** the application**.
- **Pathfinding Algorithm**:
  - Implements a priority queue-based **Dijkstra’s Algorithm**.
  - Finds the shortest path from the **source node** to the **destination node**.

## Prerequisites

Ensure you have the following installed:

- **C++ Compiler** (GCC, Clang, MSVC)
- **OpenGL & GLUT Library**  
  Install using:
  ```sh
  sudo apt-get install freeglut3-dev   # Ubuntu
  brew install freeglut                # macOS (Homebrew)
  ```
  Windows users may need to manually install **GLUT** and link the libraries.

## How to Compile & Run

### Linux/macOS:
```sh
g++ graph.cpp -o pathfinder -lGL -lGLU -lglut
./pathfinder
```

### Windows (MinGW):
```sh
g++ graph.cpp -o pathfinder.exe -lopengl32 -lglu32 -lfreeglut
pathfinder.exe
```

## Controls

| Key | Action |
| --- | ------ |
| `Left Mouse Click` | Place **Start, Destination, and Walls** |
| `Right Mouse Click` | Remove placed nodes |
| `S` | Start the pathfinding visualization |
| `R` | Reset the grid |
| `Enter` | Start the application |
| `ESC` | Exit the program |

## Contributors

- **Sushant**


## License

This project is open-source under the **MIT License**.


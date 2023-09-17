# Pygame-Pathfinding-Visualization
Visualize pathfinding algorithms in a grid-based environment using Pygame and the A* algorithm.
# Pathfinding Visualization with Pygame

This repository contains a Python program that uses the Pygame library to visualize pathfinding on a grid. It demonstrates the A* algorithm for finding a path from a starting point to a target point in a grid-based environment.

## Prerequisites

Before running the code, make sure you have the following:

- Python installed on your system (Python 3.x recommended).
- Pygame library installed. You can install it using pip:

    ```
    pip install pygame
    ```

## Usage

1. Clone this repository or download the source code to your local machine.

2. Navigate to the project directory containing the code.

3. Run the program using Python:

    ```
    python main.py
    ```

## Instructions

- The program opens a window displaying a grid-based map with obstacles and a car.

- Click on the grid cells to set a destination for the car.

- The car will then use the A* algorithm to find the shortest path to the clicked destination and follow it.

- The path will be displayed on the screen as a white line.

- The grid cells with a value of `1` represent obstacles that the car cannot pass through.

## Controls

- Click on the grid cells to set the car's destination.

- Click the close button (X) on the window to exit the program.

## Customization

You can customize the map by modifying the `matrix` variable in the code. The `matrix` is a 2D array where `0` represents empty cells, and `1` represents obstacles. You can change the layout of obstacles to create different maps.

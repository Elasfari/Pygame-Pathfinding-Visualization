# Pygame Pathfinding Visualization

Explore the world of pathfinding with this Python program that leverages the Pygame library to provide an interactive visualization of pathfinding algorithms on a grid. Witness the A* algorithm in action as it finds the optimal route from a designated starting point to a target destination in a captivating grid-based environment.

## Prerequisites

Before diving into the code, ensure you have the following prerequisites in place:

- Python installed on your system (Python 3.x recommended).
- Pygame library installed. You can quickly install it using pip:

    ```
    pip install pygame
    ```

## Getting Started

1. Clone this repository or download the source code to your local machine.

2. Navigate to the project directory containing the code.

3. Launch the program using Python:

    ```
    python main.py
    ```

## How to Use

- The program launches a window featuring a grid-based map, complete with obstacles and a nimble car.

- Interact with the grid by clicking on individual cells to set the car's destination.

- Watch in awe as the car employs the A* algorithm to discover the most efficient path to the selected destination, and then gracefully follows it.

- The path is showcased on the screen as a crisp, white trail.

- Grid cells marked with a value of `1` represent impassable obstacles, posing intriguing challenges for the pathfinding car.

## Controls

- Set the car's destination by clicking on any desired grid cell.

- When done, exit the program gracefully by clicking the close button (X) on the window.

## Personalization

You hold the power to craft unique maps by tweaking the `matrix` variable in the code. The `matrix` functions as a 2D array where `0` signifies open cells, while `1` symbolizes formidable obstacles. Unleash your creativity and craft diverse terrains to test the pathfinding capabilities.

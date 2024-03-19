# FrozenLake Q-Learning Visualization

This repository contains code for visualizing a Q-learning agent's behavior on the FrozenLake environment using Pygame and OpenCV.

## Overview

The code includes the following components:

1. `FrozenLake` class: Defines the FrozenLake environment, including the grid layout, state space, action space, rendering method, and methods for stepping through actions and computing rewards.

2. `QLearning` class: Implements the Q-learning algorithm, including initialization, action selection, Q-table updating, and exploration/exploitation control.

## Usage

1. Install the required dependencies: Pygame, OpenCV, and IPython (if running in a Jupyter Notebook).

2. Import the required libraries and define the FrozenLake and QLearning classes as provided in the code.

3. Create a FrozenLake environment with the desired grid size and layout.

4. Initialize a Q-learning agent with appropriate parameters (exploration rate, discount factor, learning rate, etc.).

5. Train the Q-learning agent by running multiple episodes, updating the Q-table based on observed transitions.

6. Visualize the Q-learning agent's behavior by running the visualization loop, which renders each step of the agent's behavior using Pygame and OpenCV.

## Files

- `frozenlake.py`: Contains the definition of the FrozenLake environment and QLearning class.

## Requirements

- Python 3.x
- Pygame
- OpenCV
- IPython (if running in a Jupyter Notebook)

## Credits

This code is adapted from various sources and tutorials on reinforcement learning, Pygame, and OpenCV.


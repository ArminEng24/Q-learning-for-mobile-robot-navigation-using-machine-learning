# Q-learning-for-mobile-robot-navigation-using-machine-learning

## Description
This project implements Q-learning for mobile robot navigation in a grid environment. The goal is to explore the effects of different hyperparameters and reward structures on the learning performance of the agent.

## Table of Contents  
- [Files](#files)  
- [Experiments](#experiments)
  - [Modifying-the-Maze](#modifying-the-maze)
  - [Changing-Agent-Learning-Parameters](#changing-agent-learning-parameters)
  - [Changing-Reward-and-Testing-Learning-Performance](#changing-reward-and-testing-learning-performance)
- [Results](#results)
- [Usage](#usage)
- [Acknowledgments](#acknowledgments)

## Files
- `grid_env.py`: defines the grid environment class
- `agent.py`: defines the agent class
- `task3.py`: main script for running the experiments
- `README.md`: this file

## Experiments
The project includes three main experiments:

### Modifying-the-Maze
- Modify the maze size, shape, and start position
- Train and test the agent with different maze configurations

### Changing-Agent-Learning-Parameters

- Modify the agent's learning rate, discount factor, and exploration parameters
- Train and test the agent with different learning parameters

### Changing-Reward-and-Testing-Learning-Performance

- Modify the reward structure to include a "hole" in the maze
- Train and test the agent with the modified reward structure

## Results
The results of the experiments are presented in the form of plots and tables.

## Usage
To run the experiments, simply execute the `task3.py` script. You can modify the hyperparameters and experiment settings by editing the script.

## Acknowledgments
This project was inspired by the Q-learning algorithm and mobile robot navigation research.

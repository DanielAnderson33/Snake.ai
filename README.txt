Snake Game AI
-------------

This project implements an AI agent to play the classic Snake game using the Q-learning algorithm. The agent learns to navigate the snake on a grid, avoiding collisions with walls and its own body while attempting to eat food to grow longer.

Features
--------

- Snake Movement: The snake can move in four directions: up, down, left, and right.
- Food Generation: Food appears randomly on the grid for the snake to eat.
- Collision Detection: The agent detects collisions with walls and the snake's body, resulting in game over.
- Score Tracking: The agent keeps track of the score based on the number of food items eaten.

Files
-----

- game.py: Contains the implementation of the Snake game environment (SnakeGameAI class).
- model.py: Defines the neural network model (Linear_QNet class) used by the agent for Q-learning.
- helper.py: Provides helper functions for plotting and visualization.
- agent.py: Entry point for training the agent.

Getting Started
---------------

1. Install the necessary dependencies by running `pip install -r requirements.txt`.
2. Run the `agent.py` script to train the AI agent.
3. Monitor the training progress and performance metrics.
4. Once trained, the agent can be used to play the Snake game autonomously.
5. A .png of the plot is saved after each episode, it is overwritten every time. 

TODO: 
---------------
- Add body position to game state
- Update model to be aware of body position
- Fix bug where snake eats self randomly?
- Make this readme less GPT'd

Usage
-----

python main.py

Dependencies
------------

- Python 3.x
- Pygame
- NumPy
- Torch
- Matplotlib
- IPython

Credits
-------

This project was created by [Your Name].

License
-------

This project is licensed under the MIT License - see the LICENSE file for details.

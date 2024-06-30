# CS370
Final Project in Current and Emerging Trends in Computer Science

In this project, we use the Google TensorFlow and Keras libraries to train a Q-learning model to play our custom pirate game. The objective of the game is to reach a designated target destination by navigating through an environment. This environment is represented by an 8x8 matrix, and it is filled with obstacles. To solve this problem, we must design a Q-training model that uses reinforcement learning, where the agent learns to make decisions by interacting with the environment and receiving either rewards for winning or penalties for taking a wrong turn. 
Keras Q-learning utilizes a neural network to approximate the Q-function. This function estimates the expected cumulative reward for taking a specific action in a given state, facilitating the agent's decision-making process (Choudhary, 2023). During each epoch, the agent explores the environment using an epsilon-greedy equation to find an optimal choice between exploration, i.e. randomly discovering new paths, and exploitation, choosing a path based on previously learned experiences. This way, the model continuously learns to navigate through the maze.

For this project, I was provided with some starter code and a sample environment where the pirate agent will be placed, and was asked to create a deep Q-learning algorithm to train the pirate agent. 

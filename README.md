# rl_reacher_x86_64
Udacity Reinforcement Learning Continuous Control Project using Reacher Unity Environment

# Project Description
The agent is trained to move a double-jointed arm to a target location. A reward of 0.1 is provided for the steps that the hand is at the target location. Therefore the goal of the project is to train an agent that can maintain the location of the arm at the target location for as long as possible.

The state space consists of 33 dimensions that includes position, rotation, velocity, and angular velocities of the arm. The action vector consists of 4 numbers that correspond to torque applied to the two joints in the arm. Each number should be between -1 and 1.

The version of the environment solved here contains 20 identical agents, and an average score of 30 over 100 episodes is required to consider the environment solved.

# Getting Started
To install all the necessary dependencies for this project, run: !pip -q install ./python

# Run the Code
To run the code for training the agent, open the jupyter notebook named learning.ipynb and run all cells. The training automatically terminates when the reward requirement is reached for the agent. It will save the model output as checkpoint_actor.pth and checkpoint_critic.pth.

# Banana Navigation Project
The project is part of the Udacity Deep Reinforcement Learning Nanodegree.

![banana](banana.gif)

In this project we train an agent to navigate a Unity square world and collect bananas. The project uses Unity Machine Learning Agents, an open-source Unity plugin that enables games and simulations to serve as environments for training intelligent agents.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction.
Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to: 0 - move forward, 1 - move backward, 2 - turn left, 3 - turn right.  

The task is episodic, meaning that it has a defined end. The environment is considered solved with an average score of +13 over 100 consecutive episodes.

## Libraries
The code uses python 3.6, numpy and pytorch and UnityEnvironment.

## Instructions
Follow the Navigation.ipynb jupyter notebook. You can read more about the project in  Report.ipynb.

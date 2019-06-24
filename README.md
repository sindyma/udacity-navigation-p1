# udacity-navigation-p1
Solving the Unity banana environment using deep reinforcement learning. This repo contains a project to meet requirements for the Udacity Reinforcement Learning Nanodegree.

# Background
This is the first project in [Udacity's Deep RL nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893). Prior to this project, the degree takes you through reinforcement learning theory first and then moves onto deep RL.  This project focuses on using DQN to solve a variant of Udacity's banana environment for 100 steps and scoring 13 or more. The modified environment is included in this repo.

# Getting started
To get started, clone this repo.

``git clone https://github.com/sindyma/udacity-navigation-p1.git``

Open Navigation.ipynb in the root directory. This Jupyter Notebook trains an RL agent to navigate the environment and collect bananas.

# Troubleshooting
If you aren't able to get started, see if any of the following describe your situation:
* Python version
This repo has been developed with python 3.7. Python 2 users may need to switch their kernel and ensure all dependencies have been installed for python 3.7
* Dependencies
You may need to install dependencies:
* unity-ml
* numpy
* torch
* matplotlib

# Train your own RL agent
Run all the cells in `Navigation.ipynb` to train your own agent. At the end of training, your weights will be saved in the folder as `trained_agent.pth`. If this file exists from a previous training session, this will be overwritten.

# Run a trained agent
The final section in `Navigation.ipynb` runs a trained agent (submission for the project).

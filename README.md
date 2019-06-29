# udacity-navigation-p1
Solving the Unity banana environment using deep reinforcement learning. This repo contains a project to meet requirements for the Udacity Reinforcement Learning Nanodegree.

# Background
This is the first project in [Udacity's Deep RL nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893). Prior to this project, the degree takes you through reinforcement learning theory first and then moves onto deep RL.  This project focuses on using DQN to solve a variant of Udacity's banana environment for 100 steps and scoring 13 or more. The modified environment is included in this repo.

# Getting started
To get started, download the training environment for your OS:

* Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)

* Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)

* Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)

* Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

Next, clone this github repo:

```git clone https://github.com/sindyma/udacity-navigation-p1.git```

Before running the Jupyter Notebook, ensure all requirements are installed. To do this, navigate to the cloned repo and run the following command. This will install all packages specified in `requirements.txt`.

```pip install .```

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

# The environment and success criteria
The state space in this environment has 37 dimensions: the agent's velocity and ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available: 
* 0 - move forward
* 1 - move backward
* 2 - turn left
* 3 - turn right

In order to solve the environment, the agent needs to get an average score of 13 over 100 episodes. A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  

Run all the cells in `Navigation.ipynb` to train your own agent. At the end of training, your weights will be saved in the folder as `trained_agent.pth`. If this file exists from a previous training session, this will be overwritten.

# Run a trained agent
The final section in `Navigation.ipynb` runs a trained agent (submission for the project).

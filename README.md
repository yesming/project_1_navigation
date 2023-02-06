# project 1 : Navigation
This repo is for the deep reinforcement learning nanodegree of Udacity.
Espectially, in this repo, I will deal with the first project, Navigation.

**Note : The version of pytorch is 1.4.0. The original version from udacity is 0.4.0. Due to the version of numpy, I upgraded the version of pytorch.** 

## The code structure of this project
- aa
  - bb
  - cc

## How to start
This project is supposed that you have anaconda.

1. activate virtual environment 
```bash
conda create --name drlnd python=3.6
source activate drlnd
```
2. TBD


## Project
Project 

## State Space and Action space
The state space has 37 dimensions and contains the agent's velocity, alogn with ray-based perception of objects around the agent's forward direction.

And the discretized actions are described as below
```
0 : move forward
1 : move backward
2 : turn left
3 : turn right
```

## Reward and Evaluate
The agent gets +1 reward when it can reach to yellow banana

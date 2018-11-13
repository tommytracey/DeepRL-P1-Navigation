#### Udacity Deep Reinforcement Learning Nanodegree
### Project 1: Navigation
# Train an RL Agent to Collect Bananas
:banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana::banana:

##### &nbsp;

<img src="images/banana_agent.gif" width="100%" align="top-left" alt="" title="Banana Agent" />

##### &nbsp;

## Goal
In this project, we build a reinforcement learning (RL) agent that navigates an environment that is similar to [Unity's Banana Collector environment](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#banana-collector).

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. The goal of our agent is to collect as many yellow bananas as possible while avoiding blue bananas. In order to solve the environment, our agent must achieve an average score of +13 over 100 consecutive episodes.

##### &nbsp;

## Approach
The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

- `0` move forward
- `1` move backward
- `2` turn left
- `3` turn right



##### &nbsp;

## Results
The results from the final model can be found in cell 20 of the [notebook](machine_translation.ipynb).

Validation accuracy: 97.5%

Training time: 23 epochs


##### &nbsp;

## Future Improvements

##### &nbsp;
##### &nbsp;

---

# Project Starter Code
In case you want to run this project yourself, below is the project starter code.

## Setup
The original Udacity repo for this project can be found [here]().

# Grid World Value Iteration

This project involves creating a grid world environment and applying value iteration to find the optimum policy. Below is the value iteration pseudocode that was programmed and tested.
<img src="https://imgur.com/u7fb9OM.jpg" alt_text="Value Iteration Pseudocode" width="700">

The state space of the grid world was represented using an array of length 25 (NxM) using the index system as shown below. In the grid world it is possible to have two different items, fire and water. Each step performed by the agent received a reward of -1. The rewards for collecting fire was set to -10 and the reward for collecting water set to 10. Both the fire and water are terminal states.

<img src="https://imgur.com/ohcW3LA.jpg" alt_text="Gridworld Index" width="300">

## Deterministic Environment
It was first decided to implement a deterministic environment as it is easier to check is the solution is correct. The two images below show the Values and Policy derived for this environment, with orange representing fire and blue representing water.

<img src="https://imgur.com/mkKnIGM.jpg" alt_text="Deterministic Environment Values" width="300">
<img src="https://imgur.com/EU4WWhz.jpg" alt_text="Deterministic Environment Policy" width="300">

## Stochastic Environment

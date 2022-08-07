# Reinforcement-Learning
The repository for some of my reinforcement learning codes

# Multi-Armed Bandits
## Problem1
Extract q*(a) for each 10 actions from a normal distribution, then each time select each action greedily and do it 1000 times.

## Problem2
Do experiment of Problem1 2000 times and select action in three manners: greedy, epsilon-greedy (epsilon=0.01), and epsilon-greedy (epsilon=0.1)

## Problem3
Use Upper-Confidence-Bound Action Selection method with c=2, number of steps: 1000, and number of itteration: 2000

# Frozen Lake 8*8
## Problem1
Considering uniform action selection probability for all actions, evaluate the policy with the policy evaluation algorithm:

![1](https://user-images.githubusercontent.com/79801992/183277810-acc96d07-9db4-42f4-9087-a03d3f7b068e.png)

## Problem2
Implement policy itteration algorithm:

![2](https://user-images.githubusercontent.com/79801992/183277866-4819611e-1175-457d-b2ce-545675bb4c23.png)

## Problem3
Using the optimal policy obtained in problem2, evaluate that with Monte-Carlo method

## Problem4
Determine the optimal action value using off-policy Monte-Carlo with importance sampling:

![4](https://user-images.githubusercontent.com/79801992/183278133-3d0cf995-cf4a-40c6-b451-a60545ed732e.png)

# Mountain Car
mountain car of openai gym using semi-gradient Sarsa with tiling

# CardPole with naive Monte Carlo RL algorithm

## Presentation

The CartPole environment from Open AI Gym (https://gym.openai.com/envs/CartPole-v1/) is solved using a Simple, yet efficient, reinforcement learning algorithm based on Monte Carlo estimates of the action-value function.

the goal of this environment is to hold a card vertically on a cart, which can moves on a rail to maintain the pole balance.

## Description

The agent use a Monte Carlo algorithm to learn the action value function of the problem offline. It stores the past (state, action) pairs played in the past episodes and stores their average outcomes, so it can further chose the best estimate action in a given state.

The observation space is discretized linearly to have a compact space of state. 

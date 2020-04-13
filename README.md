# CartPole with naive Monte Carlo RL algorithm

## Presentation

The CartPole environment from OpenAI Gym (https://gym.openai.com/envs/CartPole-v1/) is solved using a simple, yet efficient, reinforcement learning algorithm based on Monte Carlo estimates of the action-value function.

The goal of this environment is to hold a pole vertically on a cart, which moves on a rail to maintain the pole balance.

## Description

The agent uses a Monte Carlo algorithm to learn the action-value function of the problem offline. It stores the past (state, action) pairs played in the past episodes and stores their average outcomes, so it can further choose the best estimated action in a given state.

The observation space is discretized linearly to have a compact space of state. 

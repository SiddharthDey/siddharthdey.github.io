---
layout: page
title: CUDA accelerated Q-Learning
---

Implemented Q-Learning algorithm for a 2D grid world environment in CUDA

- Multiple agents were initialized with random start locations in a 2D grid world

- Q-learning was used to learn the optimal policy, where the objective was to reach the goal state (flag) in the minimum number of steps while avoiding land mines

- A common Q-table was maintained and updated simultaneously by all the agents based on the Bellman Optimality Equation

- The computation involved with each agent was implemented in different threads to parallelize the Q learning process across multiple agents

## Visualization of the Multi-agent Q-Learning for grid navigation
{% include embed.html url="https://drive.google.com/file/d/1OHNXCZzaJt5NszWSHgXbqBqCvd-dfAct/preview" %}
<!-- <p style="text-align: center; font-style: italic;"> 
Visualization of the Multi-agent Q-Learning for grid navigation
</p> -->
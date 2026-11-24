# Intelligent Parking Simulation

A Python project developed for my Artificial Intelligence course at UNT. It uses a Markov Decision Process (MDP) and value iteration to guide cars toward a parking destination while avoiding obstacles and collision hazards.

## Features

- 5 × 8 grid environment.
- Value iteration and policy generation.
- Reward and penalty-based decision-making.
- Random movement noise of 10%.
- Obstacle avoidance.
- Testing 21 different living reward values.

## Results

Each environment was tested with 700 parking attempts.

| Environment | Successful Attempts | Success Rate |
|---|---:|---:|
| Original | 683/700 | 97.6% |
| With Obstacle | 695/700 | 99.3% |

Results may vary between runs due to randomized movement.

## Technologies

Python, Google Colab

## Concepts Covered

- Markov Decision Processes
- Reinforcement learning fundamentals
- Value iteration
- Probability and stochastic simulation
- Policy optimization

## What I Learned

This project helped me understand how an agent can make decisions under uncertainty and adapt its movements when the environment changes.

# FrozenLake Reinforcement Learning

This project implements classic reinforcement learning algorithms to solve the **FrozenLake** environment from [OpenAI Gym](https://www.gymlibrary.dev/).  
The goal is to train agents that can navigate a frozen lake gridworld to reach the goal while avoiding holes.

## 📌 Features
- Implemented **Dynamic Programming (DP)** methods:
  - **Value Iteration**
  - **Policy Iteration**
- Implemented **Temporal-Difference (TD)** method:
  - **SARSA**
- Benchmarked performance on both **slippery** and **non-slippery** variants of the environment.

## 📊 Results
- **DP (8×8 map)**:  
  - Non-slippery → **100.0% success** over 10,000 episodes (avg reward = 1.0).  
  - Slippery → **64.6% success** (avg reward ≈ 0.65).  
- **SARSA** (best config: α=0.1, γ=0.9, ε=0.2, β=0.1):  
  - Achieved **92.76% training success**.  
  - Evaluated policy reached up to **100% success** (non-slippery).

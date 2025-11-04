# Honors Machine Learning Project  
## **Dynamic Programming in Reinforcement Learning**

**Contributors:**  
- Ruth Walters  
- Jaxon Ham  

**Deliverables Due:** November 4, 2025  
Code File: "Honors Project Code.ipynb"
- contains the full notebook with all environment setup, function definitions, and graphic outputs
- running the notebook is set-up to be random every time, but can be seeded for reproducability

Presentation:
- contains a mathematical overview of the concepts detailed below, as well as an overview of the real-world coded example
- file is .pdf because .ppt file was too large to upload
---

## Project Overview
This project explores **Dynamic Programming (DP)** as a model-based method in **Reinforcement Learning (RL)**.  
Our focus is on demonstrating how DP algorithms can be used to compute **optimal policies** for an agent operating in a known environment, represented as a **GridWorld**.

The project connects theoretical foundations from the Bellman equations and policy/value iteration to a working Python simulation that visualizes how an agent learns to move optimally through an environment with rewards, penalties, and probabilistic transitions.

---

## Objectives
1. **Understand Dynamic Programming in RL**: applying Bellman equations to evaluate and improve policies.  
2. **Build a visual MDP simulation**: a grid-based world where the agent learns the optimal route from a start state to a goal.  
3. **Show convergence behavior**: visualize how iterative updates stabilize over time as the value function approaches its optimal state.  
4. **Connect code to math**: demonstrate how key RL functions (V(s), V*(s), π*(s), Q(s,a)) operate in a practical example.

---

## Conceptual Background
Dynamic Programming is used in **model-based reinforcement learning**, where the environment’s dynamics (states, actions, transition probabilities, and rewards) are **known**.

This project implements **Value Iteration**, which combines:
- **Policy Evaluation:** estimating how good it is to be in each state (V(s))  
- **Policy Improvement:** updating the policy to choose the best action at each state (π*(s))  

These processes repeat until **convergence**, when the values no longer change significantly, meaning the agent has found the optimal way to act.


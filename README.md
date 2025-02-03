# ReinforcementLearning

This repository contains a collection of Jupyter notebooks covering fundamental and advanced topics in **Reinforcement Learning (RL)**. Each notebook introduces key RL concepts through theoretical explanations and hands-on implementations.

## 1. Markov Decision Process

This notebook introduces the concept of a **Markov Decision Process (MDP)**, where an agent interacts with an environment and collects rewards based on states. Rewards are attached to states, such as +1 for a win, -1 for a loss, and 0 otherwise. The notebook includes:

- An example of a **walk in a square**, demonstrating state transitions.
- Implementation of an `Environment` class to model the state and reward structure.
- Basic MDP simulations showcasing agent-environment interactions.

This serves as a foundation for understanding how reinforcement learning models decision-making under uncertainty.

## 2. Dynamic Programming

This notebook explores **dynamic programming** techniques for reinforcement learning, specifically **policy iteration** and **value iteration** to determine the optimal policy. These methods require the enumeration of all states and are applicable to simpler models such as **walk, Tic-Tac-Toe, and Nim**.

Key topics covered:
- **Maze navigation** as an example application.
- **Policy Evaluation** using Bellman’s equation.
- **Policy Iteration** to refine strategies for optimal decision-making.

This notebook provides a structured approach to solving MDPs with a known transition model.

## 3. Online Prediction

This notebook focuses on **online prediction** of a value function using **Monte-Carlo learning** and **Temporal Difference (TD) learning**. These methods are essential for reinforcement learning when the environment model is unknown.

Key topics covered:
- **Monte-Carlo Learning**, which estimates value functions based on complete episode returns.
- **TD Learning**, which updates value functions incrementally using bootstrapping.
- **Walk example**, illustrating the differences between MC and TD approaches.

This notebook introduces foundational online learning techniques used in reinforcement learning for value estimation.

## 4. Online Control

This notebook demonstrates **online control** of an agent using **SARSA** and **Q-learning**, two fundamental reinforcement learning algorithms for decision-making in unknown environments.

Key topics covered:
- **SARSA (State-Action-Reward-State-Action)**, an on-policy learning method.
- **Q-Learning**, an off-policy method that learns optimal action values.
- **Tic-Tac-Toe experiment**, comparing SARSA and Q-learning performance under different exploration rates (`ε`).
- Evaluation of **average game gains** over multiple runs.

This notebook provides an interactive way to understand the impact of different exploration strategies on learning performance.

## 5. Value Function Approximation

This notebook explores **value function approximation** for large-scale reinforcement learning problems, where tabular methods become impractical. A **neural network with a single hidden layer** is used to estimate value functions.

Key topics covered:
- **Tic-Tac-Toe experiment**, applying function approximation to reinforcement learning.
- Implementation of **policy** and **training functions** for learning.
- Evaluation of agent performance after training.
- Extending the approach to **Connect Four** and testing different neural network architectures.

This notebook demonstrates how deep learning can be used to scale reinforcement learning to more complex environments.

## 6. Bandit Algorithms

This notebook covers **multi-armed bandit** algorithms, which are foundational for reinforcement learning in environments with a single state and uncertain rewards.

Key topics covered:
- **Multi-Armed Bandit problem**, where an agent selects among multiple options with unknown reward distributions.
- **ε-Greedy Policy**, balancing exploration and exploitation.
- **Optimism in the face of uncertainty**, analyzing agent behavior when ε = 0.
- **Expected gain computation**, comparing theoretical and empirical results.

This notebook introduces key strategies for solving bandit problems, which are widely used in decision-making and online learning scenarios.

## 7. Contextual Bandits

This notebook explores **contextual bandits**, an extension of the multi-armed bandit problem where decisions depend on contextual information. The focus is on recommending **movies** based on available contextual data.

Key topics covered:
- **Movie recommendation task**, using contextual bandit algorithms.
- **Handling a dataset of 1,037 movies** available in 2015.
- **Adaptive decision-making**, where actions are optimized based on observed contexts.

This notebook demonstrates how contextual bandits can be applied to personalized recommendations and adaptive learning tasks.

# Monte Carlo Tree Search (MCTS) Implementation

## Overview

This repository contains an implementation of the Monte Carlo Tree Search (MCTS) algorithm, a popular heuristic search algorithm used in decision processes, particularly in game playing and optimization problems. This README provides an overview of how MCTS works and outlines the common procedures involved in its execution.

## How it Works

MCTS operates by iteratively building and exploring a search tree. The process typically involves the following steps:

1. **Selection**: Starting from the root node, recursively select nodes according to a tree policy. In this implementation, we use the UCB-1 tree policy, which balances exploration and exploitation by choosing actions that maximize a score derived from action values and visit counts.

    Action Selection Formula:
    ```
    a* = argmax_a Q(s, a) + Cp * sqrt(log(N) / n_a)
    ```
    where:
    - `N`: Number of times state `s` has been visited.
    - `n_a`: Number of times action `a` has been taken.
    - `Cp`: Exploration balance parameter.

2. **Expansion**: If the selected node is a leaf node (i.e., it has not been fully explored), expand the tree by adding child nodes corresponding to feasible actions.

3. **Simulation**: Estimate the value of nodes by performing simulations from them. This involves playing out multiple trajectories using a rollout policy or a model to estimate action values.

4. **Backpropagation**: Propagate the rewards obtained from the simulations back up the tree to update the Q-values of parent nodes.

    Backpropagation Formula:
    ```
    Q(parent, a) = r + γ * Q(child, a)
    ```
    where:
    - `r`: Reward obtained from the simulation.
    - `γ`: Discount factor.

For further details on MCTS and its variants, refer to the paper linked in the references section.

## References

- Original Paper: [Efficient Selectivity and Backup Operators in Monte-Carlo Tree Search](https://link.springer.com/chapter/10.1007/978-3-540-75538-8_7)


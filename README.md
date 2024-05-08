# Reinforcement Learning Overview

Reinforcement learning (RL) is a general framework where agents learn to perform actions in an environment to maximize a reward. It involves two main components: the environment and the agent.

## Components of RL:

### 1. Environment:
- Represents the problem to be solved.
- Provides observations to the agent and receives actions from it.
- Generates rewards based on agent's actions.

### 2. Agent:
- Represents the learning algorithm.
- Learns to interact with the environment to maximize rewards.
- Implements a policy π(at|st) to select actions based on observations.

## Interaction:
- The agent and environment continuously interact with each other.
- At each time step, the agent:
  - Receives an observation (state) st from the environment.
  - Selects an action at based on its policy.
  - Receives a reward rt+1 and the next observation st+1.
- The goal is to improve the policy to maximize the sum of rewards (return).

## Note:
- Distinguish between the state of the environment and the observation:
  - State: Entire environment state including hidden information.
  - Observation: Part of the state visible to the agent.
- Observations are denoted as st in literature and represent the agent's perception of the environment.


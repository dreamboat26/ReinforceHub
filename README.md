# DI-engine Quick Start with CartPole v1.0

## Overview

DI-engine is a reinforcement learning (RL) framework designed to simplify the development and deployment of RL algorithms. This quick start guide provides step-by-step instructions for getting started with DI-engine using the CartPole v1.0 environment, a classic RL benchmark problem.

## Prerequisites

Before you begin, ensure that you have the following prerequisites installed:

    Python 3.x
    Pip package manager
    DI-engine framework

You can install DI-engine via pip:

pip install di-engine

Step 1: Set Up CartPole Environment

    Import the necessary modules:

python

import gym

    Create the CartPole v1.0 environment:

python

env = gym.make('CartPole-v1')

Step 2: Define Agent

    Import the Agent class from DI-engine:

python

from diengine.agent import Agent

    Define your RL agent using the Agent class:

python

agent = Agent(env)

Step 3: Train Agent

    Train the agent on the CartPole environment:

python

agent.train()

Step 4: Evaluate Agent

    Evaluate the trained agent:

python

agent.evaluate()

Step 5: Visualize Results

    Visualize the training and evaluation results:

python

agent.visualize()

## Conclusion

Congratulations! You have successfully completed the quick start guide for DI-engine with CartPole v1.0. Explore further customization options, experiment with different RL algorithms, and tackle more challenging RL problems using DI-engine.

For more information and advanced usage, refer to the official DI-engine documentation.

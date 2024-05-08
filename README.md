# Super Mario Bros Reinforcement Learning with A2C

## Overview

This repository contains code for training an agent to play the classic video game Super Mario Bros using the Advantage Actor-Critic (A2C) algorithm. The agent learns to navigate through the game environment and complete the specified level using reinforcement learning techniques.

## Dependencies

Ensure you have the following dependencies installed:

- `gym-super-mario-bros`: Provides the Super Mario Bros environment for OpenAI Gym.
- `stable-baselines3`: Library for reinforcement learning algorithms.

## Getting Started
- Create the Super Mario Bros Environment: Initialize the Super Mario Bros environment specifying the world and stage.
- Action Space Discretization: Use the SonicDiscretizer wrapper to convert the action space to discrete actions compatible with the A2C algorithm.
- Frame Stacking: Wrap the environment to handle vectorized input and stack frames for improved learning.
- Define and Train the A2C Model: Define an A2C model with a convolutional neural network policy and train it on the environment for a specified number of timesteps.
- Save the Trained Model: Save the trained model for future use or evaluation.
- Load and Evaluate the Trained Model: Load the saved model and evaluate its performance on the Super Mario Bros environment.
- Close the Environment: Ensure to close the environment after training or evaluation.

## Usage

Follow the provided code snippets to train and evaluate the A2C agent for playing Super Mario Bros. Customize the parameters and training settings as needed for your specific use case.

## Acknowledgments

This project utilizes the gym-super-mario-bros and stable-baselines3 libraries, which provide the Super Mario Bros environment and reinforcement learning algorithms, respectively.


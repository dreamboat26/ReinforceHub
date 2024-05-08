# BipedalWalker-V2 with PPO2

This Colab notebook allows you to train, evaluate, and visualize the results of a reinforcement learning agent using the Proximal Policy Optimization (PPO2) algorithm in the BipedalWalker-v2 environment.

The BipedalWalker-v2 environment is a challenging task where an agent must control a bipedal walker to move forward while avoiding falling or hitting obstacles.

## Usage

To run the entire notebook, select "Runtime" in the menu and choose "Run all".

## Components

1. **Setup Environment:** Import necessary libraries and set up the BipedalWalker-v2 environment.

2. **Define Helper Functions:** Define functions for training, evaluating, and visualizing results.

3. **Train the Agent:** Train the reinforcement learning agent using the PPO2 algorithm.

4. **Evaluate the Agent:** Evaluate the trained agent by running episodes in the environment and recording the results.

5. **Visualize Results:** Visualize the recorded video of the agent's performance.

## Note

Since rendering the environment directly in Google Colab is not supported, we use a workaround to record videos and display them. This might introduce slight delays or differences in rendering compared to a local environment.

## Acknowledgments

This notebook is based on the OpenAI Gym environment for BipedalWalker-v2 and the Proximal Policy Optimization (PPO2) algorithm. It is inspired by the Deep Learning Labs series.

## License

This notebook is provided under the MIT License. See the LICENSE file for details.

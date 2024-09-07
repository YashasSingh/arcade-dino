# Dino Game AI
![Video Project 1](https://github.com/user-attachments/assets/7ae95014-4655-4187-a0a0-42f15272954f)


This project demonstrates how to create an AI agent to play the Chrome Dino game using OpenAI's Gym environment and Stable-Baselines3. The AI model is trained using Deep Q-Learning (DQN) with the goal of maximizing the score by jumping over obstacles.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
  - [1. Install and Import Dependencies](#1-install-and-import-dependencies)
  - [2. Build the Environment](#2-build-the-environment)
    - [2.1 Create Environment](#21-create-environment)
    - [2.2 Test Environment](#22-test-environment)
  - [3. Train the Model](#3-train-the-model)
    - [3.1 Create Callback](#31-create-callback)
    - [3.2 Build DQN and Train](#32-build-dqn-and-train)
  - [4. Test the Model](#4-test-the-model)
- [Contributing](#contributing)
- [License](#license)

## Installation

To get started, clone the repository and install the required dependencies. Ensure you have the correct versions of Python and pip installed.

## Usage

### 1. Install and Import Dependencies

The project requires various dependencies including PyTorch, Stable-Baselines3, MSS, PyDirectInput, and PyTesseract. Make sure to install all necessary packages before proceeding.

### 2. Build the Environment

#### 2.1 Create Environment

Set up a custom Gym environment for the Chrome Dino game. This environment will handle the game's screen capture, action space, and observation space.

#### 2.2 Test Environment

Once the environment is created, test it by running a few episodes to ensure it functions correctly.

### 3. Train the Model

#### 3.1 Create Callback

Implement a callback function to monitor and save the model during training. This ensures that the best-performing models are stored for later use.

#### 3.2 Build DQN and Train

Initialize and train the DQN model using the environment. The model will be trained to maximize the score by learning the best actions to take in different situations.

### 4. Test the Model

After training, test the model by running it in the environment for several episodes. Observe its performance and track the total rewards.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License.

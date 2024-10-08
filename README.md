
# Snake Game with AI Agent

This repository contains a Snake game enhanced with an AI agent. The AI uses a Deep Q-Network (DQN) to learn and improve its gameplay over time. The game was developed using Python, Pygame for visualization, and PyTorch for the AI model.

## Features

- **Snake Game**: The classic Snake game where the player controls the snake to eat food and grow.
- **AI Agent**: The AI agent is implemented using a reinforcement learning algorithm (Deep Q-Learning) to play the game autonomously.
- **Training Visualization**: Live plotting of the AI's performance during training, including the scores and average scores over time.

## Requirements

To run the game and train the AI agent, you need to install the following dependencies:

```bash
pip install torch pygame matplotlib numpy
```

## How to Run

1. **Play Manually**: You can run the game in manual mode (without AI) using the following command:
    ```bash
    python snake_game.py
    ```

2. **Train the AI Agent**: To start training the AI to play the Snake game, run the following command:
    ```bash
    python train.py
    ```

The AI will continuously train itself by playing the game. The training process will automatically save the best model.

## Files Description

- `game.py`: Contains the implementation of the Snake game and its logic.
- `model.py`: Defines the AI model (a simple neural network) and the training process.
- `agent.py`: Implements the reinforcement learning agent that interacts with the game.
- `main.py`: The main file to start training the AI agent.
- `README.md`: This file.
- `LICENSE`: The license for this project.

## Training Visualization

Below is a plot of the scores and mean scores achieved by the AI agent during the training process.
<img width="668" alt="Screenshot 2024-10-08 at 3 10 14 AM" src="https://github.com/user-attachments/assets/1ed2ac55-80b6-4874-ac15-8f17654fb338">

<img width="638" alt="Screenshot 2024-10-08 at 3 10 22 AM" src="https://github.com/user-attachments/assets/4f0ce064-0e4f-410b-8e4f-b6af2e2ed43d">



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

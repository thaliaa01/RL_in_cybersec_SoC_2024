Stock Market Predictor using Reinforcement Learning

This project implements a  Q Learning Agent for stock trading. Q-Learning Algorithm is a reinforcement Learning Algorithm in which an agent picks up new information by observing results, interacting with the environment, and getting feedback in the form of rewards.

Methodology : The Q-learning algorithm forms the core of this project. Q-learning is a model-free RL algorithm that enables the agent to learn the best actions to take in a given state. The key components of the project include:

State Representation: The agent's state is represented by the price differences in a sliding window of closing prices. This representation allows the agent to capture relevant patterns in the stock price movements.

Action Space: The agent can take three actions - buy, sell, or hold - based on its current state and learned policy.

Reward System: The agent receives rewards based on the profit made from its actions. A successful trade results in a positive reward, while an unsuccessful trade leads to a negative reward.

Experience Replay: To improve learning efficiency, the agent stores its experiences and samples them randomly to train the model in batches.

Exploration vs Exploitation: Initially, the agent explores different actions to learn about the environment. As it gains experience, it shifts towards exploiting the best-known actions to maximize profit.

The agent's performance is evaluated based on the total gains and the percentage of investment returns. The plot generated shows the stock prices with the points where the agent decided to buy or sell.





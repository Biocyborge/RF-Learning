# Reinforcement Learning with Q-Learning Algorithms

This repository explores the concept of **Reinforcement Learning (RL)** using the **Q-learning algorithm**, implemented with the Python **NumPy** library. It includes two distinct projects that demonstrate the application of Q-learning in different environments:

## 1. **Tic-Tac-Toe: Win and Draw Probability Calculation**
   - **Overview**: This project uses Q-learning to train an agent to play Tic-Tac-Toe on a 3x3 board. The agent learns optimal strategies by exploring different moves and adjusting its policy based on rewards. The training process includes calculating and plotting the **win and draw probabilities** over thousands of episodes. 
   - **Key Features**:
     - The agent explores the state space and updates its Q-values based on the epsilon-greedy strategy.
     - The plot dynamically visualizes how the win and draw probabilities change as the agent learns over time.
     - It calculates the outcome probabilities as a function of **epsilon** (exploration vs. exploitation) to analyze its impact on learning efficiency.
  
## 2. **Optimal Path Finding on a Cartesian Grid**
   - **Overview**: This project applies Q-learning to find the optimal path in a Cartesian plane. The environment consists of a grid where an agent starts from a defined initial position and needs to find the most efficient path to a goal state while avoiding obstacles. A **reward system** is used to guide the agent towards the goal, and the optimal path is learned through interaction.
   - **Key Features**:
     - The agent learns the most efficient path by navigating the grid, receiving rewards for favorable actions and penalties for undesirable moves.
     - The process visualizes the agent’s learned policy and highlights the most efficient path in the Cartesian grid.
     - This project demonstrates how Q-learning can be applied to a navigation problem in a continuous environment.

## Technologies Used:
- **Python**
- **NumPy**
- **Matplotlib** (for plotting probability changes and visualizations)

## How to Use:
1. Clone the repository and navigate to the respective project directories.
2. Install dependencies by running:
   ```bash
   pip install -r requirements.txt
3. Run the Python scripts to train the agent and visualize the results.

## Contributions: https://github.com/sayakpaul/FloydHub-Q-Learning-Blog/blob/master/Q-Learning%20using%20numpy.ipynb

# Portfolio Optimization Using Reinforcement Learning

## Overview
This project applies Reinforcement Learning (RL) for optimizing financial portfolios. By simulating a stock market environment, we utilize Q-learning to determine optimal asset allocations, comparing the performance against traditional Markowitz optimization.

## Repository Structure
- `RLPortfolioOptimization.ipynb`: Jupyter notebook with the RL implementation and analysis.
- `RLPortfolioOptimization.pdf`: Comprehensive report detailing the methodology, findings, and implications.

## Getting Started
To run the Jupyter notebook:
1. Ensure you have Python installed, preferably via [Anaconda](https://www.anaconda.com/products/individual).
2. Install the required packages using `pip install numpy pandas scipy matplotlib`.
3. Open the notebook in Jupyter Lab or Jupyter Notebook by running `jupyter lab` or `jupyter notebook` in the terminal within the project directory.

## Key Components
- `PortfolioEnv`: A class representing the portfolio environment with stock returns and risk simulation.
- `Q-Learning Configuration`: Setup for the learning algorithm, defining exploration-exploitation trade-off and learning parameters.
- `Markowitz Optimization Model`: Functions to find the portfolio that minimizes variance for a given return.

## How to Use
Run the cells in `PortfolioOptimization.ipynb` sequentially to:
1. Initialize the environment and simulate returns.
2. Configure and run the Q-learning algorithm.
3. Perform Markowitz optimization.
4. Analyze and visualize the outcomes.

## Results
Our findings show that the RL agent can effectively learn and adapt its policy to achieve an optimal balance between risk and return. The comparative analysis with Markowitz's method reveals RL's potential to outperform in dynamically changing market conditions.

## Visualizations
- Allocation comparison between Q-learning and Markowitz methods.
- Cumulative returns of the final RL policy vs. Markowitz allocation.
- Evolution of the RL policy over training episodes.

## Acknowledgements
- Daniel Alpizar for the foundational work and report.
- References include "Machine Learning in Finance: From Theory to Practice" by Dixon, M.F., et al., and advanced data modelling literature by Swishchuk, A.

## Citation
Please cite this project as follows:

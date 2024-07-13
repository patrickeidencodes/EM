# EM 2024 Simulation

This project is a simulation for the UEFA European Championship 2024. It includes a simulator that simulates each minute of a match and generates data from it. This data is then used to train a model that decides whether the team deserves a loss, a draw, or a win based on their performance.

## Project Description

The main goal of this project is to create a realistic simulation of the matches in the EM 2024. The simulator provides minute-by-minute updates on the game, generating detailed performance data. This data is used to train a machine learning model that predicts the outcome of the match.

## Features

- **Minute-by-Minute Simulation**: Simulates each minute of a football match and generates performance data.
- **Data Generation**: Collects and organizes data from the simulation to be used for model training.
- **Outcome Prediction Model**: Uses the generated data to train a model that predicts whether a team deserves a win, loss, or draw based on their performance.

## Simulation Methods

There are two ways the EM 2024 is simulated:

1. **Simulator Only**: The EM is simulated directly without storing the data.
2. **Machine Learning Model**: The EM is simulated using a machine learning model trained with the generated data.

## Limitations

Due to time constraints, this project may be somewhat disorganized and contain redundant code.

## Technologies Used

- Python
- Machine Learning libraries (e.g., scikit-learn)
- Data processing libraries (e.g., pandas, NumPy)

## Setup

To set up and run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/patrickeidencodes/EM.git
   ```
2. Open the project in Pycharm or VScode
3. Run the last cells of the notebook simulating the EM

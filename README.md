# Vehicle-Maneuver-Evaluation

This repository contains code for training and testing a maneuver prediction and decision-making algorithm.
1. Data Preprocessing
   - Cleaned and preprocessed datasets of different driving maneuvers.
   - Prepared the data for training by organizing it into meaningful input features and labels.

3. Scenario Generation for Decision Making
   - Considered both the controlled vehicle and surrounding vehicles to simulate multiple maneuvering options.
   - Features include the relative longitudinal and lateral positions and speeds of surrounding vehicles.

5. Model Training

  - HMM (Hidden Markov Model):
    Trained for maneuver prediction using time-series features such as vehicle speed, longitudinal position, and lateral position.

  - Decision Tree:
    Trained for decision-making using relative information (longitudinal/lateral positions and speeds) of surrounding vehicles.

6. Algorithm Testing
  - tests to evaluate the performance of the proposed models for maneuver prediction and decision making.

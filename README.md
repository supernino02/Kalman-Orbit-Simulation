# DSIP Kalman Accuracy vs Uncertainty

This project simulates a spaceship gravitating around the moon in a dynamic non-linear system. The simulation introduces gravitational pull and synthetic noise to simulate real-world unpredictable external forces. 

The primary objective is to apply Kalman filter algorithms to estimate the true state (position, velocity, acceleration) of the spaceship from the noisy data, and to explore the balance between accuracy and uncertainty.

## Project Structure

Please refer to the docs/docs.md file for detailed information regarding the directory layout and the contents of each directory.

## Installation

1. Ensure Python 3 is installed.
2. Install the required dependencies using pip:
   `ash
   pip install -r requirements.txt
   `

## Running the Project

1. Navigate to the 
otebooks/ directory.
2. Open REAL_WORLD_SIMULATION.ipynb to run the mathematical and physical basis of the model. 
3. Open FINAL_PPRESENTATION.ipynb to see the results, the Kalman logic, and the generated comparative plots.
4. Execute the cells sequentially. 
> Note: The data outputs (like CSVs) will be generated in the ../data/ directory, and video renderings in the ../videos/ directory.

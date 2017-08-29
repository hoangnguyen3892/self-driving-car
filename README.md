# Self-Driving Car Simulation
This reporitory follows the instruction of [Siraj Raval](https://www.youtube.com/watch?v=EaY5QiZwSP4) ([Github](https://github.com/llSourcell/How_to_simulate_a_self_driving_car)).

## Directory structure:

```
self-driving-car
│   README.md
│   environments.yml
|   environment-gpu.yml
|   self-driving-car.ipynb: steps to simulate self-driving car
|   utils.py: utils for code in Keras
|   model.py: model built in Keras
|   drive.py: test built in Keras
| 
|--- pytorch
|

```

## How to run:
Follow this [kernel](https://github.com/llSourcell/How_to_simulate_a_self_driving_car/blob/master/self-driving-car.ipynb)

**Step 1:** Install dependencies

```python
# Use TensorFlow without GPU
conda env create -f environments.yml 

# Use TensorFlow with GPU
conda env create -f environment-gpu.yml
```
- To activate the environment:

```source activate car-behavioral-cloning```

**Step 2:** Generate data
- Download the simulator: https://github.com/udacity/self-driving-car-sim
- Open the app.
- Go to TRAINING MODE.
- Drive the car by using navigation buttons and record to get the data.

**Step 3:** Write Training script

**Step 4:** Train

**Step 5:** Write Testing script

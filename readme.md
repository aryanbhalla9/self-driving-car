# Self Driving Car using Behavioral Cloning

## Setup

1. Download the Term 1 [Udacity Car Simulator](https://github.com/udacity/self-driving-car-sim).
2. Create a conda environment with the required libraries.

```bash
 # Without GPU
 conda env create -f car-env.yml

 # With GPU
 conda env create -f car-gpu-env.yml
```

## Usage

1. Record Training data with the simulator
2. For Training a new model, run the [Behavioral Cloning](BehavioralCloning-Pytorch.ipynb) notebook
3. After training the model, you can run the `drive.py` script as

```bash
python drive.py models/model-10-plains.pth
```

### References

- https://devblogs.nvidia.com/deep-learning-self-driving-cars
- https://arxiv.org/abs/1604.07316v1
- https://github.com/udacity/CarND-Behavioral-Cloning-P3
- https://github.com/udacity/self-driving-car-sim
- https://github.com/naokishibuya/car-behavioral-cloning

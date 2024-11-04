# Twin-Delayed-Deep-Deterministic-policy-for-door-opening

**A Pytorch implementation of TD3 applied to controlling a Panda robot in Robosuite environments.**

Door Environment Render | Training Curve Example
:-----------------------:|:-----------------------:
<img src="https://github.com/your-username/td3-panda-robosuite/blob/main/images/door_render.gif" width="80%" height="auto">  | <img src="https://github.com/your-username/td3-panda-robosuite/blob/main/images/training_curve.png" width="80%" height="auto">

## Dependencies

```bash
gym==0.23.0
pybullet==3.2.6
matplotlib==3.8.2
tensorboard==2.15.1
robotsuite==1.4.0
termcolor==2.4.0
h5py==3.10.0
torch
torchvision
torchaudio
```
## Setup
### Clone the Repository
```bash
git clone https://github.com/your-username/td3-panda-robosuite.git
cd td3-panda-robosuite
```

## Install Dependencies
```bash
pip install -r requirements.txt
```
## How to use
### Train the Agent
To train the agent from scratch, simply run:
```bash
python main.py
```
The default environment is "Door" with a Panda robot.

## Test a Trained Model with Rendering
```bash
python test_with_render.py
```
## Visualize Training with TensorBoard
Install TensorBoard (if not already installed):
```bash
pip install tensorboard
```
Start Tensorboard
```bash
cd path/to/directory
tensorboard --logdir='logs' --port 6007
```
## Hyperparameter training
For more details on hyperparameter settings, please refer to main.py.

## Reference
TD3: Fujimoto S, Hoof H V, Meger D. "Addressing Function Approximation Error in Actor-Critic Methods." 2018.

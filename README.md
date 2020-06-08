1. Environment details

The environment involves an agent (a double-jointed arm), which goal is to maintain its position at a target location. For every step that the correct position is maintained, a reward of positive 0.1 is awarded. The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1. The environment is solved when the average rewards over 100 consecutive episodes is higher than 30.

2. Requirements

In order to run the project, Python3 and Unity ML-Agents are needed. Firstly, the python environment need to be set up according to this [guide](https://github.com/udacity/deep-reinforcement-learning#dependencies).

The project environment can be downloaded from the following links, depending on the OS used:
- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
- Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
- Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
- Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)

3. How to run the code?

The main file is represented by the jupyter notebook. Then, two additional Python files are imported in it. The code can be run by firstly running the seventh cell (which installs all the dependencies), then the eighth cell (in order to define the environment), then run the ninth cell (last one) for the main block.

References
The Udacity deep-reinforcement-learning repository was used for inspiration: https://github.com/udacity/deep-reinforcement-learning/tree/master/ddpg-pendulum. 

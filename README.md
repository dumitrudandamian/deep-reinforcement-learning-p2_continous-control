# deep-reinforcement-learning-p2_continous-control
This is the second project of the deep reinforcement learning course built by Dan Dumitru Damian - the countinous control

## Project Details

For this project I built and trained an actor-critic agent in the [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment 

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

The Benchmark Mean Reward is 30 over 100 episodes.

## Getting started

1. Download the project files from this GitHub repository into a local directory and create `env/` subfolder into it.

2. Download both **Version 1: One (1) Agent** and **Version 2: Twenty (20) Agents** environments for playing from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [**Version 1: One (1) Agent**](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip), [**Version 2: Twenty (20) Agents**](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
    - Mac OSX: [**Version 1: One (1) Agent**](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip), [**Version 2: Twenty (20) Agents**](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
    - Windows (32-bit): [**Version 1: One (1) Agent**](https://s3-us-west-1.amazonaws.com/udacitydrlnd/P2/Reacher/one_agent/Reacher_Windows_x86_32.zip), [**Version 2: Twenty (20) Agents**](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
    - Windows (64-bit): [**Version 1: One (1) Agent **](https://s3-us-west-1.amazonaws.com/udacitydrlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip), [**Version 2: Twenty (20) Agents**](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)
    
3. Place the file in the `env/` sub-folder, and unzip (or decompress) the file. 

## Instructions

1. Read the `Reporrt.ipynb` containing full desccription of all the steps built for training the agent. It can be used to run a from scratch training, and for this one the **Version 2: Two (2)** environment is needed.

2. Read and run the `Continous_Control.ipynb` to visualize a trained agent, based on the saved actor and critic NNs. For this one the **Version 1: One(1)** environment is needed.

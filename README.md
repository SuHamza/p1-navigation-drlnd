# Project 1: Navigation
## Introduction
In this project, an RL agent is trained to navigate and collect bananas in a large, square world.
<p align="center">
<img src="https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif" alt="Banana World!">
</p>

## The Environment
A reward of **+1** is provided for collecting a *yellow banana*, and a reward of **-1** is provided for collecting a *blue banana*. Thus, the **goal** of the agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The **state space** has **37 dimensions** and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. 

**Four discrete actions** are available, corresponding to:

* `0` - move forward.
* `1` - move backward.
* `2` - turn left.
* `3` - turn right.

The task is **episodic**, and in order to solve the environment, the agent must get an average score of **+13 over 100 consecutive episodes**.

## Instructions
1. Download the environment from one of the links below. You need only select the environment that matches your operating system:

    * Linux: [Click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    * Mac OSX: [Click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    * Windows (32-bit): [Click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    * Windows (64-bit): [Click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

  *(For Windows users)* Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

  *(For AWS)* If you'd like to train the agent on AWS (and have not enabled a [virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

2. Place the file in the main `p1-navigation-drlnd/` folder, and unzip (or decompress) the file.
3. Follow the instructions in `Navigation.ipynb` to get started with training your own agent!

## Project Files
- `Navigation.ipynb`: fully functional code for creating and training the agent.
- `README.md`: markdown file that describes the project environment details.
- `Report.pdf`: report that describes the learning algorithm, along with the chosen hyperparameters and the model architectures. In addition to a plot of rewards per episode and ideas for future work.
- `checkpoint.pth`: file with the saved model weights of the successful agent.

# Project 2: Continuous-Control

### Introduction

![Example](environment.gif)

For this project, we will train an agent to follow an object. 
You can check this [youtube-link](https://www.youtube.com/watch?v=ZVIxt2rt1_4) 

The environment cosist of 33 states, considering the posistion, rotation, velocity, and angular velocieties 
Each Action is Vector of 4 numbers, corresponding to force applied to two joints, each number is between -1 and 1
The Agent get a reward of +0.1 for each time the agent hand is on the target (object) 
This means the goal to keep the Agent hand on the target as many times as possible

The agent must get an average score of +30.0 over 100 consecutive episodes.

### Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

2. Place the file in the DRLND GitHub repository, in the `DRLN-Continuous-Contol/` folder, and unzip (or decompress) the file. 

### Instructions


## How to run the code
You could use the [insturction in the DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning#dependencies) to setup the Deep-Reinforcement-Leanring environment 

Which highlighting these steps
1. create a conda virenv ``` conda create -n drlnd python=3.6```
2. cd to the downloaded repo ``` cd /Download_path/DRLND-naviigation ``` ** 'Download_path' ** the location where you download the repo
3. activate the conda environment ``` conda activate drlnd ```
4. install the packages ``` pip install . ```
5. create IPython kernel ``` python -m ipykernel install --user --name drlnd --display-name "drlnd" ``` 
6. open jupyter-notebook in the root-directory and open Navigation.ipynb ``` jupyter notebook Navigation.ipynb ```
7. Execute the secions in the notebook

For more info about setting the environmet, please follow [the instructions in the DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning#dependencies)

Follow the instructions in `Continuous_Control.ipynb` to get started with training your own agent!  

## You can test the result by running the Test Section
By loading the weights for actor, and critic
then using these networks to for selecting the optimal action for the exisiting state

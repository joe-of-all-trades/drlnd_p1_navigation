This repository contains files for project 1 of deep reinforcement learning nanodegree. 

### Installing dependencies

1. clone the repository by `git clone `
2. create a new conda environment by `conda create -n drlnd python=3.6`
3. activate the newly created conda environment and cd into the folder named python of this repo, then do `pip install .`
4. create an IPython kernel for the drlnd environment by `python -m ipykernel install --user --name drlnd --display-name "drlnd"`


### Project environment

This project uses a simulator created with Unity as the environment for the RL agent. The environment allows four actions : forward(0), backward(1), left(2) and right(3). The state space of the environment has 37 dimensions, which represent the agent's velocity, and ray-based perception of objects around the agent's forward direction. A reward of +1 will given to agent when a yellow banana is collected. A reward of -1 will be given when blue banana is collected. 


### Running the script

All the code is contained in the single ipynb file named "drlnd_project1_navigation.ipynb". To run it, choose "Run all cells" from the tool bar of the jupyter notebook. If all the dependecies are correctly installed, a Unity environment window should pop up and you'll see the agent navigating the environment and collecting bananas. Toward the end of the script, model weights will be saved and the environment closed. 
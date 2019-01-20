# Reinforcement Learning - Actor Critic Method - Deep Deterministic Polict Gradient

Deep Deterministic Polict Gradient Actor-Critic Method is applied to solve collobaration and competition problem. Agent is trained to learn to coloobarate and compete.

## Environment Details
This is a tennis environment. 

In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,

After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.
This yields a single score for each episode.
The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.



## Setup

- **Clone the DRLND Repository**
    
    Follow the instructions in the DRLND GitHub repository [click here](http://github.com/udacity/deep-reinforcement-learning#dependencies)
    

- **Download the enviroment**
  
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)
   
   (_For Windows users_) Check out 
    [click here](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version     or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not 
    [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use 
    [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.
    
  - **Place Environment file in DRLND repository**  
    
      Place the downloaded file from the previous step in the DRLND GitHub repository, in the `p3_collab-compet/` folder, and           unzip (or decompress) the file. 

- **Clone this repository**
    
    Clone this repository in the DRLND GitHub repository
    
 ## Usage and structure
 
    - To train the agent run 'Collaboration and Competition_Solution.ipynb' file. 
    
    - 'ddpg_agent.py' - Interacts with and learns from the environment. Parameters can be modified in this file.
    
    - 'Model.py' is the policy model. Neural network architecture is defined here.


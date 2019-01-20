# Reinforcement-Learning---Collobaration-and-Competition
# Reinforcement Learning - Deep Q Network
Deep Q Network algorithm is applied to solve navigation problem in a gaming environment. Agent is trained to navigate the environment.

## Environment Details
Within the environment agent can navigate forward,backward, left and right. 
A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Four discreet actions are available.

## Setup

- **Clone the DRLND Repository**
    
    Follow the instructions in the DRLND GitHub repository [click here](http://github.com/udacity/deep-reinforcement-learning#dependencies)
    

- **Download the enviroment**
  
    Download the environment from one of the links below.  You need only select the environment that matches your operating       system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out 
    [click here](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version     or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not 
    [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use 
    [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.
    
  - **Place Environment file in DRLND repository**  
    
      Place the downloaded file from the previous step in the DRLND GitHub repository, in the `p1_navigation/` folder, and           unzip (or decompress) the file. 

- **Clone this repository**
    
    Clone this repository in the DRLND GitHub repository, the `p1_navigation/` folder 
    
 ## Usage and structure
 
    - To train the agent run the last section of 'Navigation' file. 
    
    - 'dqn_agent.py' - Interacts with and learns from the environment
    
    - 'Model.py' is the policy model. Neural network architecture is defined here.
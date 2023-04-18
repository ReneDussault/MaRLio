# MaRLio
## Mario's adventure with Reinforcement Learning

click [here](marlio.ipynb) to explore the notebook  

more documentation soon

### Deep Reinforcement Learning for Super Mario World and the potential of RL models in Nuclear Fusion

#### Project Overview
The main goal of this project is to use deep reinforcement learning (DRL) to train a model to play Super Mario World on the SNES.  
The project will demonstrate the ability of RL models to use data as inputs and learn to prevent bad outcomes (from the reward function).  
Additionally, the proposal will explore the potential of DRL models in controlling devices, more specifically in the context of nuclear fusion (to be seen).  

#### Data Description
The data for this project will come from the OpenAI Gym Retro environment, which provides an emulator (snes9x) for Super Mario World.  
The dataset consists of frames from the game, along with actions taken by the model and the corresponding rewards.  
The dataset will need to be preprocessed to extract features that are relevant to the DRL model.  

#### Methodology
The DRL model will be trained using the Proximal Policy Optimization (PPO from stable baselines 3) algorithm.  
The DRL model will be evaluated on its ability to complete different levels in the game.  

#### The timeline for completing the project is as follows:
Week 1: Collect and preprocess data for Super Mario World  
Week 2: Train and evaluate the DRL model on Super Mario World  
Week 3: Visualize the model's progress  
Week 4: Explore the potential of DRL in controlling the plasma for nuclear fusion  

#### Results Interpretation
The results of the Super Mario World model will be interpreted in terms of the average score achieved and the number of deaths.  
The interpretation of the results will be presented in a the jupyter notebook, which will include graphs and visualizations to make the results more interpretable.  
Also, videos will be made, to show the progress while training (learn) versus the progress after training (predict).  

#### Access to the code, model and videos
The trained PPO model will be provided alongside the jupyter notebook, as is, with instructions on how to load it.  
Links to popular video sharing platforms will be provided.  
Additionally, a dashboard cell will be provided at the beginning of the jupyter notebook to showcase the results of the project.  

#### Conclusion
The project will demonstrate the ability of DRL models to learn from data and prevent bad outcomes.  
The exploration of the potential of DRL in controlling a somewhat complex videogame environment will provide insights into how this technology can be applied in real-world scenarios.  
Overall, this project will showcase the potential of DRL in solving complex problems and preventing failures of complex systems.  

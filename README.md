# MaRLio
## Mario's adventure with Reinforcement Learning


[notebook](marlio.ipynb)  
[video](https://youtu.be/VJvW6f6e-Wo)  
[references](references.txt)  
[requirements](requirements.txt)  
[proposal](proposal.txt)  


I started this project big, by installing Ubuntu alongside Windows 10 (dual boot). Leveraging my AMD GPU with the ROCm package, I was able to achieve a 4x speed improvement in training. The journey wasn't easy, however. I had to troubleshoot and research for three days (see references) to get the ROCm package to work with my 6900xt GPU (not supported officially). I also had to work with outdated and unmaintained libraries, spending time debugging and troubleshooting to get them to work properly. This included rolling back Python to version 3.8 and modifying library scripts to fix bugs.  

Once the environment was set up, I explored it and created a wrapper for the action space to make it more user-friendly. I also pre-processed the environment by wrapping it in greyscale, framestacking, and vectorizing it with proper packages. I even found a way to generate the buttons the agent used and store them in a dictionary to generate an overlay (for the video, see link).  

Hyperparameter tuning was the next step, alongside the reward crafting, in order to get a successful behavior from the agent.  

Finally, I had to learn the basics of Davinci Resolve to produce a video for YouTube.  

This project showcases not only my technical skills and my ability to learn on the spot, but also my determination and problem-solving abilities.   

In conclusion, 
Reinforcement learning (RL) and deep reinforcement learning (DRL) have the potential to revolutionize a wide range of industries and applications. RL algorithms can learn to make decisions in complex environments with dynamic and uncertain conditions, making them well-suited for tasks such as control, optimization, and decision-making. DRL, in particular, has shown remarkable success in challenging domains such as robotics, game playing, and autonomous driving.  

In the future, RL and DRL could be used to improve healthcare by optimizing treatment plans for patients, reduce energy consumption by optimizing building operations, and even help to mitigate climate change by optimizing carbon emissions. Additionally, these techniques could be applied to create more efficient supply chain management, personalized education, and autonomous decision-making systems for finance and business.  

Deep reinforcement learning (DRL) has shown promise in the field of nuclear fusion, particularly in the area of plasma stabilization. In fact, researchers at Princeton Plasma Physics Laboratory (PPPL) have used DRL to control and stabilize the plasma in a fusion device [paper](https://pubs.aip.org/aip/pop/article/27/2/022501/1062589/Machine-learning-control-for-disruption-and) called the DIII-D tokamak. By using DRL algorithms to make real-time decisions, the researchers were able to improve plasma confinement and reduce the amount of energy lost to turbulence. This is a significant step towards achieving stable and efficient nuclear fusion, which could provide a nearly limitless source of clean energy.  

The potential applications of DRL in nuclear fusion and other fields are vast and exciting, and ongoing research in this area is likely to yield many more breakthroughs in the coming years. As research in RL and DRL continues to progress, we can expect to see more and more applications that will transform the way we live, work, and interact with technology.  

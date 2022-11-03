<!--# Safe RL 2022: The 1st International Workshop on Safe Reinforcement Learning Theory and its Applications

# The 1st Safe RL Workshop @ IEEE MFI 2022
-->

# <center>[The 1st Safe RL Workshop @ IEEE MFI 2022](https://saferl.online/2022/)</center>

<center>
The 1st international workshop on Safe Reinforcement Learning Theory and its Applications is co-located with the 2022 IEEE International Conference on Multi-sensor Fusion and Integration (MFI 2022). It will be held hybrid, the physical venue will be at Cranfield University in the United Kingdom, September 21, 2022.
</center>

# Workshop Motivation



<span style="float:right">Developing reinforcement learning (RL) algorithms that satisfy safety constraints are becoming increasingly important in real-world applications, which has received substantial attention in recent years. Many methods and algorithms have been proposed and developed for Safe RL, however, how to ensure safety during deploying RL methods in real-world applications and how to develop safe RL in the future still need further discussion. It’s necessary to organize the Safe RL Workshop and discuss how to address safe RL problems with researchers from academia and industry.</span>


<!--
<h1 style="text-align:right">
<p align="left">
Developing reinforcement learning (RL) algorithms that satisfy safety constraints are becoming increasingly important in real-world applications, which has received substantial attention in recent years. Many methods and algorithms have been proposed and developed for Safe RL, however, how to ensure safety during deploying RL methods in real-world applications and how to develop safe RL in the future still need further discussion. It’s necessary to organize the Safe RL Workshop and discuss how to address safe RL problems with researchers from academia and industry.
</p>
 </h1>
 -->
 
 # Topics of Interest
 - Safe reinforcement learning (including single agent and multi-agent RL)
- Metrics for safe real-world deployments
- Robust reinforcement learning
- Decision making under uncertainty
- Safe robot learning dataset, simulators, and benchmarks
- Robust perception, planning and control
- Uncertainty quantification
- Safety analysis and safety verification
- Transfer learning
- Sim2real transfer
- Embodied systems and safety-critical applications
- Explainability, transparency, and interpretability of learning
- Repeatability and reliability of learning-based control
- Safe multi-task learning and meta learning

# Speakers


Sergey Levine. He is currently an Associate professor in the Department of Electrical Engineering and Computer Sciences at UC Berkeley. His work focuses on machine learning for decision making and control, with an emphasis on deep learning and reinforcement learning algorithms. Applications of his work include autonomous robots and vehicles, as well as applications in other decision-making domains. His research includes developing algorithms for end-to-end training of deep neural network policies that combine perception and control, scalable algorithms for inverse reinforcement learning, deep reinforcement learning algorithms, and more. He received a BS and MS in Computer Science from Stanford University in 2009, and a Ph.D. in Computer Science from Stanford University in 2014. He joined the faculty of the Department of Electrical Engineering and Computer Sciences at UC Berkeley in fall 2016.
  
Talk Title: Safety in Reinforcement Learning by Leveraging Offline Data.
  
Talk Abstract: Reinforcement learning provides a powerful framework for learning-based decision making. However, running reinforcement learning methods in the real world requires handling safety challenges during exploration -- even if the final learned policy is safe and reliable, the learning process itself might involve unsafe behaviors. In this talk, I will describe how we can improve the safety of reinforcement learning methods by leveraging offline data: by providing the algorithm with prior data before online deployment, offline RL methods can infer which actions might lead to unsafe or unfamiliar situations, or even infer a distribution over potentially optimal policies, and then online reinforcement learning can be performed efficiently and in a way that avoids potentially unsafe and unfamiliar situations. I will cover Lyapunov density models, which bring in concepts from Lyapunov stability to provide task-agnostic safety constraints, and APE-V, a method that builds a posterior distribution over potentially optimal policies from offline data and then infers the most optimal hypothesis from online interaction.

[Video](https://www.youtube.com/watch?v=uvXb0P1knRw&t=4s)

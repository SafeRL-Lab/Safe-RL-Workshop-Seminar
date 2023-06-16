
&nbsp; 

# <div align=center>[Safe Reinforcement Learning Online Seminar](https://sites.google.com/view/saferl-seminar/home) </div>


In December 2022, we launched this long-term safe reinforcement learning online seminar. Every month, we will invite at least one speaker to share cutting-edge research with RL researchers and students (each speaker has about 1 hour to share his/her research). We believe that holding this seminar can attract more people's attention and promote the research of safe reinforcement learning. See [homepage](https://sites.google.com/view/saferl-seminar/home)

#### Get involved: We welcome the researchers and students who are interested in safe RL to join us! To receive relevant seminar information in time, please click the [link](https://forms.gle/RS2BiK8fwhH2WYyV8) to register.



&nbsp; 
&nbsp; 
&nbsp; 

***

&nbsp; 
&nbsp; 
&nbsp; 

# <div align=center>[The 1st Safe RL Workshop @ IEEE MFI 2022](https://saferl.online/2022/) </div>


 <div align=center>
 <img src="https://github.com/Safe-RL-Lab/Safe-RL-Workshop/blob/main/safe_rl_background.png" width="850"/> 
 </div>

&nbsp; 

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

### Talk Title: Safety in Reinforcement Learning by Leveraging Offline Data.

[Sergey Levine](https://people.eecs.berkeley.edu/~svlevine/). He is currently an Associate professor in the Department of Electrical Engineering and Computer Sciences at UC Berkeley. His work focuses on machine learning for decision making and control, with an emphasis on deep learning and reinforcement learning algorithms. Applications of his work include autonomous robots and vehicles, as well as applications in other decision-making domains. His research includes developing algorithms for end-to-end training of deep neural network policies that combine perception and control, scalable algorithms for inverse reinforcement learning, deep reinforcement learning algorithms, and more. He received a BS and MS in Computer Science from Stanford University in 2009, and a Ph.D. in Computer Science from Stanford University in 2014. He joined the faculty of the Department of Electrical Engineering and Computer Sciences at UC Berkeley in fall 2016.
  

  
**Talk Abstract**: Reinforcement learning provides a powerful framework for learning-based decision making. However, running reinforcement learning methods in the real world requires handling safety challenges during exploration -- even if the final learned policy is safe and reliable, the learning process itself might involve unsafe behaviors. In this talk, I will describe how we can improve the safety of reinforcement learning methods by leveraging offline data: by providing the algorithm with prior data before online deployment, offline RL methods can infer which actions might lead to unsafe or unfamiliar situations, or even infer a distribution over potentially optimal policies, and then online reinforcement learning can be performed efficiently and in a way that avoids potentially unsafe and unfamiliar situations. I will cover Lyapunov density models, which bring in concepts from Lyapunov stability to provide task-agnostic safety constraints, and APE-V, a method that builds a posterior distribution over potentially optimal policies from offline data and then infers the most optimal hypothesis from online interaction.

[Talk Video](https://www.youtube.com/watch?v=uvXb0P1knRw&t=4s)


### Talk Title: Trustworthy Reinforcement Learning.

[Ding Zhao](https://safeai-lab.github.io/people.html). He is currently an assistant professor in the Department of Mechanical Engineering at Carnegie Mellon University, with affiliation at the Computer Science Department and Robotics Institute. His research focuses on both the theoretical and practical aspects of trustworthy AI with applications on autonomous vehicles, intelligent transportation, assistant robots, healthcare diagnosis, and cybersecurity. He is the recipient of the National Science Foundation CAREER Award, George Tallman Ladd Research Award, MIT Technology Review 35 under 35 China Award, Ford University Collaboration Award, Carnegie-Bosch Research Award, Struminger Teaching Award, and industrial fellowship awards from Adobe, Bosch, and Toyota. He worked with leading industrial partners, including Google Brain, Ford, Uber, IBM, Adobe, Bosch, and Rolls-Royce. He is also a visiting researcher at Google Brain/Robotics.
  

  
**Talk Abstract**: In recent years, reinforcement learning has started shifting towards deployment on real-world problems. To this end, people pay more attention to the trustworthiness of reinforcement learning in addition to its performance on the targeted tasks. In this talk, I will give an overview of trustworthy reinforcement learning including three aspects: robustness, safety, and generalization. I will introduce taxonomies, definitions, methodologies, and popular benchmarks in each aspect. I will also share our recent work and lessons and our outlook for future research directions.

[Talk Video](https://youtu.be/PBtEllHoZG4)


### Talk Title: Certifiable Learning Machines.

[Michael Everett](https://mfe7.github.io/). He is currently a Visiting Faculty Researcher with Google’s People + AI Research (PAIR) team, he will be joining Northeastern University in January 2023 as an Assistant Professor, with a joint appointment in the Department of Electrical & Computer Engineering and the Khoury College of Computer Sciences. His research lies at the intersection of robotics, deep learning, and control theory, with the goal of developing certifiable learning machines. Previously, He was a Research Scientist and Postdoctoral Associate at the MIT Department of Aeronautics and Astronautics, working on the DARPA RACER program, the ARL SARA program, and advancing the field of certifiable learning. He received the PhD (2020), SM (2017), and SB (2015) degrees from MIT in Mechanical Engineering.
  

  
** Talk Abstract**: The talk will discuss the challenges of certifying the safety and robustness properties of machines that learn. I will describe our work that uses convex relaxations and set partitioning to simplify the analysis of highly nonlinear neural networks used across AI. These analysis tools led to the first framework for deep reinforcement learning that is certifiably robust to adversarial attacks and noisy sensor data. The tools also enable reachability analysis -- the calculation of all states that a system could reach in the future -- for systems that employ neural networks in the feedback loop, which provides another notion of safety for learning machines that interact with uncertain environments.

[Talk Vedio](https://youtu.be/CaBBSDjQ-zM)

### Talk Title: Decision Structure in Decentralized Multi-Agent Learning.

[Yali Du](https://yalidu.github.io/). She is a Lecturer at King’s College London and a member of the Distributed Artificial Intelligence Group. Prior to joining King’s, she was a postdoctoral research fellow at University College London. She obtained her Ph.D. from University of Technology Sydney in 2019. Her research interest lies in machine learning and reinforcement learning, especially in the topics of multi-agent learning, policy evaluation, and applications to Game AI, data science and wide decision-making tasks. Her research output has been widely published in prestigious venues including ICML, NeurIPS, ICLR, IJCAI, AAMAS, WWW, etc.
  

  
Talk Abstract: Many real-world problems, such as traffic light control, connected autonomous vehicles, and multiplayer games, can be naturally formulated into multi-agent learning problems. While centralized controllers are an off-the-shelf choice enabling the use of various existing reinforcement learning algorithms, a long-standing challenge is the scalability of the algorithms with exponential growing state-actions spaces with the number of agents. Especially in large scale multi-agent systems, centralized algorithms are hard to scale, and fully decentralized algorithms are favored. While in reality some decision makers might not be influenced by distant agents, such as in traffic lights, we are inspired to investigate the structure of multi-agents systems and understand how it will promote the design of better decentralized learning algorithms. In this talk, we will discuss factorizability of multi-agent systems including the transition dynamics and action coordinations, and propose novel fully decentralized multi-agent learning algorithms. Theoretically we find that the localized policy gradient is a close approximation to true policy gradients and provide the conditions for monotonic improvement under factorized model-based policy optimization. Empirically, we evaluate our algorithm on intelligent transportation systems, demonstrating the high sample efficiency and superior performance.

[Talk Vedio](https://youtu.be/KQp6C11x1z4)

### Talk Title: When are Offline Two-Player Zero-Sum Markov Games Solvable?

[Simon Shaolei Du](https://simonshaoleidu.com/). He is an assistant professor in the Paul G. Allen School of Computer Science & Engineering at University of Washington. His research interests are broadly in machine learning such as deep learning, representation learning and reinforcement learning. Prior to starting as faculty, He was a postdoc at Institute for Advanced Study of Princeton, hosted by Sanjeev Arora. He completed my Ph.D. in Machine Learning at Carnegie Mellon University, where he was co-advised by Aarti Singh and Barnabás Póczos. Previously, He studied EECS and EMS at UC Berkeley. He have also spent time at Simons Institute and research labs of Facebook, Google and Microsoft.
  

  
Talk Abstract: We study what dataset assumption permits solving offline two-player zero-sum Markov game. In stark contrast to the offline single-agent Markov decision process, we show that the single strategy concentration assumption is insufficient for learning the Nash equilibrium (NE) strategy in offline two-player zero-sum Markov games. On the other hand, we propose a new assumption named unilateral concentration and design a pessimism-type algorithm that is provably efficient under this assumption. In addition, we show that the unilateral concentration assumption is necessary for learning an NE strategy. Furthermore, our algorithm can achieve minimax sample complexity without any modification for two widely studied settings: dataset with uniform concentration assumption and turn-based Markov game. Our work serves as an important initial step towards understanding offline multi-agent reinforcement learning.

[Talk Vedio](https://youtu.be/wqNEm_Q1frU)

### Talk Title: Are robots safe for everyone? The intersection of safety and fairness in robot motion.

[Martim Brandao](https://www.martimbrandao.com/). He is an Assistant Professor in Robotics and Autonomous Systems, at King’s College London. His research focuses on planning, optimization, and vision algorithms for robotics - as well as issues of fairness, transparency and ethics in these algorithms. Previously, he was a post-doc at King’s College London (2019-2021), at the Oxford Robotics Institute, University of Oxford (2017-2019), and at Takanishi Laboratory, Waseda University, Tokyo (2016-2017). His PhD was advised by Atsuo Takanishi and Jose Santos-Victor.
  

  
Talk Abstract: Recently, much attention has been given to risks of AI in terms of bias and discrimination. In this presentation I will describe practical issues of fairness and disparate impact relating to the motion of robots (and thus RL). I will show how person detectors and motion planners, if left unchecked, can be safer or more beneficient to some people compared to others - and how this could raise concerns of fairness. The presentation will focus both on algorithmic audits and practical "fairness-aware" algorithm implementations.

[Talk Vedio](https://youtu.be/pJVh6gYyB9U)


### Talk Title: When Is Partially Observable Reinforcement Learning Not Scary?


[Chi Jin](https://sites.google.com/view/cjin/). He is an assistant professor at the Electrical and Computer Engineering department of Princeton University. He obtained his PhD degree in Computer Science at University of California, Berkeley, advised by Michael I. Jordan. His research mainly focuses on theoretical machine learning, with special emphasis on nonconvex optimization and reinforcement learning. His representative work includes proving noisy gradient descent escape saddle points efficiently and proving the efficiency of Q-learning and least-squares value iteration when combined with optimism in reinforcement learning.
  

  
Talk Abstract: Partially observability is ubiquitous in applications of Reinforcement Learning (RL), in which agents learn to make a sequence of decisions despite lacking complete information about the latent states of the controlled system. Partially observable RL is notoriously difficult in theory---well-known information-theoretic results show that learning partially observable Markov decision processes (POMDPs) requires an exponential number of samples in the worst case. Yet, this does not rule out the possible existence of interesting subclasses of POMDPs, which include a large set of partial observable applications in practice while being tractable. In this talk we identify a rich family of tractable POMDPs, which we call weakly revealing POMDPs. This family rules out the pathological instances of POMDPs where observations are uninformative to a degree that makes learning hard. We prove that for weakly revealing POMDPs, a simple algorithm combining optimism and Maximum Likelihood Estimation (MLE) is sufficient to guarantee a polynomial sample complexity. To the best of our knowledge, this gives the first line of provably sample-efficient results for learning from interactions in POMDPs. This is based on joint works with Qinghua Liu, Alan Chung, Akshay Krishnamurthy, Sham Kakade, and Csaba Szepesvari.

[Talk Video](https://youtu.be/G63kxCMBKxQ)


### Talk Title: Safe Reinforcement Learning with Model Order Reduction Techniques.

[Zhehua Zhou](https://www.ce.cit.tum.de/en/lsr/team/zhehua-zhou/). He is a Postdoctor at University of Alberta. His research focuses on safe reinforcement learning and control theory in robotics. He received the B.E. degree in mechatronics engineering from Tongji University, Shanghai, China, in 2014, and the M.Sc. degree in electrical and computer engineering from the Department of Electrical and Computer Engineering, Technical University of Munich, Munich, Germany, in 2017. He earned PhD degree from Technical University of Munich under the supervision of Professor Martin Buss, in 2022.
  

  
Talk Abstract: Although the state-of-the-art learning approaches exhibit impressive results for dynamical systems, only a few applications on real physical systems have been presented. One major impediment is that the intermediate policy during the training procedure may result in behaviors that are not only harmful to the system itself but also to the environment. In essence, imposing safety guarantees for learning algorithms is vital for autonomous systems acting in the real world. In this talk, we discuss a computationally effective safe reinforcement learning (SRL) framework for complex dynamical systems that is based on model order reduction (MOR) techniques. With a proper definition of the safe region, a supervisory control strategy, which switches the actions applied on the system between the learning-based controller and a predefined corrective controller, is given. A simplified system, found by either using physically inspired or data-driven MOR, formulates a low-dimensional safe region that approximates the high-dimensional safe region of the original dynamical system. To ensure the performance of the learning-based controller, the belief of the safe region is updated online by using the observed actual system's behavior. The proposed SRL framework leads to a safer learning process, and provides a possible solution to the challenging problem of how to safely apply learning algorithms in real-world scenarios.

[Talk Video](https://youtu.be/lmSSmBjsi10)

### Talk Title: Human-in-the-loop Safe Reinforcement Learning.

[Ilias Kazantzidis](https://www.linkedin.com/in/ilkaza/?originalSubdomain=uk). He is currently a third-year PhD student at the UKRI Centre for Doctoral Training in Machine Intelligence for Nano-Electronic Devices and Systems (MINDS) of the University of Southampton. He holds a Diploma in Electrical and Computer Engineering from the Democritus University of Thrace (2018) and an MSc in Artificial Intelligence from the University of Southampton (2020). His research is on Safe Reinforcement Learning, focusing on methods that use a human-in-the-loop.
  

  
Talk Abstract: Although reinforcement Learning is a powerful paradigm for agent sequential decision-making, it cannot be used in its traditional form in most real-world applications and particularly in safety-critical environments. Unrestricted exploration can lead to unsafe states or even catastrophic failures for the agent or in the environment due to the agent’s actions. Human feedback can enable an agent to learn a good policy while avoiding unsafe states, but at the cost of human time. In this talk, I will discuss Human-in-the-loop Reinforcement Learning methods, with the focus being on the safety of the agent and its environment. Then I will present a new model for safe learning from human input, which extends the standard technique of Learning from Human Preferences, and improves safety during training while limiting interaction with the user.

[Talk Video](https://youtu.be/f8PMr1fpZdM)







# Policy Gradient RL Algorithms as Directed Acyclic Graphs

Meta Reinforcement Learning (RL) methods focus on automating the design of RL algorithms that generalize to a wide range of environments. The framework introduced in [Anonymous, ICLR 2021](https://openreview.net/forum?id=0XXpJ4OtjW) addresses the problem by representing different RL algorithms as Directed Acyclic Graphs (DAG), and using an evolutionary meta learner to modify these graphs and find good agent update rules. While the search language used to generate graphs in the paper serves to represent numerous already-existing RL algorithms (e.g., DQN, DDQN), it has limitations when it comes to representing Policy Gradient algorithms. In this work we try to close this gap by extending the original search language and proposing graphs for different Policy Gradient algorithms.

### Vanilla Policy Gradient (VPG)

![alt text](https://github.com/jjgarau/DAGPolicyGradient/blob/master/graphs/VPG/vpg_pi.png?raw=true)

### Proximal Policy Optimization (PPO)

![alt text](https://github.com/jjgarau/DAGPolicyGradient/blob/master/graphs/PPO/ppo.png?raw=true)

### Deep Deterministic Policy Gradient (DDPG)

![alt text](https://github.com/jjgarau/DAGPolicyGradient/blob/master/graphs/DDPG/ddpg_phi.png?raw=true)

### Twin Delayed DDPG (TD3)

![alt text](https://github.com/jjgarau/DAGPolicyGradient/blob/master/graphs/TD3/td3_phi.png?raw=true)

### Soft Actor-Critic (SAC)

![alt text](https://github.com/jjgarau/DAGPolicyGradient/blob/master/graphs/SAC/sac_phi.png?raw=true)
# Cooperative Reinforcement Learning in Multi-Agent Scenarios

  Reinforcement learning has received great interest in the last decades as it suc-
ceeded in reaching and even surpassing human performance in various fields, especially
games like Go. In addition to these great breakthroughs, reinforcement learning is be-
coming very popular in the development of cutting-edge sector requiring autonomous
behaviors from machines like robotics and self-driving cars. Among the various fields
of RL, cooperative multi-agent RL, the area that puts together autonomous agent in
order to achieve collective goals, is gaining momentum. To the usual challenges of RL
like *exploration-exploitation*, MARL adds new challenges like coordination that makes
the learning task way harder.  
  
  After redefining key elements of SARL and MARL, the objective of this report
is to explain the progression in solving MAMDPs, from basic MARL algorithms and
sublinear-regret SARL algorithms to the problem of doing near-optimal learning in
multi-agent scenarios. After mentioning the main challenges of near-optimal learning
in MARL and the various approaches considered, we introduce the algorithm that we
designed, *Pessimistic Q-learning with exploration policies* that aims at computing the
max-Q functions. This algorithm is then tested in a challenging environment.

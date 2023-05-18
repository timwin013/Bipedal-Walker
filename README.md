# Solving OpenAI's BipedalWalker Using Reinforcement Learning
Video: https://youtu.be/5jdRPK0HmrI  
  
## Master 1 of 4
The results for an agent who behaves randomly in the Pendulum-v1, BipedalWalker-v3, and BipedalWalkerHardcore-v3 which form baselines to compare future results. It also contains DDPG implementation for Pendulum-v1 and BipedalWalker-v3. 
  
## Master 2 of 4
Implementation of TD3 for BipedalWalker-v3 with a hidden size of 128 and a batch size of 128.  
  
## Master 3 of 4
Implementation of TD3 for BipedalWalker-v3 with a hidden size of 64 and a batch size of 64. This agent is then tested on BipedalWalkerHardcore-v3. The agent is then trained on BipedalWalkerHardcore-v3 with hidden size of 64 and a batch size of 64 to ensure a reasonable runtime.  
  
## Master 4 of 4
Implementation of TD3 for BipedalWalkerHardcore-v3 with hidden size of 64 and a batch size of 64 to ensure a reasonable runtime. This allows comparison of the performance of an agent who learns to adapt from BipedalWalker-v3 to BipedalWalkerHardcore-v3 (Master 3 of 3) against an agent who learns BipedalWalkerHardcore-v3 from scratch (Master 4 of 4).

# Python-Cooperative-Synapse-NeuroEvolution

"Look ma, no gradients!" 

![](https://github.com/Hellisotherpeople/Python-Cooperative-Synapse-NeuroEvolution/blob/master/cooperative_neuroevolution.gif)


An implementation of a simple 3 layer ANN, which evolves it's weights using a Cooperative Coevolutionary method. 



Implemented with Numpy (and soon, PyTorch!) 

This algorithim was originally developed for Reinforcement learning. I wrote this on a hunch that this is *still* the State of the Art for fixed architecture networks. I (eventually) intend to showcase it on a task that it's actually good at (pole-balancing, certain types of game playing), but my main priority is getting it put onto the GPU - a considerably tougher task than anticipated.

If a GPU implementation isn't possible, than I will implement it in Numba and then attempt to use it to solve simple reinforcement learning problems... maybe flappybird? 



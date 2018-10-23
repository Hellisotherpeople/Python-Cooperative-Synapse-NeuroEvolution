# Python-Cooperative-Synapse-NeuroEvolution


![](https://github.com/Hellisotherpeople/Python-Cooperative-Synapse-NeuroEvolution/blob/master/ezgif.com-crop(1).gif)




An Implementation of this paper: [Accelerated Neural Evolution through Cooperatively Coevolved Synapses](https://pdfs.semanticscholar.org/966e/41903b4aff42601a188bd7b26d71ef120d11.pdf)

"Hey look, a reproducable paper!" 


![](https://github.com/Hellisotherpeople/Python-Cooperative-Synapse-NeuroEvolution/blob/master/CoSyne1.PNG)


![](https://github.com/Hellisotherpeople/Python-Cooperative-Synapse-NeuroEvolution/blob/master/CoSyne2.PNG)


![](https://github.com/Hellisotherpeople/Python-Cooperative-Synapse-NeuroEvolution/blob/master/CoSyne3.PNG)

"Look ma, no gradients!" 

![](https://github.com/Hellisotherpeople/Python-Cooperative-Synapse-NeuroEvolution/blob/master/cooperative_neuroevolution.gif)


An implementation of a simple 3 layer ANN, which evolves it's weights using a Cooperative Coevolutionary method. 



Implemented with Numpy (and soon, PyTorch!) 

This algorithim was originally developed for Reinforcement learning. I wrote this on a hunch that this is *still* the State of the Art for fixed architecture networks.  but my main priority is getting it put onto the GPU - a considerably tougher task than anticipated.

If a GPU implementation isn't possible, than I will implement it in Numba and then attempt to use it to solve simple reinforcement learning problems... maybe flappybird? 



# ResPSO

Forward passes through residual blocks are found to be equivalent to gradient descent steps. This leads to questions about more efficient residual blocks. 
This project explores the idea of modifying residual networks using the particle swarm optimization (PSO) algorithm. The ResPSO model architecture is introduced to achieve this.  This project tries to understand the effect of introducing PSO algorithms into residual blocks.

Different experiments like clustering and muting model compoonents, were designed as introspection techniques to examine the learning behaviour of the ResPSO model. As swarm’s particles
are modeled to be equivalent to feature maps, clustering these particles allowed exploration of PSO’s effectiveness in adding information to the residual block. Muting model components while training, helped in understanding the interaction between
the model components. Robustness was experimented with, as Gaussian noise introduction in input. 

The ResPSO model was compared to the classical Resnet model. ResPSO models are less accurate on test set than Resnet, but are more robust. Muting components and clustering experiments show that PSO is a useful
and integral part of the model. The ResPSO models can extract features like - background colour, object colour, object shape and object alignment.

---
layout: post
title: Overview
permalink: /overview/
---

**Date and time:** TBD <br>
The workshop will be held **virtually** following ICLR guidelines; for more information from ICLR 2021, please see the [ICLR conference website](https://iclr.cc/Conferences/2021).

## Why Deep Learning for Simulation <br>
Recently there has been a surge in interest in using **deep learning to facilitate simulation**, in application areas including physics [1], chemistry [2], robotics [3] and graphics [4].
We define simulation as the process of iteratively generating output of the next time step using the output of the previous time step as input starting from an initial condition.

To date, out of the 10 [most powerful supercomputers](https://www.olcf.ornl.gov/2019/01/17/a-sneak-peek-at-19-science-simulations-for-the-summit-supercomputer-in-2019/) in the world, 9 of them are used for simulations, spanning the field of cosmology, geophysics and fluid dynamics [5].
These applications not only demonstrate the importance of simulation as a methodology in sciences and engineering, but also reveal the tremendous time and space complexity of such real-world simulations.

Recent works have started to actively explore the potential of using deep learning to improve these highly important simulations in terms of accuracy and efficiency.
The goal is to use data-driven machine learning models to learn the underlying mechanism by which a given system evolves, such that it could predict the evolution over large number of time steps, and generalize to an unseen initial condition or extrapolate future evolution. 
So far these works have shown the promise to learn a variety of complex processes, such as graphics simulation [4], cosmology simulation [6], glassy dynamics [7] and generic partial differential equations [8]. 

## Application Domains <br>

Many different communities have realized the potential of using deep learning approach to learn simulation. Those communities include:
- Simulation for physics, such as simulations in particle physics, plasma physics and fluid dynamics [9, 10]. Initial conditions typically involve particle data, as well as electric and magnetic field data that interact with each other over time.
    
- Simulation is widely applied in chemistry, to understand structures of molecules. 
    For example, in quantum chemistry, given an initial geometric configurations of atoms, simulation is required to evolve the atom configurations to eventually achieve a lowest-energy state of a molecule [2].
    
- In robotics, learning a forward simulation model of the complex environment helped the agent perform better planning (model-predictive control) [3].
    
- Graphics is an important area to test the physical reasoning ability of a learned simulation model. Recent works have demonstrated the generalization ability of machine learning models to predict diverse graphics scenes consisting of fluid, rigid bodies and elastic bodies [4, 11].


The workshop will consist of contributed talks, contributed posters, and invited talks on a wide variety of methods and problems including but not limited to those in the abovementioned communities.
We encourage submissions that propose benchmarks and provide a standard evaluation strategy for performance comparison between existing methods for learning simulation.
The goal of this workshop is to encourage knowledge sharing and communication revolving around machine learning for simulation, across the variety of domains, and potentially create collaborations.

Should you have any questions, please reach out to us via email:<br>
[simdl2021@gmail.com](mailto:simdl2021@gmail.com)

### References
[1] P. Battaglia et al. Interaction networks for learning about objects, relations and physics. NeurIPS 2016. <br>
[2] K. T. Schütt et al. Schnet: A continuous-filter convolutional neural network for modeling quantum interactions. NeurIPS 2017.<br>
[3] A. Sanchez et al. Graph networks as learnable physics engines for inference and control. PMLR 2018.<br>
[4] A. Sanchez et al. Learning to simulate complex physics with graph networks. ICML 2020.<br>
[5] A Sneak Peek at 19 Science Simulations for the Summit Supercomputer in 2019 (from the Oak Ridge National Laboratory). <br>
[6] S. He et al. Learning to predict the cosmological structure formation. Proceedings of the National Academy of Sciences 2019.<br>
[7] V. Bapst et al. Unveiling the predictive power of static structure in glassy systems. Nature Physics 2020.<br>
[8] Z. Long et al. PDE-Net 2.0: Learning PDEs from data with a numeric-symbolic hybrid deep network. Journal of Computational Physics 2019.<br>
[9] R. Wang et al. Towards physics-informed deep learning for turbulent flow prediction. KDD 2020.<br>
[10] A. Mohan et al. Embedding hard physical constraints in convolutional neural networks for 3D turbulence. ICLR 2020 Workshop.<br>
[11] Y. Li et al. Learning compositional koopman operators for model-based control. ICLR 2020.<br>


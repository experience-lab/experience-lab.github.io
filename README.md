# The Internet Science Experience Lab

Welcome! This is a page for some interactive science/math visualizations/simulations I've written for the browser (these will likely not function on mobile). Below you will find some links. I plan to record some videos explaining how to use them.

## Dynamical Systems and Bifurcations

A dynamical system is composed of a space of configurations and a prescription for the time evolution of those configurations. One class of dynamical systems describes the configuration as a vector v in some n-dimensional vector space V and specifies the time evolution by giving a formula for the rate of change of v which looks like

<p align="center">
<img src="https://render.githubusercontent.com/render/math?math=\frac{dv}{dt} = f(v)">
</p>
  
where f is a function from V to V. It can be useful to picture f as a vector field on V, like the velocity field of some fluid. This equation then says that the system moves as would a mote in the flow. We can visualize this when n is small, even drawing the paths of several motes at once, which would represent the fate of several initial configurations simultaneously, and tracing out their streamlines, which represents the history of the configuration.

Here is an example with n = 2 and a particularly interesting flow f which depends on some parameters a,b,c. speed is a parameter

[Hopf bifurcation](https://experience-lab.github.io/hopf-bifurcation/)

<img width="598" alt="image" src="https://user-images.githubusercontent.com/6211319/137595742-a9562dc4-f0c3-4378-85a9-a02cc3a58231.png">


[Swallow tail bifurcation](https://experience-lab.github.io/swallowtail/)

[Fitzhugh-Nagumo model](https://experience-lab.github.io/FitzHugh-Nagumo/)

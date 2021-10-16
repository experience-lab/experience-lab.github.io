# The Internet Science Experience Lab

Welcome! This is a page for some interactive science/math visualizations/simulations I've written for the browser (these will likely not function on mobile). Below you will find some links. I plan to record some videos explaining how to use them.

##### Table of Contents  
[dynsystems](#dynsystems)

## Dynamical Systems and Bifurcations
<a name="dynsystems"/>

A dynamical system is a way of talking about a system evolving in time. It is composed of a space of configurations of the system and a prescription for the time evolution of those configurations. One class of dynamical systems describes the configuration as a vector v in some n-dimensional vector space V and specifies the time evolution by giving a formula for the rate of change of v which looks like

<p align="center">
<img src="https://render.githubusercontent.com/render/math?math=\frac{dv}{dt} = f(v)">
</p>
  
where f is a function from V to V. It can be useful to picture f as a vector field on V, like the velocity field of a fluid. This equation then says that the system moves as would a mote in the flow. We can visualize this when n is small, even drawing the paths of several motes at once, which would represent the fate of several initial configurations simultaneously, and tracing out their streamlines, which represents the history of the configuration.

Here is an example which was created using the Hopf bifurcation with the motes intially arranged as an evenly spaced grid. As the time progresses, they are caught up in the flow and pulled towards the circular eddy.

<p align="center">
<img width="686" alt="image" src="https://user-images.githubusercontent.com/6211319/137596260-adfe9cf7-8608-4118-ba0f-4bb99c52b391.png">
</p>

This circular eddy is called a limit cycle. In this case it is an attractive limit cycle, meaning nearby points are sucked into its orbit. Systems with attractive limit cycles exhibit spontaneous oscillation

[Hopf bifurcation](https://experience-lab.github.io/hopf-bifurcation/)



[Swallow tail bifurcation](https://experience-lab.github.io/swallowtail/)

[Fitzhugh-Nagumo model](https://experience-lab.github.io/FitzHugh-Nagumo/)

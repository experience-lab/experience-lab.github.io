## Dynamical Systems and Bifurcations

##### Table of Contents  

[Hopf Bifurcation](#hopfbifurc)

* [Hopf bifurcation](https://experience-lab.github.io/hopf-bifurcation/)

[Swallowtail Bifurcation](#swallowtail)

* [Swallow tail bifurcation](https://experience-lab.github.io/swallowtail/)

[Fitzhugh-Nagumo Neuron Model](#fitzneuron)

* [Fitzhugh-Nagumo model](https://experience-lab.github.io/FitzHugh-Nagumo/)

A dynamical system is a way of talking about a system evolving in time. It is composed of a space of configurations and a prescription for the time evolution of those configurations. One class of dynamical systems describes the configuration as a vector v in some n-dimensional vector space V and specifies the time evolution by giving a formula for the rate of change of v which looks like

<p align="center">
<img src="https://render.githubusercontent.com/render/math?math=\frac{dv}{dt} = f(v)">
</p>
  
where f is a function from V to V. It can be useful to picture f as a vector field on V, like the velocity field of a fluid. This equation then says that the system moves as would a mote in the flow. We can visualize this when n is small, even drawing the paths of several motes at once, which would represent the fate of several initial configurations simultaneously, and tracing out their streamlines, which represents the history of the configuration.

<a name="hopfbifurc"/>

### Hopf Bifurcation

Here is an example which was created using the Hopf bifurcation with the motes intially arranged as an evenly spaced grid. As the time progresses, they are caught up in the flow and pulled towards the circular eddy.

<p align="center">
<img width="686" alt="image" src="https://user-images.githubusercontent.com/6211319/137596260-adfe9cf7-8608-4118-ba0f-4bb99c52b391.png">
</p>

This circular eddy is an example of a limit cycle. In this case it is an attractive limit cycle, meaning nearby points are sucked into its orbit. Systems with attractive limit cycles exhibit spontaneous oscillation. For example, the air blown into a woodwind instrument or across a blade of grass excites a spontaneous oscillation of the reed and can be turned into music by tuning the resonant cavity of the instrument.

This phenomenon can be simplified by considering a fluid flowing in a plane perpendicular to an infinitely long cylinder. Here is a video from the American Physical Society's Gallery of Fluid Motion which nicely shows the progression from a steady flow to an oscillating flow:

<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/pW0JfEBE9h8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

Although the system has infinitely many variables (its configuration is itself a vector field) and displays intricate phenomena including turbulence, the transition from steady to oscillating can be understood in a two-variable model called the Hopf bifurcation. Transitions like these in dynamical systems are generally called bifurcations and the classification of bifurcations is a problem in topology.

[Here is the simulation of the Hopf bifurcation.](https://experience-lab.github.io/hopf-bifurcation/)

It is modelled with three parameters a, b, and c (real numbers).

* a is the tuning parameter of the bifurcation: when a <= 0, the system has a stable fixed point - every starting configuration eventually spirals into this stationary state. When a > 0, this fixed point becomes unstable and "emits" a stable limit cycle - almost every starting configuration will eventually join this oscillating cycle.
* b controls the sign and strength of circulation. It is 1 by default.
* c adds a constant velocity along the x axis. When c begins to overpower the circulation b, there are new bifurcations and the limit cycle can be destroyed.

<p align="center">
<img width="663" alt="image" src="https://user-images.githubusercontent.com/6211319/137603456-261dd4e1-dd95-41a3-a3d7-c695ccb69f22.png">
</p>

We can compactly express the time evolution equation by expressing the configuration (a point in the 2d plane) as a complex number z:

<p align="center">
<img src="https://render.githubusercontent.com/render/math?math=\frac{dz}{dt} = c %2b (a %2b i b) z - z |z|^2">
</p>



<a name="swallowtail"/>

### Swallowtail Bifurcation

* [Swallow tail bifurcation](https://experience-lab.github.io/swallowtail/)

<a name = "fitzneuron"/>

### Fitzhugh-Nagumo Neuron Model

* [Fitzhugh-Nagumo model](https://experience-lab.github.io/FitzHugh-Nagumo/)

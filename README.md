# Reactor Modelling using OpenMC

Nuclear Reactors can be modelled in different ways, these are characterized by a trade-off and compromise between *computational cost* and *accuracy* in modelling occurring phenomena. Point Kinetics, Diffusion Theory and Monte Carlo Simulations are three approaches for modelling the Core Neutronics.

OpenMC is a library that allows to apply the Monte Carlo method for neutronic simulations. The Monte Cralo method is based on the iterative generation of a pre-defined number of neutrons that are "thrown" into the system. Sampling some initial variables for the first neutron considered using a Monte Carlo logic, give the start to the simulations: several reactions like Scattering, Fission, Absorption and Leakage events occur (statistical approach) to the neutron considered, and we can descibe the life of this neutron. This procedure is applied to each single neutron and the final calculation considers all the neutrons to return a global set of results about the neutron flux, fission events, scattering events, and so on.

As reported on the [Official Website](https://docs.openmc.org/en/stable/), OpenMC is a *community-developed Monte Carlo neutron and photon transport simulation code* capable of performing fixed source, k-eigenvalue, and subcritical multiplication calculations on models built using either a *Constructive Solid Geometry* (CSG) or CAD imported representations. It supports both continous-energy and multigroup transport.

## Repository content:
As personal training and interest in learning how to use OpenMC for neutronics and core design applications, I use documentations, codes and example projects provided by OpenMC Website and GitHub repositories to carry out simple personal projects and exercises (e.g., Modelling assemblies in different geometries, modelling different fuel rods, modelling cores for different reactor types).

At this [link](https://github.com/openmc-dev/openmc/wiki/Example-Jupyter-Notebooks) OpenMC provides some examples of Model Building and Reactor Examples.


## Recommended publication for citing:
Paul K. Romano, Nicholas E. Horelik, Bryan R. Herman, Adam G. Nelson, Benoit Forget, and Kord Smith, *“OpenMC: A State-of-the-Art Monte Carlo Code for Research and Development”*, Ann. Nucl. Energy, 82, 90–97 (2015).

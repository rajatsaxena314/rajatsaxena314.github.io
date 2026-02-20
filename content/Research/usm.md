+++
title = "N-body Simulations of Dust Cloud Collapse in Star–Disk Systems"
summary = "Research Intern | Universitäts-Sternwarte München, Ludwig-Maximilians-Universität | March 2025 - October 2025"
draft = false
weight = 20
showtoc = false
+++

#### Research Intern | [Universitäts-Sternwarte München](https://www.usm.uni-muenchen.de/), Ludwig-Maximilians-Universität | March 2025 - October 2025

#### Mentor: [Dr Til Birnstiel](https://www.physik.lmu.de/en/about-us/people/contact-page/til-birnstiel-abb3ee27.html), Professor 

The N-body simulations were made using the Python package [REBOUND](https://rebound.readthedocs.io/en/latest/) 

- Developed and executed N-body simulations to investigate the gravitational collapse of a dust cloud in the presence of a central star and a pre-existing (collapsed) gas disk, focusing on the interaction between stellar gravity and disk-induced forces on gas drag. 

- Modeled coupled dust–gas dynamics during protostar formation by integrating particle trajectories with hydrodynamic fields, using snapshots from [Tarā](https://plg.physlab.uni-due.de/tara-database/) simulations to temporally and spatially interpolate local gas density, velocity, and temperature. This approach allowed for a faster computation of particle trajectories compared to hydrodynamics simulation performed in [2024, A&A, 687, A158](https://ui.adsabs.harvard.edu/abs/2024A%26A...687A.158B/abstract)

- Developed and implemented semi-implicit and exponential midpoint integrators in Python, inspired by [2019, ApJS, 244, 38](https://iopscience.iop.org/article/10.3847/1538-4365/ab4356). Executed simulations on an independently built codebase, achieving faster performance than REBOUND. Additionally, designed an epsilon-implicit integrator that allows the degree of implicitness to be adaptively controlled by the ratio of timestep to stopping time.

- Communicated complex research insights for a broader audience through Astrobites articles, summarizing the group’s findings in an accessible and engaging manner while maintaining scientific accuracy.   

#### Results:
![](/research/USM.png)
The plot shows dust particles initialized with different orbital conditions gradually losing vertical momentum due to gas drag and becoming embedded within the disk.

#### Material:

Avaliable: [Astrobites](https://astrobites.org/2025/08/26/build-a-planet-workshop-planet-formation-one-bump-at-a-time/)   
The code is avaliable at:
- [Collpase of Dust Cloud](https://github.com/rajatsaxena314/dusty-collapse)
- [Gas-Dust Dynamics based on Protostellar Hydrodynamics](https://github.com/rajatsaxena314/gas-drag-dynamics-with-hydrodynamic-snaphosts)
- [Custom Integrators](https://github.com/rajatsaxena314/Semi-Implicit-and-Exponential-Mid-Point-Integrators)
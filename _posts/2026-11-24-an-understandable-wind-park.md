---
layout: post
author: lanzieri
title: "An Understandable Wind Park"
---

At the TUHH Institute of Embedded Systems, [Franziska-Sophie Göttsch](/people/goettsch), [Mohammad Alkhiyami](/people/alkhiyami), [Leandro Lanzieri](/people/lanzieri) and [Görschwin Fey](/people/fey) are building a model wind park together with a group of students. The park should coordinate itself and be able to explain what it does.

Smart grids and transport networks are made of embedded devices that sense their surroundings, act on them and coordinate over a network. When such a system behaves unexpectedly, the people who operate and use it need to understand why. A wind park is a compact example, in which each turbine has its own controller, the turbines affect each other through their wakes, and a park controller coordinates them over a wireless network to feed the grid.

<img src="{{ '/assets/img/understandable-windpark-diagram.webp' | relative_url }}" class="img-fluid my-3" alt="Diagram of the wind park with turbine nodes, park controller and simulation.">

Every model turbine has an embedded node running [RIOT](https://www.riot-os.org/), which drives the rotor and turns the nacelle into the wind. A simulated wind field simulation runs alongside the hardware, and a central controller coordinates the turbines over the network.

<div class="row align-items-center my-3">
  <figure class="col-md-6 text-center">
    <img src="{{ '/assets/img/understandable-windpark-pcb.webp' | relative_url }}" class="img-fluid" alt="3D model of the turbine node PCB.">
    <figcaption class="small text-muted">Turbine node PCB</figcaption>
  </figure>
  <figure class="col-md-6 text-center">
    <img src="{{ '/assets/img/understandable-windpark-nacelle.webp' | relative_url }}" class="img-fluid" style="max-height: 400px;" alt="3D model of the turbine nacelle and rotor hub.">
    <figcaption class="small text-muted">Turbine nacelle and rotor hub</figcaption>
  </figure>
</div>

With the park we want to study **how turbines should be configured, how the park as a whole should behave, and whether the system can explain its behaviour using IoT protocols.** We will keep reporting on the progress and results!

## Further reading
- Görschwin Fey, Martin Fränzle, Rolf Drechsler. _Self-Explanation in Systems of Systems_. RE4ES, 2022. [doi:10.1109/REW56159.2022.00023](https://doi.org/10.1109/REW56159.2022.00023)
- Emmanuel Baccelli et al. _RIOT: An Open Source Operating System for Low-End Embedded Devices in the IoT_. IEEE Internet of Things Journal 5(6), 2018. [doi:10.1109/JIOT.2018.2815038](https://doi.org/10.1109/JIOT.2018.2815038)

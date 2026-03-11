---
layout: project
title: "MAE 3240 - Composite Wall Heat Conduction (Problem Set)"
date: 2026-03-10
icon: /assets/images/Cornell_Logo.png
image: assets/images/Cornell_Logo.png
---

### Reflection

This problem set assignment from MAE 3240 (Heat Transfer) was one of the most valuable exercises in building my physical intuition for one-dimensional conduction through composite systems. The problem centered on a two-wall system — Wall A with uniform volumetric heat generation and an insulated left boundary, and Wall B acting as a purely conductive layer between Wall A and a convective coolant. By working through the energy balance and applying Fourier's Law in each region, I had to carefully reason about what the temperature measurements at the two surfaces of Wall A actually tell us: the interface temperature T_i and the insulated-wall temperature T_w together encode both the heat flux leaving Wall A and the shape of the parabolic temperature profile driven by heat generation. Finding the right surface temperature T_s for Wall B, the volumetric generation rate q̇, and the thermal conductivity k_A all followed from applying the correct boundary conditions in the right sequence — a process that made the connection between the governing equations and measurable physical quantities very concrete.

What I found most useful about this assignment was how it reinforced the idea that every boundary condition tells a physical story. The insulated left wall means zero heat flux there, which fixes the symmetry of the temperature profile in Wall A and determines the direction all generated heat must flow. The no-contact-resistance condition at the A–B interface means the flux and temperature are continuous, linking the two sub-problems together into one coherent system. These kinds of reasoning steps — rather than just plugging into formulas — are directly applicable to real engineering problems involving thermal management of layered structures, such as circuit boards, heat exchangers, or insulated wall panels. This assignment gave me practice thinking through those steps systematically, which I expect to carry forward throughout the course and into future design work.

---

### Assignment PDF
<a href="{{ site.baseurl }}/assets/files/htUpload.pdf" target="_blank">📄 View Completed Assignment (PDF)</a>

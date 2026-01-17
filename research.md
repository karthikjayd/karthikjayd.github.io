---
layout: page
title: Research
permalink: /research/
---

# Research Experience

During my M.Sc. studies at the University of Freiburg, I took part in Quantum Computing research, focusing on Quantum Algorithms. In the past I have worked on topics such as Computational Physics, Astrophysics and Materials Physics (which also led to a [publication](#publications)). 

<!-- Key highlights -->
## Key Highlights
1. [Master's thesis work on Quantum Combinatorial Optimization at the Fraunhofer IAF, Freiburg, Germany](#master-thesis)
2. [Research assistant position on simuation of critical infrastructure networks on Quantum Hardware, Fraunhofer EMI, Freiburg, Germany](#emi-qc)
3. [Co-authored publication on study of physical parameters of Graphene forms](#publications)


## May 2024 – August 2025 {#master-thesis}
### Fraunhofer-Institut für Angewandte Festkörperphysik (IAF)
Completed the master's thesis titled *Classical v/s Quantum Optimization: Comparison of Runtime Scaling*, under PD Dr. Thomas Wellens and Vanessa Dehn. 

[Link to master's thesis full-text](https://github.com/aQuetzalcoatlus/kjayd-mthesis)

#### Abstract

> The study of algorithms for combinatorial optimization has been a central focus of quantum computing research in recent years. The primary goal in this field is to develop efficient algorithms based on quantum mechanical principles, that can outperform (or more realistically, complement) classical algorithms for solving NP-hard problems. Setting up problem instances in the Quadratic Unconstrained Binary Optimization (QUBO) model, this thesis aims to compare the performance of classical algorithms like CPLEX, Goemans-Williamson and MQLib against two variants of the Linear Ramp Quantum Approximate Optimization Algorithm (LR-QAOA) on two combinatorial optimization problems: the Maximum Cut Problem (MaxCut) and a new resource allocation problem from the energy provider EnBW
(which we refer to as the TA problem).

> The first variant of LR-QAOA, which we refer to as normalized Hamiltonian LR-QAOA,
sets up instance-agnostic parameters for the algorithm for all problem sizes, while the second variant, which we refer to as extrapolation LR-QAOA, determines suitable LR-QAOA parameters for each problem instance by heuristically extrapolating from smaller sub-instances.

> For both the classical and quantum algorithms, we investigate how the runtime of each of
the algorithms scales with the problem size for both problems, and how the solution quality compares across algorithms.

I worked on the implementation of the [Linear Ramp QAOA](https://arxiv.org/abs/2504.08577) for various combinatorial optimization problems, including the Maximum Cut Problem, Market Split and some specific industrial problems under the [Kompetenzzentrum Quantum Computing Baden-Württemberg (KQCBW)](https://www.iaf.fraunhofer.de/de/forscher/quantensysteme/quantencomputing/KQCBW24.html) project. 

During this period, I presented the LR-QAOA method at two conferences:
1. *Deutsche Physikalische Gesellschaft (DPG) Frühjahrstagung 2025* in Bonn, Germany, where I presented a talk titled [_"Quantum Optimization using Linear Ramp QAOA"_](https://www.dpg-verhandlungen.de/year/2025/conference/bonn/part/qi/session/12/contribution/2) for the Portfolio Optimization problem.
2. *KQCBW Developer Conference 2025* at Fraunhofer IAF, Freiburg, Germany, where I presented a poster on _"Energy grid optimization as a Linear Ramp QAOA use case"_.

I am further working on a publication that will include some of the results from my thesis, which will be submitted to a peer-reviewed journal in the near future.

## August 2023 – March 2024 {#emi-qc}
### Fraunhofer-Institut für Kurzzeit Dynamik, Ernst-Mach Institut (EMI)
Worked as a student research assistant (Hilfswissenschaftler or Hiwi) in the Risk Management and Structural Protection Department (_Abteilung Risikomanagement und Baulicher Schutz_). Assisted in developing a demonstrator for quantum-computing approaches to resilience analyses of network structures, under Dr. Christoph Brockt.

## May 16 – May 27 2022
### A.T.S.O.A. 2022, ARIES Nainital
Attended the ARIES Training School in Observational Astronomy 2022 ([more details](https://www.aries.res.in/atsoa2022/)), conducted by the Aryabhatta Research Institute of Observational sciencES (ARIES). Topics covered: telescopes, optical data-analysis techniques, star formation and evolution, and extra-galactic astronomy.

As part of this training school, I completed a project on _Data Reduction and Photometric Analysis of Blazars_. We analyzed image data of the MRK 501 blazar from the ARIES 1.3 m Devasthal Fast Optical Telescope (DFOT) using a BVRI Johnson–Cousins filter. Photometry (aperture photometry) yielded the blazar’s apparent magnitude and light curves. Pre-processing (image cleaning) was done with IRAF and DAOPHOT.


## October 2020 – December 2020
### Project Experience
Learned basics of Molecular Dynamics simulations using LAMMPS (Large-scale Atomic/Molecular Massively Parallel Simulator) while working on the project _“Stable amorphous system using Kob-Andersen type binary Lennard-Jones mixture with a Yukawa potential.”_  
*This project could not be completed due to health issues during the period.*


## May 2020 – August 2020
### Summer Project (Astronomy) {#IITB-orbits}
Developed a pipeline to compute the ephemeris of any heliocentric object given three observations of the object. It involved principles of celestial mechanics and numerical analysis. This project was preceded by tutorials on basic astrophysics covering topics like photometric image reduction, exoplanets, and gravitational waves.

In this project, I learned celestial mechanics and intermediate Python programming. I mastered NumPy, Matplotlib, SciPy, and AstroPy packages and became competent in collaborating via GitHub. Team communication was handled via Slack.


## February 2019
### Paper Presentation
Presented a paper on “Analysis of Electrical Parameters of Commercial SiC Schottky Power Diodes through Different Models” with Dr. Santosh Kumar (Asst. Prof. in Physics, Dept. of Education in Science & Mathematics, RIE Mysore) and Navya Jose (M.Sc.Ed.Physics, RIE Mysore) during National Science Day (NSD 2019) at RIE Mysore.

_Abstract published in the conference proceedings of NSD 2019._

---

# Publications {#publications}

## Extrapolation method to optimize linear-ramp quantum approximate optimization algorithm parameters: Evaluation of runtime scaling
(Article accepted to Physical Review A on 15 January 2026) 

**Co-author in upcoming revised version.** 
Vanessa Dehn, Martin Zaefferer, Gerhard Hellstern, **Karthik Jayadevan**, Florentin Reiter, and Thomas Wellens (2026). Extrapolation method to optimize linear-ramp quantum approximate optimization algorithm parameters: Evaluation of runtime scaling. 

- DOI: https://doi.org/10.1103/l5r4-zcqv

- *Older version available as arXiv preprint [arXiv:2504.08577](https://arxiv.org/abs/2504.08577)*

## Topological Data Analysis & Comparison of Physical Parameters of Different Forms of Graphene
Karthik, J., Jose, N., Kumar, M., & Somashekar, R. (2022). Topological data analysis and comparison of physical parameters of different forms of graphene. International Journal of Computational Materials Science and Surface Engineering, 11(2), 73-83

**Abstract:** Different crystallographic forms of graphene were investigated for their physical properties using reported experimental crystal-structure data and molecular-dynamics study. We find interesting changes in the values of certain physical parameters and three-dimensional spatial variations (Young’s, Linear and Shear moduli). The simulated strength of graphene in different forms was compared with experimental values to establish structure–property relations. Topological data analysis was carried out using a two-dimensional plot generated with Platon from CIF files of each graphene form.

Worked on this project from January to August 2021 under the guidance of Prof. R. Somashekar, University of Mysore.

**Article Published on:** 22 December 2022  
**DOI:** [10.1504/IJCMSSE.2022.10052084](https://doi.org/10.1504/IJCMSSE.2022.10052084)  
[Full article](https://www.inderscience.com/info/inarticle.php?artid=127980)

<!-- > **Update (31.04.22):** Reviewers’ comments received.  
> **Update (27.06.22):** Article accepted for publication. -->

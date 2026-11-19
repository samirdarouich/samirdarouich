# Samir Darouich

PhD researcher in AI for science at the [University of Stuttgart](https://www.uni-stuttgart.de/en/), advised by [Mathias Niepert](https://www.ki.uni-stuttgart.de/) (AI) and [Johannes Kästner](https://www.itheoc.uni-stuttgart.de/) (theoretical chemistry).

I build generative AI that predicts the 3D shapes of molecules, from stable structures to the short-lived states they pass through when they react. My work focuses on flow matching and diffusion models, in particular one-shot generation and physically inspired models that learn from the potential energy surface itself rather than from atomic coordinates alone.

I expect to finish my PhD in **June 2027** and I'm open to R&D roles in AI for science as well as postdoctoral positions.

[Website](https://samirdarouich.github.io) · [Google Scholar](https://scholar.google.com/citations?user=GDM6m9oAAAAJ) · [LinkedIn](https://www.linkedin.com/in/samir-darouich-529625b9/) · [Email](mailto:samir.darouich@ki.uni-stuttgart.de)

## Research interests

- Flow matching, diffusion models, and one-shot generative models
- Physically inspired and symmetry-aware generative modelling
- Generalization of generative models beyond their training data
- Generative modelling of molecular conformers, transition states, and chemical reactions
- Molecular simulation and machine learning with scarce data

## Selected research

### SymDrift: One-Shot Generative Modeling under Symmetries — NeurIPS 2026

Co-first-author work on symmetry-aware one-step generative modelling, enabling efficient generation for highly symmetric distributions such as molecular conformers and transition states.

[Paper](https://arxiv.org/abs/2605.06140) · [Code](https://github.com/samirdarouich/SymDrift)

### Robust Generative Transition-State Models for Unseen Chemistry — Nature Computational Science 2026

Work from my research stay in Heather Kulik's group at MIT, studying how well generative transition-state models generalize to chemistry outside their training data, and how pretraining on equilibrium structures makes them more robust.

[Paper](https://www.nature.com/articles/s43588-026-01034-5) · [Code](https://github.com/samirdarouich/RobustTSGen)

### Adaptive Transition-State Refinement with Learned Equilibrium Flows — JCIM 2026

A generative approach that refines rough transition-state guesses from machine learning models or fast approximate methods, improving their quality before quantum chemical optimization.

[Paper](https://doi.org/10.1021/acs.jcim.5c02902) · [Code](https://github.com/samirdarouich/AEFM)

### Curvature-Aware Flow Matching for Molecular Structure Generation — 2026

Flow matching supervised with the curvature of the potential energy surface, so that generated structures are physically consistent stationary points.

[Paper](https://arxiv.org/abs/2609.34592)

### ElemeNet: Multiscale Molecular Machine Learning across the Periodic Table — JCIM 2026

Co-first-author collaboration with the Kulik group at MIT on a turnkey machine learning framework with uncertainty quantification for elements across the periodic table.

[Paper](https://arxiv.org/abs/2606.30961)

## Background

I came to machine learning from chemical engineering, where I simulated molecules and materials with molecular dynamics and developed force fields. From this time, I built [MDSetup](https://github.com/samirdarouich/MDSetup), a tool to set up and run molecular dynamics simulations with LAMMPS or GROMACS from YAML configuration files ([documentation](https://samirdarouich.github.io/MDSetup)). My first contact with machine learning was parameterizing force fields from scarce experimental data. During an internship and working-student position at [BASF](https://www.basf.com/), I worked on molecular modelling for cement chemistry and corrosion protection.

## Academic service

- Reviewer: Nature Communications, JACS, NeurIPS, ICLR, and additional journals and conferences
- Instructor: seminar on Machine Learning for Science
- Teaching assistant: Advanced Theoretical Chemistry II, Technical Thermodynamics, and Advanced Engineering Mathematics
- Mentor for student research projects

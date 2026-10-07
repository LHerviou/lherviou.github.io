---
layout: page
title: Offers
subtitle: Here you will find offers to join my group.
---
**Currently:** I have one M2 internship position open. Nonetheless, Grenoble has regular open calls for postdoc and PhDs throughout the year, notably through [QuantAlps](https://quantalps.univ-grenoble-alpes.fr/). I am always happy to discuss them, whether you wish to work with me or someone else.

**Permanent:** Feel free to send me an email should you be interested in working with us, whether for internships or a PhD/postdoc position. If you are a student, please send me a brief email presenting yourself, including your CV, your grades of the previous year/semester and any reports you made for previous internships. I may ask for recommendation letters, but only after a first discussion.

**Important note:** due to administrative constraints, non-EU applications need to be done at two to three months before the beginning of the internship. Quantum research has become relevant to national security in France, so we have a lot of constraints enforced from above. For EU applications, administration is far less strict but at least a month is needed to set-up the contracts.

Below you can find the previous internships and positions I offered with my collaborators at LPMMC.


## ** 2026 - 2027 **
Please find below a M2 internship offer. See also on the [lab's website](https://lpmmc.cnrs.fr/en/m2-internship-tensor-network-methods-for-tight-binding-models-on-complex-lattices/)

## Tensor-network methods for tight-binding models on complex lattices

Tight-binding Hamiltonians are simple and versatile models of quantum matter. Beyond regular lattices, tight-binding models defined on complex geometries can show remarkably rich physical behavior. Among these, fractals and quasiperiodic lattices have historically played an important role in theoretical physics. Fractal lattices challenge the usual picture of topological phases, blurring the distinction between bulk and edge[1], while quasiperiodic models show unconventional localization with critical, multifractal eigenstates[2].
Tensor networks[3] have become a powerful tool for simulating quantum many-body systems. Ground states of gapped, local, one-dimensional Hamiltonians can be appro-ximated quasi-exactly at a cost polynomial in the number of degrees of freedom, and hence logarithmic in the Hilbert space dimension. Their use has recently been extended to a wide range of situations, including the representation of tight-binding Hamiltonians [4]. Combined with kernel polynomial methods, this approach gives the spectral functions of non-interacting models at a cost logarithmic in system size, for systems with billions of sites. We recently extended such constructions to a broad class of lattices with hierarchical structure, including fractal and quasiperiodic lattices [5].

The goal of this internship is to extend these approaches to more complex models and to study their properties. Depending on the student's interests, we propose two directions:
1) Topological states on fractal lattices. The student will implement topological models in this framework, including magnetic-flux, and then study localization and bulk-edge properties on different fractal lattices. 
2) Quasiperiodic models in one and two dimensions. Tensor models have shown promising results for large quasiperiodic systems based on Fibonacci chains. The internship will work on more complex two-dimensional substitution tilings. Beyond a direct generalization, we will also explore using categorical symmetries to represent the substitution rules.

Both directions will give the student insight into the physics of these systems and a good understanding of tensor networks and their links with finite automata, which will be useful for all their applications.

[1] Fremling, van Hooft, Smith and Fritz, Phys. Rev. Res. 2, 013044 (2020)
[2] Kohmoto, Sutherland and Tang, Phys. Rev. B 35, 1020 (1987)
[3] Schollwoeck, Annals of Physics 326, 96 (2011)
[4] Antão, Moustaj, Sun, and Lado, arXiv:2607.00991
[5] Brzezińska, Colbois and Herviou, arXiv:2609.25276

## ** 2025 - 2026 **
For 2025-2026, we had one postdoc opening, and we also took one student for a Master 2 internship.

## Postdoc opening: Tensor networks for the fractional quantum Hall effect
**Postdoctoral fellow:** [Tymoteusz Tula](https://scholar.google.com/citations?user=6xRtnqoAAAAJ&hl=en)

Our goal for this project is to develop tensor network methods, building upon existing libraries, to study general models of the fractional quantum Hall effect, with a focus on multi-orbital systems. Without entering into details, the first part of the project is the transfer of the libraries I codeveloped for ITensors, [ITensorInfiniteMPS](https://github.com/ITensor/ITensorInfiniteMPS.jl), to TensorKit. Our goal will be to incorporate the non-Abelian symmetries often present in the new FQHE platforms (think SU(2) spin symmetries, or emerging SU(4) in graphene) directly at the tensor level, in order to dramatically decrease the complexity of all computations.
We are also working on simulations for cold atoms experiments, as a theoretically simpler playground. \
Financed by ANR JCJC ANR-25-CE30-2205-01.

##  Efficient representations of Sp(N) and SO(N) spin chains 
**Codirector:** [Pierre Nataf](https://lpmmc.cnrs.fr/annuaire/?lpmmc_name=nataf) \
**Master student:** [Mathias Godefroi](https://lpmmc.cnrs.fr/annuaire/?lpmmc_name=godefroi)

Large-spin models have recently gained significant attention due to experimental breakthroughs in cold atom systems. These setups enable highly controlled experiments that simulate complex theoretical models. However, large-spin models present considerable challenges for numerical modeling. The large spin dimensions and intricate symmetries of these systems make simulations extremely difficult, and standard methods often fall short, failing to access certain experimental regimes of interest. 

In this context, an alternative approach based on advanced group theory concepts was recently proposed by one of the project supervisors[1,2]. It avoids the traditional bottleneck of computing Clebsch-Gordan coefficients by directly implementing the SU(N) algebra in its most efficient mathematical basis: the basis of (semi-)standard Young tableaux (SYT). This breakthrough has already enabled simulations of systems at unprecedented scales with an exact implementation of all symmetries. 

This internship aims to explore and extend this new framework. The successful candidate will investigate one of the following research avenues, according to their interests and skills: 1) generalization to other symmetry groups. 2) Monte-Carlo/machine learning simulations of SU(N) models. 


## ** 2024 - 2025 **
For spring/summer 2025, I proposed two master internships (M2) in condensed matter theory, cosupervised by two colleagues at LPMMC. We has an additional M1 internship on similar subjects.

## Numerical simulations of SU(N) spin chains and ladders
**Codirector:** [Pierre Nataf](https://lpmmc.cnrs.fr/annuaire/?lpmmc_name=nataf) \
**Master student:** Elodie Campan

Large-spin models have recently gained significant attention due to experimental breakthroughs in cold atom systems. These setups enable highly controlled experiments that simulate complex theoretical models. However, large-spin models present considerable challenges for numerical modeling. The large spin dimensions and intricate symmetries of these systems make simulations extremely difficult, and standard methods often fall short, failing to access certain experimental regimes of interest. 

In this context, an alternative approach was recently proposed by one of the project supervisors. This method bypasses the calculation of Clebsch-Gordan coefficients, thereby overcoming the limitations of traditional approaches. Given its demonstrated potential, there are now several promising avenues for further development. The proposed internship will explore these avenues in multiple stages. Initially, the student will delve into group theory, with a particular focus on SU(N) group representations, which are crucial for modeling large-spin systems. A solid grasp of these concepts is essential for the later stages of the project.

Subsequently, the student will implement a numerical method (exact diagonalization) to model quantum systems with high accuracy. Several theoretical models are under consideration, including variants of Heisenberg chains and ladders, where analytical approaches fail to provide clear predictions.

Finally, with a view towards continuing in a PhD, the student will explore tensor network methods. These have become one of the most powerful and efficient tools for modeling low-dimensional quantum systems. Tensor networks are particularly well-suited to simulating one-dimensional systems like spin chains, offering unmatched precision in capturing their fundamental properties. Our goal is to adapt existing algorithms to integrate this new computational approach.

## Exploring Spin-Orbit Coupling in Quantum Hall Systems
**Codirector:** [Thierry Champel](https://lpmmc.cnrs.fr/annuaire/?lpmmc_name=champel) \
**Master student:** [Sarah Mevel](https://lpmmc.cnrs.fr/annuaire/?lpmmc_name=mevel)

The quantum Hall effect (QHE) has long been a key area of research in condensed matter physics, exemplifying the role of topology in quantum mechanics. In QHE systems, the Hall conductance becomes quantized with significant applications in quantum metrology. The fractional quantum Hall effect, which arises due to electron-electron interactions, leads to the creation of exotic quasi-particles with fractional charge and statistics that are neither fermionic nor bosonic.

Recent experimental progress [1] has unveiled numerous fractional Hall plateaus, particularly in bilayer systems like graphene or double quantum wells. These bilayer structures introduce new complexities [2] due to strong interlayer interactions. Spin-orbit coupling can also be present – or engineered – in these materials. The spin-orbit coupling complicates the traditional picture of spin being a good quantum number and alters the nature of the QHE states [3]. Near Landau level crossings, these effects are further amplified, leading to rich and intricate physics [4] that demands theoretical attention.

This internship project will focus on the effects of spin-orbit coupling on integer QHE systems. It will begin by analyzing how spin-orbit coupling modifies the wavefunctions and edge states of non-interacting electrons in a single Landau level in the presence of trapping potentials. The second phase will consider Landau level crossings effects in bilayer structures and address electron interactions through a mean-field Hartree-Fock approach. Combining both analytical and numerical work, this research will contribute to a better understanding of topological phases. Long-term (PhD) goals include extending this analysis to study transport and disorder effects, light-matter coupling to a QED cavity, or a more precise numerical treatments of interactions to study fractional phases.

[1] K. Huang et al, Phys. Rev. X 12, 031019 (2022) \
[2] E. McCann et al, Rep. Prog. Phys. 76 056503 (2013) \
[3] Y. Xing et al., Phys. Rev. B 77, 114346 (2008) \
[4] P. Nataf et al., Phys. Rev. Lett. 123, 207402 (2019)

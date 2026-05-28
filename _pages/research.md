---
layout: page
title: Current Research
permalink: /research/
description:
nav: true
nav_order: 2
---

<style>
p {
text-align: justify;
}
</style>

## Mathematical & Computational Finance


**Markets as Markov State Spaces: Greeks, Stochastic Flows, and Reinforcement Learning**

This research programme proceeds from a single theoretical observation: by the Feynman-Kac representation and Kunita's differentiability of stochastic flows, option Greeks are intrinsic properties of the Markov pricing semigroup, and the Malliavin calculus of Fournié et al. establishes that every Greek admits a path-functional representation determined entirely by the process dynamics. The cross-section of Greeks across strikes and tenors therefore constitutes a rich encoding of the current Markov state, a claim supported empirically by Ross's recovery theorem and Aït-Sahalia, Li and Li's finding that implied volatility surface shape characteristics encode the coefficient functions of the underlying process. From this foundation, we are then to apply classification to identify distinct Markov market states, and test the Markov property of the resulting state sequence empirically. Where the Markov property holds, the continuous-time reinforcement learning framework of Jia and Zhou is applied to approximate the optimal stochastic control policy within those states, interrogating the learned value function as an approximation to the Hamilton-Jacobi-Bellman solution and recovering the economic architecture of optimal behaviour across market states. Where it does not, Zhang's neural rough differential equation approach extends the analysis to path-dependent settings, and their policy gradient convergence results establish that near-optimal policies remain recoverable in either case. Beyond its theoretical contributions, the framework carries direct practical implications from a data-driven state representation of the derivatives market in tandem with a greater understanding of its underlying architecture. 

---

## Computational Neuroscience


**Modelling Pain Chronification: A Stochastic Landau-Ginzburg Approach**

*In collaboration with Caitlyn Mary Dyster [King's College London].*

Pain chronification affects 20–30% of acute pain patients yet lacks a unified mathematical framework integrating its neurobiological, psychological, and environmental determinants into actionable clinical guidance. This research programme addresses that gap through a systematic progression from theoretical foundation to computational demonstration to empirical validation. A systematic review of chronification determinants motivates a stochastic Landau jump-diffusion model in which a latent pain state evolves in a quartic bistable potential under discrete perturbations whose frequency and severity are governed by separable environmental and inherent patient propensity variables. The mathematical properties of this system — survival equations, Bellman representations, and timescale-separated control structure distinguishing short-term symptomatic intervention from long-term neuroplastic restructuring — are derived rigorously. Simulation studies are then to investigate whether reinforcement learning can successfully optimise intervention policy within this framework, with learned policies proven clinically interpretable across the propensity space. Finally, the framework will be grounded empirically using longitudinal clinical cohort data, with latent variables operationalised from observable measurements, model parameters estimated, and reinforcement learning-derived treatment recommendations assessed for clinical plausibility. The result is to be a principled, end-to-end mathematical basis for personalised, dynamically optimised chronic pain prevention, bridging stochastic dynamical systems theory, computational reinforcement learning, and clinical pain medicine.


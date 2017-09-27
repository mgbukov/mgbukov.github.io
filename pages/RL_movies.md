---
layout: page
title: Reinforcement Learning in Phases of Quantum Control
permalink: ../RL_movies/
---

On this page, you can find the supplementary videos to the paper [Reinforcement Learning in Phases of Quantum Control](https://arxiv.org/abs/1705.00565) <span style="color:blue">[1]</span>. 

For the single qubit, we present three movies showing protocols found by the Reinforcement Learning (RL) agent (Movies 1-3) and three moves for the one-parameter variational protocols (Movies 4-6) for ramp durations $T=0.5, 1.0, 3.0$, respectively. The target state on the Bloch sphere is shown in red, while the instantaneous state - in green. The protocol time step size is $\\delta t=0.5$. 

The final two movies show the learning dynamics in for a single qubit for $T= 2.4$ (Movie 7), and a ten coupled qubit system for $T=4.0$ (Movie 8).


* __Single qubit protocols learned by the RL agent__. Movies 1-3 show the protocols found by the RL agent for a single qubit for protocol durations of $T=0.5, 1.0, 3.0$, respectively: [Movie 1]({{ site.baseurl }}{% link movies/RL_paper/Movie-1.mp4 %}), [Movie 2]({{ site.baseurl }}{% link movies/RL_paper/Movie-2.mp4 %}), [Movie 3]({{ site.baseurl }}{% link movies/RL_paper/Movie-3.mp4 %}).

* __Single qubit variational protocols__. Movies 4-6 show variational protocols inspired found by the RL agent for a single qubit for protocol durations of $T=0.5, 1.0, 3.0$, respectively: [Movie 4]({{ site.baseurl }}{% link movies/RL_paper/Movie-4.mp4 %}), [Movie 5]({{ site.baseurl }}{% link movies/RL_paper/Movie-5.mp4 %}), [Movie 6]({{ site.baseurl }}{% link movies/RL_paper/Movie-6.mp4 %}).

* __Learning dynamics__. Movies 7-8 shows the learning dynamics of the single qubuit with $T=2.4$ and ten coupled qubits with $T=3.0$, respectively. The reward in the manybody Movie 8, $\tilde F_h(T) = 1 + 1/L\log F_h(T)$, can be thought of as the fidelity per site: [Movie 7]({{ site.baseurl }}{% link /movies/RL_post/qubit.mp4 %}), [Movie 8]({{ site.baseurl }}{% link /movies/RL_post/many_qubits.mp4 %}).

*References*:\\
<a href="https://arxiv.org/abs/1705.00565" style="color: #0000cd">[1] M. Bukov, A.G.R. Day, D. Sels, P. Weinberg, A. Polkovnikov, P. Mehta, *arXiv: 1705.00565* (2017).</a>

Copyright © 2017 Marin Bukov
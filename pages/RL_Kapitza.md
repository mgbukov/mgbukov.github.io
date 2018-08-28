---
layout: page
title: Reinforcement Learning to Invert the Kapitza Oscillator
permalink: ../RL_kapitza/
---

On this page, you can find supplementary videos to the paper [Reinforcement Learning to Autonomously Prepare Floquet-Engineered States: Inverting the Quantum Kapitza Oscillator](https://arxiv.org/abs/1808.08910) <span style="color:blue">[1]</span>. 

The movies below show three stages of time evolution: 
* (i) the oscillator is subject to the control field in the presence of the Floquet drive. The arrow direction indicates the direction of the horizontal control kick.
* (ii) Once the control stage is over, the Floquet-drive is kept on but the control field is turned off.
* (iii) Both the Floquet drive and the control are turned off, and the system evolves under the free oscillator Hamiltonian $H_0$, see [paper](https://arxiv.org/abs/1808.08910). 

[Movie 1]({{site.baseurl}}../movies/RL_kapitza/movie-1.mp4) shows the real-space probability distribution of being in the target state for the ___quantum Kapitza oscillator___, following the best-encountered RL protocol. The control process takes $N_T=15$ drive cycles, and the drive protocol contains $8$ steps per cycle. The oscillator parameters are $N_T=15$ periods with $8$ steps each, $\Omega/\omega_0=10$, $A=2$ and $m\omega_0=1$. 

[Movie 2]({{site.baseurl}}../movies/RL_kapitza/movie-2.mp4) shows the real-space probability distribution of being in the target state for the ___quantum Kapitza oscillator___, following the best Stochastic Descent protocol. The control process takes $N_T=15$ drive cycles, and the drive protocol contains $8$ steps per cycle. The oscillator parameters are $N_T=15$ periods with $8$ steps each, $\Omega/\omega_0=10$, $A=2$ and $m\omega_0=1$. 

[Movie 3]({{site.baseurl}}../movies/RL_kapitza/movie-3.mp4) shows the ___classical Kapitza pendulum___ dynamics, following the best-encountered RL protocol. The control process takes $N_T=4$ drive cycles, and the drive protocol contains $8$ steps per cycle. The pendulum parameters are $N_T=4$ periods with $8$ steps each, $\Omega/\omega_0=10$, $A=2$ and $m\omega_0=1$. 


*References*:\\
<a href="https://arxiv.org/abs/1808.08910" style="color: #0000cd">[1] **M.B.**, *arXiv: 1808.08910* (2018).</a>

Copyright © 2018 Marin Bukov
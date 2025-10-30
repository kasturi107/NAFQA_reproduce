In this work, we present a method for simulating the dynamics of open quantum systems on a quantum computer, including negative dissipation rates in the Gorini-Kossakowski-Sudarshan-Lindblad master equation. Using this method, we develop a quantum algorithm for calculating ground-state properties that exploits feedback-controlled, noise-assisted dynamics. In this scheme, Lyapunov-based feedback steers the system toward a target virtual state under engineered noise conditions. Furthermore, motivated by recent experiments, we propose a protocol to experimentally realize our approach, combining noise-learning and quantum error mitigation techniques.

In summary, we propose a novel approach to dynamically engineer controlled dissipation to determine ground-state properties at the end of the protocol. Through numerical simulations, we demonstrate that our protocol can calculate observables at a faster rate than noisy and ideal closed-system simulations. While noisy simulations typically fail to converge and degrade in performance as noise accumulates over time, our method exhibits an improved convergence, albeit with an increased sampling overhead. As other error mitigation strategies, our approach has an exponential overhead in certain parameters, and its applicability is limited to physical scenarios with a low number of decay channels.


Requirements: 
Please create an environment and download all the requirements with the command: 
```python -m pip install -r requirements.txt```

Files:


References:
Kasturi Ranjan Swain, Rajesh K. Malla, and Adolfo del Campo, "Noise-Assisted Feedback Control of Open Quantum Systems for Ground State Properties", https://arxiv.org/abs/2510.18984.

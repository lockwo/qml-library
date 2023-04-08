# Quantum Machine Learning (QML) Library

A curated list of papers, blogs, and research publications in the field of Quantum Machine Learning. Inspired by the no longer updated: https://github.com/ericardomuten/qml-vqa-library. Open a PR if you want to add to it! All links should be to open access publications. If the published version is not open access, then it will link to arXiv. If the publication is not open access and it is not on arXiv then I will not be putting it in this list.

Note: the date is associated with the latest update/publication (i.e. how you would see it cited), not the first!

---

## Table of Contents

- [Reviews](#reviews-)
- [Software](#software-)
- [Theory](#theory-)
  - [Expressivity](#expressivity-)
  - [Dyanmics](#dynamics-)
  - [Trainability](#trainability-)
  - [Complexity and Learnability and Generalization](#complexity-and-learnability-and-generalization-)
- [Optimization](#optimization-)
- [Circuit Ansatz](#circuit-ansatz-)
- [Quantum Reinforcement Learning](#quantum-reinforcement-learning-)
- [Geometric QML](#geometric-qml-)
- [Generative QML](#generative-qml-)
- [Autoencoders](#autoencoders-)
- [QAOA](#qaoa-)
- [VQE](#vqe-)
- [Quantum Simulation](#quantum-simulation-)
- [Classification](#classification-)
- [Error Mitigation and QML](#error-mitigation-and-qml-)

---

## Contents

### Reviews [^](#table-of-contents)

- [A Survey of Quantum Alternatives to Randomized Algorithms: Monte Carlo Integration and Beyond](https://arxiv.org/abs/2303.04945v1) (2023)
- [Variational Benchmarks for Quantum Many-Body Problems](https://arxiv.org/abs/2302.04919) (2023)
- [Optimization Applications as Quantum Performance Benchmarks](https://arxiv.org/abs/2302.02278) (2023)
- [Quantum Computing Toolkit From Nuts and Bolts to Sack of Tools](https://arxiv.org/abs/2302.08884) (2023)
- [Quantum Machine Learning: from physics to software engineering](https://arxiv.org/abs/2301.01851) (2023)
- [A Survey on Quantum Reinforcement Learning](https://arxiv.org/abs/2211.03464) (2022)
- [Computational advantage of quantum random sampling](https://arxiv.org/abs/2206.04079) (2022)
- [Quantum computing at the quantum advantage threshold: a down-to-business review](https://arxiv.org/abs/2203.17181) (2022)
- [The Variational Quantum Eigensolver: A review of methods and best practices](https://www.sciencedirect.com/science/article/pii/S0370157322003118) (2022)
- [Variational Quantum Algorithms](https://arxiv.org/abs/2012.09265) (2021)
- [Emerging quantum computing algorithms for quantum chemistry](https://arxiv.org/abs/2109.02873) (2021)
- [Noisy intermediate-scale quantum (NISQ) algorithms](https://arxiv.org/abs/2101.08448) (2021)
- [Quantum computing models for artificial neural networks](https://iopscience.iop.org/article/10.1209/0295-5075/134/10002/meta) (2021)
- [A non-review of Quantum Machine Learning: trends and explorations](https://quantum-journal.org/views/qv-2020-03-17-32/) (2020)
- [The theory of variational hybrid quantum-classical algorithms](https://iopscience.iop.org/article/10.1088/1367-2630/18/2/023023/meta) (2016)

### Software [^](#table-of-contents)

- [Open-Source Quantum Software Projects](https://github.com/qosf/awesome-quantum-software)
- [Hierarchical architecture representations for quantum convolutional neural networks](https://arxiv.org/abs/2210.15073) (2023)
- [TeD-Q: a tensor network enhanced distributed hybrid quantum machine learning framework](https://arxiv.org/abs/2301.05451) (2023)
- [Differentiable quantum computational chemistry with PennyLane](https://arxiv.org/abs/2111.09967) (2023)
- [PennyLane: Automatic differentiation of hybrid quantum-classical computations](https://arxiv.org/abs/1811.04968) (2022)
- [TensorFlow Quantum: A Software Framework for Quantum Machine Learning](https://arxiv.org/abs/2003.02989) (2021)
- [Tequila: A platform for rapid development of quantum algorithms](https://arxiv.org/abs/2011.03057) (2021)
- [ORQVIZ: Visualizing High-Dimensional Landscapes in Variational Quantum Algorithms](https://arxiv.org/abs/2111.04695) (2021)


### Theory [^](#table-of-contents)

#### Expressivity [^](#table-of-contents)

- [Contextuality and inductive bias in quantum machine learning](https://arxiv.org/abs/2302.01365) (2023)
- [Evaluation of parameterized quantum circuits: on the relation between classification accuracy, expressibility, and entangling capability](https://link.springer.com/article/10.1007/s42484-021-00038-w) (2021)
- [Expressibility of the alternating layered ansatz for quantum computation](https://quantum-journal.org/papers/q-2021-04-19-434/) (2021)
- [Dimensional Expressivity Analysis of Parametric Quantum Circuits](https://quantum-journal.org/papers/q-2021-03-29-422/) (2021)
- [Expressive power of parametrized quantum circuits](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.2.033125) (2020)
- [Expressibility and entangling capability of parameterized quantum circuits for hybrid quantum-classical algorithms](https://arxiv.org/abs/1905.10876) (2019)


#### Dynamics [^](#table-of-contents)

- [Effects of noise on the overparametrization of quantum neural networks](https://arxiv.org/abs/2302.05059) (2023)
- [The Quantum Path Kernel: a Generalized Quantum Neural Tangent Kernel for Deep Quantum Machine Learning](https://arxiv.org/abs/2212.11826) (2022)
- [An analytic theory for the dynamics of wide quantum neural networks](https://arxiv.org/abs/2203.16711) (2022)
- [Connecting geometry and performance of two-qubit parameterized quantum circuits](https://quantum-journal.org/papers/q-2022-08-23-782/) (2022)
- [Theory of overparametrization in quantum neural networks](https://arxiv.org/abs/2109.11676) (2021)
- [The Inductive Bias of Quantum Kernels](https://proceedings.neurips.cc/paper/2021/hash/69adc1e107f7f7d035d7baf04342e1ca-Abstract.html) (2021)
- [Characterizing the loss landscape of variational quantum circuits](https://arxiv.org/abs/2008.02785) (2021)
- [Noise-induced barren plateaus in variational quantum algorithms](https://www.nature.com/articles/s41467-021-27045-6) (2021)

#### Trainability [^](#table-of-contents)

- [Trainability Enhancement of Parameterized Quantum Circuits via Reduced-Domain Parameter Initialization](https://arxiv.org/abs/2302.06858) (2023)
- [Efficient estimation of trainability for variational quantum circuits](https://arxiv.org/abs/2302.04649) (2023)
- [Quantum variational algorithms are swamped with traps](https://www.nature.com/articles/s41467-022-35364-5) (2022)
- [Exponential concentration and untrainability in quantum kernel methods](https://arxiv.org/abs/2208.11060) (2022)
- [Equivalence of quantum barren plateaus to cost concentration and narrow gorges](https://arxiv.org/abs/2104.05868) (2022)
- [Subtleties in the trainability of quantum machine learning models](https://arxiv.org/abs/2110.14753) (2021)
- [The dilemma of quantum neural networks](https://arxiv.org/abs/2106.04975) (2021)
- [Absence of Barren Plateaus in Quantum Convolutional Neural Networks](https://journals.aps.org/prx/abstract/10.1103/PhysRevX.11.041011) (2021)
- [On barren plateaus and cost function locality in variational quantum algorithms](https://arxiv.org/abs/2011.10530) (2021)

#### Complexity and Learnability and Generalization [^](#table-of-contents)

- [Provably efficient machine learning for quantum many-body problems](https://arxiv.org/abs/2106.12627) (2022)
- [Quantum machine learning beyond kernel methods](https://arxiv.org/abs/2110.13162) (2022)
- [Is quantum advantage the right goal for quantum machine learning?](https://arxiv.org/abs/2203.01340) (2022)
- [On the Quantum versus Classical Learnability of Discrete Distributions](https://quantum-journal.org/papers/q-2021-03-23-417/) (2021)
- [Generalization in Quantum Machine Learning: A Quantum Information Standpoint](https://journals.aps.org/prxquantum/abstract/10.1103/PRXQuantum.2.040321) (2021)
- [Encoding-dependent generalization bounds for parametrized quantum circuits](https://quantum-journal.org/papers/q-2021-11-17-582/) (2021)
- [Supervised quantum machine learning models are kernel methods](https://arxiv.org/abs/2101.11020) (2021)
- [Limitations of optimization algorithms on noisy quantum devices](https://arxiv.org/abs/2009.05532) (2020)

### Optimization [^](#table-of-contents)

- [An Empirical Review of Optimization Techniques for Quantum Variational Circuits](https://arxiv.org/abs/2202.01389) (2022)
- [Markov chain Monte Carlo enhanced variational quantum algorithms](https://iopscience.iop.org/article/10.1088/2058-9565/aca821/meta) (2022)
- [Optimizing Quantum Variational Circuits with Deep Reinforcement Learning](https://arxiv.org/abs/2109.03188) (2022)
- [Optimizing quantum circuits with Riemannian gradient flow](https://arxiv.org/abs/2202.06976) (2022)
- [Variational quantum algorithm with information sharing](https://www.nature.com/articles/s41534-021-00452-9) (2021)
- [Single-component gradient rules for variational quantum algorithms](https://arxiv.org/abs/2106.01388) (2021)
- [Natural Gradient Optimization for Optical Quantum Circuits](https://arxiv.org/abs/2106.13660) (2021)
- [Simultaneous Perturbation Stochastic Approximation of the Quantum Fisher Information](https://quantum-journal.org/papers/q-2021-10-20-567/) (2021)
- [Natural evolutionary strategies for variational quantum computation](https://iopscience.iop.org/article/10.1088/2632-2153/abf3ac/meta) (2021)
- [Learning to learn with quantum neural networks via classical neural networks](https://arxiv.org/abs/1907.05415) (2019)

### Circuit Ansatz [^](#table-of-contents) 

- [Hamiltonian variational ansatz without barren plateaus](https://arxiv.org/abs/2302.08529) (2023)
- [GA4QCO: Genetic Algorithm for Quantum Circuit Optimization](https://arxiv.org/abs/2302.01303) (2023)
- [Policy Gradient Approach to Compilation of Variational Quantum Circuits](https://arxiv.org/abs/2111.10227) (2022)
- [Mixer-phaser Ansätze for quantum optimization with hard constraints](https://link.springer.com/article/10.1007/s42484-022-00069-x) (2022)
- [A semi-agnostic ansatz with variable structure for quantum machine learning](https://arxiv.org/abs/2103.06712) (2022)
- [Quantum Deformed Neural Networks](https://arxiv.org/abs/2010.11189) (2020)
- [Quantum Convolutional Neural Networks](https://arxiv.org/abs/1810.03787) (2019)

### Quantum Reinforcement Learning [^](#table-of-contents)

- [Quantum Imitation Learning](https://arxiv.org/abs/2304.02480) (2023)
- [Provably Efficient Exploration in Quantum Reinforcement Learning with Logarithmic Worst-Case Regret](https://arxiv.org/abs/2302.10796) (2023)
- [Quantum algorithms applied to satellite mission planning for Earth observation](https://arxiv.org/abs/2302.07181) (2023)
- [Quantum Computing Provides Exponential Regret Improvement in Episodic Reinforcement Learning](https://arxiv.org/abs/2302.08617) (2023)
- [Asynchronous training of quantum reinforcement learning](https://arxiv.org/abs/2301.05096) (2023)
- [Quantum policy gradient algorithms](https://arxiv.org/abs/2212.09328) (2022)
- [Robustness of quantum reinforcement learning under hardware errors](https://arxiv.org/abs/2212.09431) (2022)
- [Quantum Policy Gradient Algorithm with Optimized Action Decoding](https://arxiv.org/abs/2212.06663) (2022)
- [Variational Quantum Soft Actor-Critic for Robotic Arm Control](https://arxiv.org/abs/2212.11681) (2022)
- [Bandit approach to conflict-free multi-agent Q-learning in view of photonic implementation](https://arxiv.org/abs/2212.09926) (2022)
- [Quantum deep recurrent reinforcement learning](https://arxiv.org/abs/2210.14876) (2022)
- [Unentangled quantum reinforcement learning agents in the OpenAI Gym](https://arxiv.org/abs/2203.14348) (2022)
- [Quantum Deep Reinforcement Learning for Robot Navigation Tasks](https://arxiv.org/abs/2202.12180) (2022)
- [Quantum reinforcement learning: the maze problem](https://link.springer.com/article/10.1007/s42484-022-00068-y) (2022)
- [Performance analysis of a hybrid agent for quantum-accessible reinforcement learning](https://iopscience.iop.org/article/10.1088/1367-2630/ac5b56/meta) (2022)
- [Quantum agents in the Gym: a variational quantum algorithm for deep Q-learning](https://quantum-journal.org/papers/q-2022-05-24-720/) (2022)
- [Equivariant quantum circuits for learning on weighted graphs](https://arxiv.org/abs/2205.06109) (2022)
- [Quantum reinforcement learning in continuous action space](https://arxiv.org/abs/2012.10711) (2021)
- [Experimental quantum speed-up in reinforcement learning agents](https://arxiv.org/abs/2103.06294) (2021)
- [Parametrized Quantum Policies for Reinforcement Learning](https://proceedings.neurips.cc/paper/2021/hash/eec96a7f788e88184c0e713456026f3f-Abstract.html) (2021)
- [Variational Quantum Soft Actor-Critic](https://arxiv.org/abs/2112.11921) (2021)
- [Photonic Quantum Policy Learning in OpenAI Gym](https://arxiv.org/abs/2108.12926) (2021)
- [Playing Atari with Hybrid Quantum-Classical Reinforcement Learning](https://proceedings.mlr.press/v148/lockwood21a.html) (2021)
- [Variational Quantum Circuits for Deep Reinforcement Learning](https://ieeexplore.ieee.org/abstract/document/9144562) (2020)
- [Reinforcement Learning with Quantum Variational Circuits](https://ojs.aaai.org/index.php/AIIDE/article/view/7437) (2020)
- [Reinforcement Learning with Deep Quantum Neural Networks](https://www.scirp.org/html/1-1300264_90994.htm?pagespeed=noscript) (2019)

### Geometric QML [^](#table-of-contents)

- [Exploiting symmetry in variational quantum machine learning](https://arxiv.org/abs/2205.06217) (2022)

### Generative QML [^](#table-of-contents)

- [Generative Invertible Quantum Neural Networks](https://arxiv.org/abs/2302.12906) (2023)
- [A performance characterization of quantum generative models](https://arxiv.org/abs/2301.09363) (2023)
- [Style-based quantum generative adversarial networks for Monte Carlo events](https://quantum-journal.org/papers/q-2022-08-17-777/) (2022)
- [Generation of High-Resolution Handwritten Digits with an Ion-Trap Quantum Computer](https://journals.aps.org/prx/abstract/10.1103/PhysRevX.12.031010) (2022)
- [Anomaly detection with variational quantum generative adversarial networks](https://arxiv.org/abs/2010.10492) (2021)
- [Experimental Quantum Generative Adversarial Networks for Image Generation](https://arxiv.org/abs/2010.06201) (2021)

### Autoencoders [^](#table-of-contents)

- [On exploring practical potentials of quantum auto-encoder with advantages](https://arxiv.org/abs/2106.15432) (2021)
- [Quantum autoencoders with enhanced data encoding](https://arxiv.org/abs/2010.06599) (2021)

### QAOA [^](#table-of-contents)

- [Information scrambling and entanglement in quantum approximate optimization algorithm circuits](https://arxiv.org/abs/2301.07445) (2023)
- [Fermionic Quantum Approximate Optimization Algorithm](https://arxiv.org/abs/2301.10756) (2023)
- [Scaling of the quantum approximate optimization algorithm on superconducting qubit based hardware](https://arxiv.org/abs/2202.03459) (2022)
- [Quantum annealing initialization of the quantum approximate optimization algorithm](https://quantum-journal.org/papers/q-2021-07-01-491/) (2021)
- [Training Saturation in Layerwise Quantum Approximate Optimisation](https://arxiv.org/abs/2106.13814) (2021)

### VQE [^](#table-of-contents)

- [Symmetry enhanced variational quantum spin eigensolver](https://quantum-journal.org/papers/q-2023-01-19-899/) (2023)
- [Contextual Subspace Variational Quantum Eigensolver](https://quantum-journal.org/papers/q-2021-05-14-456/) (2021)

### Quantum Simulation [^](#table-of-contents)

- [Quantum simulation of battery materials using ionic pseudopotentials](https://arxiv.org/abs/2302.07981) (2023)
- [Simulating Majorana zero modes on a noisy quantum processor](https://iopscience.iop.org/article/10.1088/2058-9565/acb796/meta) (2023)
- [Physics Simulation Via Quantum Graph Neural Network](https://arxiv.org/abs/2301.04702) (2023)
- [Noise-assisted variational quantum thermalization](https://www.nature.com/articles/s41598-022-07296-z) (2022)
- [Extending the Variational Quantum Eigensolver to Finite Temperatures](https://arxiv.org/abs/2208.07621) (2022)
- [Simulating hydrodynamics on noisy intermediate-scale quantum devices with random circuits](https://arxiv.org/abs/2012.02795) (2021)
- [An efficient quantum algorithm for the time evolution of parameterized circuits](https://quantum-journal.org/papers/q-2021-07-28-512/) (2021)
- [Variational quantum algorithm for molecular geometry optimization](https://arxiv.org/abs/2106.13840) (2021)
- [Simulating Many-Body Systems with a Projective Quantum Eigensolver](https://journals.aps.org/prxquantum/abstract/10.1103/PRXQuantum.2.030301) (2021)

### Classification [^](#table-of-contents)

- [Practical overview of image classification with tensor-network quantum circuits](https://www.nature.com/articles/s41598-023-30258-y) (2023)
- [Quantum Methods for Neural Networks and Application to Medical Image Classification](https://quantum-journal.org/papers/q-2022-12-22-881/) (2022)
- [VSQL: Variational Shadow Quantum Learning for Classification](https://ojs.aaai.org/index.php/AAAI/article/view/17016) (2021)
- [Machine learning of high dimensional data on a noisy quantum processor](https://www.nature.com/articles/s41534-021-00498-9) (2021)
- [Single-qubit universal classifier implemented on an ion-trap quantum device](https://arxiv.org/abs/2106.14059) (2021)
- [Nearest centroid classification on a trapped ion quantum computer](https://www.nature.com/articles/s41534-021-00456-5) (2021)
- [Circuit-centric quantum classifiers](https://arxiv.org/abs/1804.00633) (2018)

### Error Mitigation and QML [^](#table-of-contents)

- [Synergetic quantum error mitigation by randomized compiling and zero-noise extrapolation for the variational quantum eigensolver](https://arxiv.org/abs/2212.11198) (2022)
- [Experimental error mitigation using linear rescaling for variational quantum eigensolving with up to 20 qubits](https://arxiv.org/abs/2106.01264) (2021)
- [Can Error Mitigation Improve Trainability of Noisy Variational Quantum Algorithms?](https://arxiv.org/abs/2109.01051) (2021)

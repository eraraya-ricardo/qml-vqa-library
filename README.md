<h1 align="center">QML-VQA Library</h1>
<div align="center">
<img src="https://img.shields.io/static/v1?label=%F0%9F%8C%9F&message=If%20Useful&style=style=flat&color=BC4E99" alt="Star Badge"/>
<a href="http://creativecommons.org/publicdomain/zero/1.0/"><img src="https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg" alt="License: CC0 1.0"/></a>

<i align="center">A curated list of recent textbooks, reviews, perspectives, and research papers related to **`quantum machine learning`**, **`variational quantum algorithms`**, **`tensor networks`**, and **`classical machine learning applications in quantum systems`**.</i>

<figure class="image">
  <img src="https://media.springernature.com/original/springer-static/image/chp%3A10.1007%2F978-3-030-50433-5_45/MediaObjects/500809_1_En_45_Fig1_HTML.png" alt="QML">
  <figcaption>Scheme of a hybrid quantum-classical algorithm for supervised learning[<a href="#references" rel="nofollow">1</a>].</figcaption>
</figure>

</div>

---

## Table of Contents
Press `^` to return to the **`Table of Contents`**.
- [Textbooks](#textbooks-)
- [Reviews & Perspectives](#reviews--perspectives-)
- [Quantum Classifier](#quantum-classifier-)
  - [Quantum Neural Networks & Variational Quantum Classifier](#quantum-neural-networks--variational-quantum-classifier-)
  - [Quantum Support Vector Machine](#quantum-support-vector-machine-)
  - [Quantum Ensembles](#quantum-ensembles-)
  - [Quantum k-Nearest Neighbors](#quantum-k-nearest-neighbors-)
- [Quantum Convolutional Neural Networks](#quantum-convolutional-neural-networks-)
  - [Near Term (without QRAM)](#near-term-without-qram-)
  - [Need QRAM](#need-qram-)
- [Quantum Graph Neural Networks](#quantum-graph-neural-networks-)
- [Quantum Generative Models & Quantum GANs](#quantum-generative-models--quantum-gans-)
- [Quantum Boltzmann Machines](#quantum-boltzmann-machines-)
- [Variational Quantum Eigensolver](#variational-quantum-eigensolver-)
- [Quantum Optimization](#quantum-optimization-)
- [Quantum Reinforcement Learning](#quantum-reinforcement-learning-)
- [Quantum Autoencoders](#quantum-autoencoders-)
- [Training & Circuit Construction Techniques](#training--circuit-construction-techniques-)
- [Embedding/Encoding Techniques](#embeddingencoding-techniques-)
- [Circuit Learning Capability Analysis (Expressivity, Entanglement, etc.)](#circuit-learning-capability-analysis-expressivity-entanglement-etc-)
- [Barren Plateaus Analysis](#barren-plateaus-analysis-)
- [Gradient Techniques](#gradient-techniques-)
- [Tensor Networks](#tensor-networks-)
- [Quantum Image Processing](#quantum-image-processing-)
- [Classical Machine Learning Applications in Quantum Computing](#classical-machine-learning-applications-in-quantum-computing-)
- [Uncategorized (yet)](#uncategorized-yet-)

---

## Contents
### Textbooks [^](#table-of-contents)
- [Supervised Learning with Quantum Computers](https://www.springer.com/gp/book/9783319964232) (2018)
- [Quantum Machine Learning: What Quantum Computing Means to Data Mining](https://www.sciencedirect.com/book/9780128009536/quantum-machine-learning) (2014)

### Reviews & Perspectives [^](#table-of-contents)
- [Quantum machine learning in high energy physics](https://iopscience.iop.org/article/10.1088/2632-2153/abc17d) (2021)
- [Quantum machine learning and its supremacy in high energy physics](https://www.worldscientific.com/doi/abs/10.1142/S0217732320300244) (2021)
- [Quantum Reinforcement Learning with Quantum Photonics](https://www.mdpi.com/2304-6732/8/2/33) (2021)
- [Variational Quantum Algorithms](https://arxiv.org/abs/2012.09265) (2020)
- [A non-review of Quantum Machine Learning: trends and explorations](https://quantum-journal.org/views/qv-2020-03-17-32/) (2020)
- [Quantum Chemistry in the Age of Quantum Computing](https://pubs.acs.org/doi/10.1021/acs.chemrev.8b00803) (2019)
- [Quantum Deep Learning Neural Networks](https://link.springer.com/chapter/10.1007/978-3-030-12385-7_24) (2019)
- [Opportunities and challenges for quantum-assisted machine learning in near-term quantum computers](https://iopscience.iop.org/article/10.1088/2058-9565/aab859/meta) (2018)
- [Quantum machine learning: a classical perspective](https://doi.org/10.3929/ethz-b-000240892) (2018)
- [Quantum machine learning](https://www.nature.com/articles/nature23474) (2017)

### Quantum Classifier [^](#table-of-contents)
#### Quantum Neural Networks & Variational Quantum Classifier [^](#table-of-contents)
- [Unified framework for quantum classification](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.3.033056) (2021)
- [QDNN: deep neural networks with quantum layers](https://link.springer.com/article/10.1007/s42484-021-00046-w) (2021)
- [Quantum Machine Learning Algorithms for Drug Discovery Applications](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00166) (2021)
- [On Depth, Robustness and Performance Using the Data Re-Uploading Single-Qubit Classifier](https://ieeexplore.ieee.org/document/9415627) (2021)
- [Quantum state discrimination using noisy quantum neural networks](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.3.013063) (2021)
- [Event Classification with Quantum Machine Learning in High-Energy Physics](https://link.springer.com/article/10.1007%2Fs41781-020-00047-7) (2021)
- [Data re-uploading for a universal quantum classifier](https://quantum-journal.org/papers/q-2020-02-06-226/) (2020)
- [Circuit-centric quantum classifiers](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.101.032308) (2020)
- [Hierarchical quantum classifiers](https://www.nature.com/articles/s41534-018-0116-9) (2018)
- [Quantum circuit learning](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.98.032309) (2018)
- [Classification with Quantum Neural Networks on Near Term Processors](https://arxiv.org/abs/1802.06002) (2018)
#### Quantum Support Vector Machine [^](#table-of-contents)
- [Application of Quantum Machine Learning using the Quantum Kernel Algorithm on High Energy Physics Analysis at the LHC](https://inspirehep.net/literature/1857931) (2021)
- [A rigorous and robust quantum speed-up in supervised machine learning](https://arxiv.org/abs/2010.02174) (2020)
- [Application of Quantum Machine Learning to High Energy Physics Analysis at LHC using IBM Quantum Computer Simulators and IBM Quantum Computer Hardware](https://pos.sissa.it/367/049) (2019)
- [Supervised learning with quantum-enhanced feature spaces](https://www.nature.com/articles/s41586-019-0980-2) (2019)
- [Quantum machine learning for quantum anomaly detection](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.97.042315) (2018)
#### Quantum Ensembles [^](#table-of-contents)
- [On quantum ensembles of quantum classifiers](https://link.springer.com/article/10.1007/s42484-020-00018-6) (2020)
#### Quantum k-Nearest Neighbors [^](#table-of-contents)
- [Implementing a distance-based classifier with a quantum interference circuit](https://iopscience.iop.org/article/10.1209/0295-5075/119/60002) (2017)

### Quantum Convolutional Neural Networks [^](#table-of-contents)
#### Near Term (without QRAM) [^](#table-of-contents)
- [Decentralizing Feature Extraction with Quantum Convolutional Neural Network for Automatic Speech Recognition](https://ieeexplore.ieee.org/abstract/document/9413453) (2021)
- [Methods for accelerating geospatial data processing using quantum computers](https://link.springer.com/article/10.1007/s42484-020-00034-6) (2021)
- [Quantum Convolutional Neural Networks for High Energy Physics Data Analysis](https://arxiv.org/abs/2012.12177) (2020)
- [A Tutorial on Quantum Convolutional Neural Networks (QCNN)](https://arxiv.org/abs/2009.09423) (2020)
- [Explorations in Quantum Neural Networks with Intermediate Measurements](https://www.esann.org/sites/default/files/proceedings/2020/ES2020-197.pdf) (2020)
- [Quanvolutional neural networks: powering image recognition with quantum circuits](https://link.springer.com/article/10.1007/s42484-020-00012-y) (2020)
- [Hybrid Quantum-Classical Convolutional Neural Networks](https://arxiv.org/abs/1911.02998) (2019)
- [Quantum convolutional neural networks](https://www.nature.com/articles/s41567-019-0648-8) (2019)
#### Need QRAM [^](#table-of-contents)
- [A quantum deep convolutional neural network for image recognition](https://iopscience.iop.org/article/10.1088/2058-9565/ab9f93) (2020)
- [Quantum Algorithms for Deep Convolutional Neural Networks](https://iclr.cc/virtual_2020/poster_Hygab1rKDS.html) (2020)

### Quantum Graph Neural Networks [^](#table-of-contents)
- [A Tutorial on Quantum Graph Recurrent Neural Network (QGRNN)](https://ieeexplore.ieee.org/document/9333917) (2021)
- [Hybrid Quantum-Classical Graph Convolutional Network](https://arxiv.org/abs/2101.06189) (2021)
- [Performance of Particle Tracking Using a Quantum Graph Neural Network](https://inspirehep.net/literature/1834498) (2020)
- [A Quantum Graph Neural Network Approach to Particle Track Reconstruction](https://inspirehep.net/literature/1806878) (2020)
- [Particle Track Reconstruction with Quantum Algorithms](https://www.epj-conferences.org/articles/epjconf/pdf/2020/21/epjconf_chep2020_09013.pdf) (2019)
- [Quantum Graph Neural Networks](https://arxiv.org/abs/1909.12264) (2019)

### Quantum Generative Models & Quantum GANs [^](#table-of-contents)
- [Anomaly detection with variational quantum generative adversarial networks](https://iopscience.iop.org/article/10.1088/2058-9565/ac0d4d) (2021)
- [Generation of High-Resolution Handwritten Digits with an Ion-Trap Quantum Computer](https://scirate.com/arxiv/2012.03924) (2021)
- [Noise Robustness and Experimental Demonstration of a Quantum Generative Adversarial Network for Continuous Distributions](https://onlinelibrary.wiley.com/doi/10.1002/qute.202000069) (2021)
- [Dual-Parameterized Quantum Circuit GAN Model in High Energy Physics](https://arxiv.org/abs/2103.15470) (2021)
- [Quantum Generative Adversarial Networks in a Continuous-Variable Architecture to Simulate High Energy Physics Detectors](https://arxiv.org/abs/2101.11132) (2021)
- [Quantum versus classical generative modelling in finance](https://iopscience.iop.org/article/10.1088/2058-9565/abd3db) (2021)
- [Experimental Quantum Generative Adversarial Networks for Image Generation](https://arxiv.org/abs/2010.06201) (2020)
- [Quantum semi-supervised generative adversarial network for enhanced data classification](https://arxiv.org/abs/2010.13727) (2020)
- [Near-term quantum-classical associative adversarial networks](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.100.052327) (2019)
- [Quantum Generative Adversarial Networks for learning and loading random distributions](https://www.nature.com/articles/s41534-019-0223-2) (2019)
- [Quantum Generative Adversarial Learning](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.121.040502) (2018)
- [Quantum generative adversarial networks](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.98.012324) (2018)

### Quantum Boltzmann Machines [^](#table-of-contents)
- [Variational quantum Boltzmann machines](https://link.springer.com/article/10.1007%2Fs42484-020-00033-7) (2021)
- [Quantum Boltzmann Machine](https://journals.aps.org/prx/abstract/10.1103/PhysRevX.8.021050) (2018)

### Variational Quantum Eigensolver [^](#table-of-contents)
- [Simulating Many-Body Systems with a Projective Quantum Eigensolver](https://journals.aps.org/prxquantum/abstract/10.1103/PRXQuantum.2.030301) (2021)
- [Qubit-ADAPT-VQE: An Adaptive Algorithm for Constructing Hardware-Efficient Ansätze on a Quantum Processor](https://journals.aps.org/prxquantum/abstract/10.1103/PRXQuantum.2.020310) (2021)
- [Measurement-Based Variational Quantum Eigensolver](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.126.220501) (2021)
- [Classically-Boosted Variational Quantum Eigensolver](https://arxiv.org/abs/2106.04755) (2021)
- [Meta-Variational Quantum Eigensolver: Learning Energy Profiles of Parameterized Hamiltonians for Quantum Simulation](https://journals.aps.org/prxquantum/abstract/10.1103/PRXQuantum.2.020329) (2021)
- [Resource-efficient quantum algorithm for protein folding (Application of CVaR-VQE)](https://www.nature.com/articles/s41534-021-00368-4) (2021)
- [Penalty methods for a variational quantum eigensolver](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.3.013197) (2021)
- [Application of Quantum Machine Learning to VLSI Placement](https://dl.acm.org/doi/10.1145/3380446.3430644) (2020)
- [An adaptive variational algorithm for exact molecular simulations on a quantum computer](https://www.nature.com/articles/s41467-019-10988-2) (2019)
- [Subspace-search variational quantum eigensolver for excited states](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.1.033062) (2019)
- [Variational Quantum Computation of Excited States](https://quantum-journal.org/papers/q-2019-07-01-156/) (2019)
- [A variational eigenvalue solver on a photonic quantum processor](https://www.nature.com/articles/ncomms5213) (2014)

### Quantum Optimization [^](#table-of-contents)
- [Warm-starting quantum optimization](https://quantum-journal.org/papers/q-2021-06-17-479/) (2021)
- [Qubit-efficient encoding schemes for binary optimisation problems](https://quantum-journal.org/papers/q-2021-05-04-454/) (2021)
- [Quantum gradient algorithm for general polynomials](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.103.042403) (2021)
- [Quantum approximate optimization of non-planar graph problems on a planar superconducting processor](https://www.nature.com/articles/s41567-020-01105-y) (2021)
- [Improving Variational Quantum Optimization using CVaR](https://quantum-journal.org/papers/q-2020-04-20-256/) (2020)
- [The Quantum Alternating Operator Ansatz on Maximum k-Vertex Cover](https://ieeexplore.ieee.org/abstract/document/9259949) (2020)
- [Quantum optimization using variational algorithms on near-term quantum devices](https://iopscience.iop.org/article/10.1088/2058-9565/aab822#qstaab822s5) (2018) (*this one is like a review of VQE*)
- [A Quantum Approximate Optimization Algorithm](https://arxiv.org/abs/1411.4028) (2014)

### Quantum Reinforcement Learning [^](#table-of-contents)
- [Quantum agents in the Gym: a variational quantum algorithm for deep Q-learning](https://arxiv.org/abs/2103.15084) (2021)
- [Variational quantum policies for reinforcement learning](https://arxiv.org/abs/2103.05577) (2021)
- [Variational Quantum Circuits for Deep Reinforcement Learning](https://ieeexplore.ieee.org/document/9144562) (2020)
- [Reinforcement Learning with Quantum Variational Circuit](https://ojs.aaai.org//index.php/AIIDE/article/view/7437) (2020)

### Quantum Autoencoders [^](#table-of-contents)
- [Quantum autoencoders with enhanced data encoding](https://iopscience.iop.org/article/10.1088/2632-2153/ac0616) (2021)
- [Quantum Autoencoders to Denoise Quantum Data](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.124.130502) (2020)
- [Quantum autoencoders for efficient compression of quantum data](https://iopscience.iop.org/article/10.1088/2058-9565/aa8072) (2017)

### Training & Circuit Construction Techniques [^](#table-of-contents)
- [Optimizing quantum heuristics with meta-learning](https://link.springer.com/article/10.1007/s42484-020-00022-w) (2021)
- [Machine Learning of Noise-Resilient Quantum Circuits](https://journals.aps.org/prxquantum/abstract/10.1103/PRXQuantum.2.010324) (2021)
- [Avoiding local minima in Variational Quantum Algorithms with Neural Networks](https://arxiv.org/abs/2104.02955) (2021)
- [Layerwise learning for quantum neural networks](https://link.springer.com/article/10.1007%2Fs42484-020-00036-4) (2021)

### Embedding/Encoding Techniques [^](#table-of-contents)
- [Encoding-dependent generalization bounds for parametrized quantum circuits](https://scirate.com/arxiv/2106.03880) (2021)
- [Efficient Discrete Feature Encoding for Variational Quantum Classifier](https://ieeexplore.ieee.org/document/9259984) (2020)
- [Robust data encodings for quantum classifiers](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.102.032420) (2020)

### Circuit Learning Capability Analysis (Expressivity, Entanglement, etc.) [^](#table-of-contents)
- [The power of quantum neural networks](https://www.nature.com/articles/s43588-021-00084-1) (2021)
- [Power of data in quantum machine learning](https://www.nature.com/articles/s41467-021-22539-9) (2021)
- [The Inductive Bias of Quantum Kernels](https://arxiv.org/abs/2106.03747) (2021)
- [Supervised quantum machine learning models are kernel methods](https://arxiv.org/abs/2101.11020) (2021)
- [Connecting geometry and performance of two-qubit parameterized quantum circuits](https://www.zapatacomputing.com/publications/connecting-geometry-and-performance-of-two-qubit-parameterized-quantum-circuits/) (2021)
- [Expressibility of the alternating layered ansatz for quantum computation](https://quantum-journal.org/papers/q-2021-04-19-434/) (2021)
- [Evaluation of parameterized quantum circuits: on the relation between classification accuracy, expressibility, and entangling capability](https://link.springer.com/article/10.1007/s42484-021-00038-w) (2021)
- [Dimensional Expressivity Analysis of Parametric Quantum Circuits](https://quantum-journal.org/papers/q-2021-03-29-422/) (2021)
- [Expressibility and Entangling Capability of Parameterized Quantum Circuits for Hybrid Quantum-Classical Algorithms](https://onlinelibrary.wiley.com/doi/abs/10.1002/qute.201900070) (2019)

### Barren Plateaus Analysis [^](#table-of-contents)
- [Analyzing the barren plateau phenomenon in training quantum neural networks with the ZX-calculus](https://quantum-journal.org/papers/q-2021-06-04-466/) (2021)
- [Diagnosing barren plateaus with tools from quantum optimal control](https://arxiv.org/abs/2105.14377) (2021)
- [Cost function dependent barren plateaus in shallow parametrized quantum circuits](https://www.nature.com/articles/s41467-021-21728-w) (2021)
- [Barren plateaus in quantum neural network training landscapes](https://www.nature.com/articles/s41467-018-07090-4) (2018)

### Gradient Techniques [^](#table-of-contents)
- [Simultaneous Perturbation Stochastic Approximation of the Quantum Fisher Information](https://arxiv.org/abs/2103.09232) (2021)
- [Single-component gradient rules for variational quantum algorithms](https://scirate.com/arxiv/2106.01388) (2021)
- [Measuring Analytic Gradients of General Quantum Evolution with the Stochastic Parameter Shift Rule](https://quantum-journal.org/papers/q-2021-01-25-386/) (2021)
- [the noisy parameter-shift rule](https://johannesjakobmeyer.com/blog/004-noisy-parameter-shift/#fn:5) (2020)
- [Quantum Natural Gradient](https://quantum-journal.org/papers/q-2020-05-25-269/) (2020)
- [Evaluating analytic gradients on quantum hardware](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.99.032331) (2019)
- [Gradients of parameterized quantum gates using the parameter-shift rule and gate decomposition](https://arxiv.org/abs/1905.13311) (2019)

### Tensor Networks [^](#table-of-contents)
- [Parallel quantum simulation of large systems on small NISQ computers](https://www.nature.com/articles/s41534-021-00420-3) (2021)

### Quantum Image Processing [^](#table-of-contents)
- [Quantum Image Processing and Its Application to Edge Detection: Theory and Experiment](https://journals.aps.org/prx/abstract/10.1103/PhysRevX.7.031041) (2017)

### Classical Machine Learning Applications in Quantum Computing [^](#table-of-contents)
- [Ray-Based Framework for State Identification in Quantum Dot Devices](https://journals.aps.org/prxquantum/abstract/10.1103/PRXQuantum.2.020335) (2021)
- [Protocol Discovery for the Quantum Control of Majoranas by Differentiable Programming and Natural Evolution Strategies](https://link.aps.org/doi/10.1103/PRXQuantum.2.020332) (2021)

### Uncategorized (yet) [^](#table-of-contents)
- [On the Quantum versus Classical Learnability of Discrete Distributions](https://quantum-journal.org/papers/q-2021-03-23-417/) (2021)

---

## References
[1](https://link.springer.com/chapter/10.1007/978-3-030-50433-5_45). Macaluso A., Clissa L., Lodi S., Sartori C. (2020) A Variational Algorithm for Quantum Neural Networks. In: Krzhizhanovskaya V. et al. (eds) Computational Science – ICCS 2020. ICCS 2020. Lecture Notes in Computer Science, vol 12142. Springer, Cham. https://doi.org/10.1007/978-3-030-50433-5_45

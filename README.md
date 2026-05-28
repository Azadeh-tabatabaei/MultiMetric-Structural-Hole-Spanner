# k-MMSHS: $k$-Multi-Metric Structural Hole Spanners Optimization Framework

This repository will host the official implementation of the **$k$-Multi-Metric Structural Hole Spanners ($k$-MMSHS)** optimization framework, a novel and topology-agnostic approach for strategic network analysis.

## 📢 Current Status: Under Review
The complete source code, algorithmic engines, and benchmarking logs are currently kept **private** as the corresponding manuscript is undergoing the peer-review process. 

**The entire repository, including reproduction scripts, will be made fully Open-Source immediately upon the official publication of the paper.**

---

## 🚀 Key Contributions & Overview

Identifying structural hole spanners (SHS) is essential for optimizing information exchange in social networks, yet it remains computationally challenging as network scale increases. This framework addresses these limitations through:

* **Formal Formulation:** Defines the $k$-MMSHS problem by integrating three distinct structural paradigms: *Effective Size*, *Bridging Coefficient*, and *Betweenness Centrality*.
* **Metaheuristic Engine:** The first modular optimization framework to apply population-based metaheuristics to this domain, featuring:
    * **Genetic Algorithm (GA)**
    * **Particle Swarm Optimization (PSO)**
    * **Enhanced Grey Wolf Optimizer (GWO)** with dynamic mutation and Chaotic Logistic Maps for robust, ergodic exploration.
* **Topology-Agnostic Advantage:** Unlike deep learning or graph neural network models, this framework provides high-precision results purely based on network topology **without requiring any training data or overhead**.
* **Proven Scalability:** Successfully benchmarks against traditional greedy methods, demonstrating stable scalability and high-quality solutions on large-scale real-world and synthetic graphs where traditional methods fail to converge.

---

## 📅 Roadmap & Upcoming Releases
Upon publication, this repository will be updated with:
1.  **Core Source Code:** Clean, modular Python implementations of the GA, PSO, and Chaotic GWO engines.
2.  **Dataset Suite:** Pre-processing scripts for both real-world social networks and synthetic graphs.
3.  **Evaluation Notebooks:** Ready-to-use scripts for plotting efficiency, convergence curves, and structural hole metrics.

---

<!-- ## 📖 Proposed Citation
If you are interested in this research or wish to track its release, please reference the upcoming publication:

> **Tabatabaei, et al.** "$k$-Multi-Metric Structural Hole Spanner Detection via Enhanced Population-Based Metaheuristics." *Under Review* (2026).

---
*For inquiries regarding collaboration or early access to the preprint for academic verification, please contact the corresponding author via institutional channels.* -->

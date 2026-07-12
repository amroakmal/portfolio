# Amr Akmal Abouelmagd

**M.S. Computer Science · HPC & GPU Systems Researcher · Software Engineer**

🔗 **Live portfolio → https://amroakmal.github.io**

---

I chase one question: how do large-scale systems actually behave when you push them
to the edge? My research runs from **GPU architecture, partitioning, and power** on the
AMD MI300A APU behind **El Capitan** — the world's fastest supercomputer — to **fault
tolerance in HPC**, **KV-caching architecture and performance**, and reshaping **MPI for
the AI era** so it stays fault-tolerant.
This fall I begin my PhD journey with Prof. Anthony Skjellum.

## Research interests

- GPU Architecture, Partitioning & Power
- Fault Tolerance in HPC Systems
- KV-Caching Architecture & Performance
- MPI for AI — fault-tolerant, strong progress
- Distributed Systems & Parallel Computing
- Systems Performance Analysis

## Education

- **Ph.D. in Computer Science** — Tennessee Technological University · *incoming, Fall 2026* (advised by Prof. Anthony Skjellum)
- **M.S. in Computer Science** — Tennessee Technological University · GPA 4.0/4.0 · *Jan 2024 – Summer 2026*
- **B.S. in Computer Engineering** — Alexandria University, Faculty of Engineering · *2016 – 2021*

## Experience

**Lawrence Livermore National Laboratory** — Research Intern, Computation Directorate *(2025 – 2026)*
- Systems-level research on the AMD MI300A APU: GPU runtime scheduling, dynamic power sharing, and heterogeneous memory behavior.
- Benchmarked RAJA Performance Suite kernels across **SPX / TPX / CPX** partitioning modes, surfacing up to **30% execution-time variance** across configurations.
- Authored a peer-reviewed paper on MI300A partitioning, power, and performance (accepted at SCA/HPC Asia 2026), targeting optimization of El Capitan.

**Incorta** — Software Engineer II → R&D Engineer → Graduate Intern *(2021 – 2024)*
- Optimized a distributed analytics platform on Kubernetes + ZooKeeper for enterprise-scale workloads.
- Delivered a **2× indexing speedup** and **7× query-latency reduction** on datasets exceeding 1 billion records.
- Designed an internal caching layer that cut cloud object-storage I/O and cost; raised average CPU utilization from **40% to 85%**.

## Selected publications

*(4 first-author · full list on the [live site](https://amroakmal.github.io/#publications))*

1. **A. Abouelmagd**, D. Boehme, S. Brink, J. Burmark, M. McKinsey, A. Skjellum, O. Pearce. *GPU Partitioning, Power, and Performance of the AMD MI300A.* **SCA/HPC Asia 2026.**
2. **A. A. Abouelmagd**, O. Pearce, S. Brink, M. McKinsey, D. Boehme, J. Burmark, B. Ryujin, T. Scogland, A. Skjellum. *Using Hardware Metrics to Understand Performance of RAJA Suite Kernels in Different GPU Modes on MI300A.* **Poster, SC'25 — Top 5 Finalist, Graduate Student Research Competition.**
3. S. Yang, X. Yao, G. Nansamba, **A. A. Abouelmagd**, A. Skjellum, M. Herbordt. *Load Imbalance in HPC Applications: Improved Profiling and New Ways to Use Wasted Cycles.* **IEEE HPEC 2025.**
4. E. Namugwanya, G. Nansamba, **A. A. Abouelmagd**, A. Skjellum. *A Survey of Optimization Approaches for MPI Alltoall and MPI Alltoallv.* **SAI Computing Conference 2025.**
5. **A. A. Abouelmagd**, A. Hilal. *Leveraging the Power of AI and Social Interactions to Restore Trust in Public Polls.* **CSCI 2025.**
6. **A. A. Abouelmagd**, A. Hilal. *Emerging Paradigms for Securing Federated Learning Systems.* **IEEE GCAIoT 2025.**
7. P. H. Chen, A. Bali, S. Yang, P. Haghi, C. Knox, B. Li, **A. A. Abouelmagd**, A. Skjellum, M. Herbordt. *Cycle-Stealing in Load-Imbalanced HPC Applications.* **IEEE HPEC 2024 — Outstanding Student Paper Award.**

## Projects

- **BusTub Database Engine** *(C++)* — Buffer-pool manager with page-replacement policies and a thread-safe LRU-K eviction algorithm for concurrent workloads.
- **CUDA Parallel Softmax** *(C++, CUDA)* — Optimized softmax kernel using shared memory and block-level reduction; throughput scaled via memory coalescing and parallel row-wise processing.
- **Distributed Key-Value Store** *(C++)* — Leader-coordinated store with auto-partitioning, live rebalancing, and Bully-algorithm leader election for zero-data-loss failover.

## Skills

- **Languages:** C/C++, Python, Java, Go
- **Parallel & HPC:** MPI, CUDA, Kokkos, RAJA Performance Suite
- **Systems & Infra:** Kubernetes, Docker, ZooKeeper, MySQL
- **Tools:** Linux, Git, CMake, Makefile

## Awards

- **Top 5** — Graduate Student Research Competition, ACM/IEEE SuperComputing (SC'25)
- **Outstanding Student Paper Award** — IEEE HPEC 2024
- **10th place, AlexCPC** — qualified for the Egyptian Collegiate Programming Contest (2018)
- Cloud DevOps Nanodegree — Udacity

## Contact

- 📧 **Email:** aabouelma42@tntech.edu
- 🎓 **Google Scholar:** https://scholar.google.com/citations?user=FJQIUp4AAAAJ&hl=en
- 💼 **LinkedIn:** https://linkedin.com/in/amroakmal
- 💻 **GitHub:** https://github.com/amroakmal

---

### About this repository

This repo hosts my personal portfolio site — a single self-contained `index.html`
(no build step) served by GitHub Pages. The empty `.nojekyll` file tells Pages to
serve the HTML as-is instead of running a Jekyll build. To update the site, edit the
text in `index.html` directly.

---
permalink: /current-projects/
toc: true
---
## Current Projects

### Agile Hardware/Software Design Methodology

#### Design Space Exploration of CGRA Processing Elements using Peak DSL
**Kathleen Feng**

#### Auto-scheduling Image Processing and DDN Workloads on CGRAs
**Adam Dai**

#### Unified Buffer Halide Compiler and Auto-scheduler
Jeff, Dillon, Adam

#### Lake: Memory DSL
Qiaoyi, Max, Keyi, Taeyoung, Kavya

#### Gemstone: Physical Design Generator
Alex, Raj, Taeyoung, James

#### SoC Generation Framework
Gedeon

#### End-to-end Application Execution
Teguh, Gedeon

### Accelerator Architectures Leveraging Emerging Technologies

#### 3D CGRA Architecture with Hybrid RRAM-NEMS-Based Interconnect
**Akash Levy**  
Programmable logic architectures such as FPGAs and CGRAs are extensively used in place of specialized ASICs to accelerate computationally-intensive algorithms. However, when compared with ASICs performing the same function, FPGAs typically have 10-40x lower logic density, 3-4x higher delay, and 5-12x higher dynamic power dissipation. Most of this overhead comes from the configurable interconnect. This work reduces this overhead by using RRAM-based configuration memory that actuates NEMS-based interconnect multiplexers, both of which can be integrated in 3D on top of silicon CMOS logic. This work also enables “normally off, instantly on” operation, which is critical for IoT devices with unreliable power sources. FPGAs need to load their configuration from off-chip memory on startup, which incurs a significant energy cost. This work leverages the non-volatility of RRAM to enable intermittent computing.

#### One-Shot Learning using RRAM-Based Associative Memory
**Haitong Li**  
Real-time learning from a few examples (one/few-shot learning) is a key challenge for machine learning systems today. When never-seen-before data is encountered, conventional parametric models like DNNs need to re-learn their parameters via gradient-based learning, often requiring huge amount of data coupled with slow learning iterations. Non-parametric models (like nearest neighbours) do not require any training, but have lower accuracy. Recent research has combined the two to create "memory-augmented" neural networks (MANNs) that can rapidly learn new examples while still performing well on common examples. MANNs consist of a frontend, which is a traditional CNN or RNN, that extracts features from new classes, and a backend associative memory that stores a hashed version of these features. During learning, new features are stored in the memory, and during inference, the feature computed on input data is compared with all the features stored in the memory, and the closest match determines the classification result. This work implements an associative memory with an RRAM-based content addressable memory for area-efficient feature storage and fast feature matching. 

#### Chimera: Compute (Immersed) in Memory with Embedded Resistive Arrays
**Kartik Prabhu, Rohan Doshi**  
The scale of deep neural networks (DNNs) trained on increasingly large datasets has rapidly outpaced the amount of memory that can be densely integrated on the same die as compute in conventional CMOS technology. This has created an energy and performance bottleneck at the interface with off-chip DRAM. With a theoretically 12F2 1T1R cell, multi-level capability, and the promise of monolithic 3D integration, resistive RAM (RRAM) offers a new, orthogonal path to significant strides in energy-efficiency and performance of DNN hardware. Driven bottom-up by this emerging technology, we are working on a set of DNN hardware architectures which leverage the density of RRAM in both the near-memory, digital and in-memory, mixed-signal computing contexts.

#### In-Memory Computing Architecture for Probabilistic Graphical Models
**Weier Wan**  
Many powerful neural networks such as probabilistic graphical models and recurrent neural networks require flexibility in dataflow and weight access patterns. This work implements an in-memory computing architecture in a 130-nm CMOS/RRAM process,  that offers dataflow reconfigurability to address the limitations of previous designs. It acheives a runtime reconfigurable dataflow with in-situ access to RRAM array and its transpose for efficient access to neural network weights and a voltage sensing stochastic analog neuron.

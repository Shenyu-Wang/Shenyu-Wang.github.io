---
permalink: /
title: "Shenyu's Academic Pages"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span id="about"></span>

About Me
------------------------
I am a third-year Ph.D. student at the Micro-nano System Center, Fudan University. My research focuses on AI accelerator architectures, energy-efficient hardware computing, and low-power digital circuits.

I am particularly interested in hardware-software co-design for efficient neural network and LLM inference, with an emphasis on reducing memory bottlenecks, improving data reuse, and enabling high-efficiency model deployment on specialized hardware.

<span id="research"></span>

Research Interests
------------------------
**Accelerator Hardware-Software Co-Optimization for LLM and NN Inference**

- Dynamic KV cache storage optimization to alleviate memory bottlenecks in LLM inference.
- Sparse CNN processing architectures with sparsity-aware data reordering for efficient computation and memory access.

**Multi-Modal Speech Processing System Design**

- Millimeter-wave, visual, and audio signal fusion for beyond-line-of-sight speech perception.
- System-level integration and hardware optimization for low-latency, high-accuracy multi-modal speech processing.

Projects
------------------------
**Cross-Stage KV Cache Optimization for LLM Inference** *(ongoing)*

Developing an algorithm-hardware co-design framework to mitigate KV cache bottlenecks in LLM inference through coordinated compression across sequence length, feature dimensionality, and data format.

**Energy-Efficient Visual-Aided Speech Enhancement Processor** *(ongoing)*

Developed a dual-modal processor architecture that leverages visual-audio fusion to achieve high noise tolerance and ultra-low power consumption.

- Proposed redundancy speculation dynamic computing to remove 36.9% redundant operations by adaptively enabling visual fusion.
- Designed a bipolar computing engine to reorder accumulation sequences, reducing toggle rate by 84.7%.
- Fabricated in 22 nm CMOS, achieving 228 uW power consumption and tolerating input noise levels down to -10 dB SNR.

**Beyond-Sparsity CNN Processing Architecture for Edge Devices** *(ongoing)*

Developed a hardware-algorithm co-design framework to enhance sparsity exploitation in CNNs, reducing redundant computation and memory access for energy-efficient edge inference.

- Proposed a beyond-sparsity paradigm to eliminate weak-contribution values in addition to zeros.
- Achieved 65.16% increased sparsity and 79.98% MAC reduction, delivering 14.15 TOPS/W energy efficiency.

**Millimeter-Wave-Based Multi-Modal Real-Time Speech Processing System** *(ongoing)*

Developing a real-time multi-modal speech processing architecture that combines millimeter-wave sensing and audio signals for robust perception under challenging acoustic conditions.

Education
------------------------
**Fudan University**, Shanghai, China    
Ph.D. Candidate in Electronic Information  
*Sep. 2023 - Present*

**Fudan University**, Shanghai, China    
B.Eng. in Electronic Information Science and Technology  
*Sep. 2019 - Jun. 2023*

<span id="publications"></span>

Publications
------------------------
<ol class="publication-list">
  <li>
    <strong>A 54.1-387.5-μW 65-nm Multimodal SoC Integrating a Custom CISC Core for Edge IoT Applications</strong><br>
    Nan Wu, <strong>Shenyu Wang</strong>, Tian Tian, Zhihua Wang, Yanshu Guo, and Hanjun Jiang<br>
    <em>IEEE Transactions on Very Large Scale Integration (VLSI) Systems</em>, vol. 34, no. 6, 2026. [DOI: 10.1109/tvlsi.2026.3670378 / <a href="https://ieeexplore.ieee.org/document/11471281">Link</a>]
  </li>
  <li>
    <strong>CrossKV: Accelerating Large Language Model Inference via Cross-Stage Dynamic Co-Optimization for KV Cache</strong><br>
    Nan Wu, <strong>Shenyu Wang</strong>, Huizheng Wang, Peng Wang, Xiao Liu, Zhihua Wang, Yang Hu, and Hanjun Jiang<br>
    <em>IEEE Transactions on Circuits and Systems I: Regular Papers</em>, vol. 73, no. 7, 2026. [DOI: 10.1109/tcsi.2026.3668423 / <a href="https://ieeexplore.ieee.org/document/11421352">Link</a>]
  </li>
  <li>
    <strong>A 3.64 μJ/frame Visual-Aided Speech Enhancement Processor Tolerating -10 dB SNR Input for Hearing Aids in 22 nm CMOS</strong><br>
    Nan Wu, <strong>Shenyu Wang</strong>, Peng Wang, Heyue Li, Kaiji Liu, Xiao Liu, Yansu Guo, Zhihua Wang, and Hanjun Jiang<br>
    <em>2025 IEEE Asian Solid-State Circuits Conference (A-SSCC)</em>, 2025. [DOI: 10.1109/a-sscc67472.2025.11349465 / <a href="https://ieeexplore.ieee.org/document/11349465">Link</a>]
  </li>
  <li>
    <strong>A 14.15 TOPS/W Energy-Efficient CNN Processing Architecture with Beyond-Sparsity Computing Engine towards Edge Devices</strong><br>
    <strong>Shenyu Wang</strong>, Nan Wu, Tian Tian, Yanshu Guo, Zhihua Wang, Xiao Liu, Fei Chen, and Hanjun Jiang<br>
    <em>IEEE International Midwest Symposium on Circuits and Systems (MWSCAS)</em>, 2025. [DOI: 10.1109/mwscas53549.2025.11244532 / <a href="https://ieeexplore.ieee.org/document/11244532">Link</a>]
  </li>
  <li>
    <strong>A 470 μW and 875 fps Throughput JPEG-LS Accelerator in 65 nm CMOS</strong><br>
    Nan Wu, <strong>Shenyu Wang</strong>, Yaoyu Li, Tian Tian, Yanshu Guo, Zhihua Wang, and Hanjun Jiang<br>
    <em>2024 IEEE International Conference on Integrated Circuits, Technologies and Applications (ICTA)</em>, 2024. [DOI: 10.1109/icta64028.2024.10860422 / <a href="https://ieeexplore.ieee.org/document/10860422">Link</a>]
  </li>
</ol>

<span id="contact"></span>

Contact
------------------------
Email: shenyuwang23@m.fudan.edu.cn  
If you are interested in my work, please feel free to reach out to discuss potential collaborations or exchange research ideas.

---
permalink: /
title: "Shenyu’s Academic Pages"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---



About Me
------------------------
I am a third-year PhD student at the Micro-nano System Center, Fudan University.  My research interests include AI accelerator architectures, energy-efficient and high-performance computing , and very-large-scale integrated digital signal processing, with a particular emphasis on leveraging more efficient computing paradigms and hardware architectures to achieve high-efficiency network model deployment through hardware–software co-design. 



Research Interests
------------------------
**Accelerator Hardware–Software Co-Optimization for LLM and NN Inference**   

- Dynamic KV Cache Storage Optimization to Alleviate Memory Bottlenecks in LLM Inference 
- Sparse CNN Processing Architecture Leveraging Sparsity-Aware Reordering to Optimize Memory Access and Achieve High-Efficiency Computation 

**Multi-Modal Speech Processing System Design**   

- Millimeter-wave, visual and audio signal fusion for beyond-line-of-sight speech perception and real-time multi-modal processing 
- System-level integration and hardware optimization for low-latency, high-accuracy multi-modal speech processing under challenging acoustic conditions   



Projects
------------------------
**Cross-Stage KV Cache Optimization for LLM Inference** *(ongoing)*   
Developed an algorithm–hardware co-design framework to mitigate KV cache bottlenecks in LLM inference through coordinated compression across sequence length, feature dimensionality, and data format.  


**Energy-Efficient Visual-Aided Speech Enhancement Processor** *(ongoing)*  
Developed a **dual-modal processor architecture** that leverages visual–audio fusion to achieve high noise tolerance and ultra-low power consumption.  
- Proposed the first **redundancy speculation dynamic computing** architecture to remove 36.9% redundant operations by adaptively enabling visual fusion  
- Designed a **bipolar computing engine** to reorder accumulation sequences, reducing toggle rate by 84.7% and improving efficiency by 2.51×
- Developed a **multi-domain coding processing element** supporting INT, PoT, and APoT computation, improving efficiency by up to 2.14× and reducing memory access by 16.5%
Fabricated in 22nm CMOS, achieving 228 μW power consumption, 3.23× higher energy efficiency, and tolerating input noise levels down to –10 dB SNR



**Beyond-Sparsity CNN Processing Architecture for Edge Devices** *(ongoing)*   
Developed a hardware–algorithm co-design framework to enhance sparsity exploitation in CNNs, reducing redundant computations and memory accesses for energy-efficient edge inference.  
- Proposed a **beyond-sparsity paradigm** to eliminate weak-contribution values in addition to zeros   
- Designed a **beyond-sparsity processing element** with sparsity-rescheduled memory access to lower dynamic power consumption and memory bandwidth requirements  
- Validated on public datasets and diverse NN models (achieving a **65.16% increase in sparsity** and a **79.98% reduction in MAC operations**, delivering **14.15 TOPS/W** energy efficiency)

  

**Millimeter-Wave-Based Multi-Modal Real-Time Speech Processing System** *(ongoing)*    
Developed a multi-modal real-time speech processing architecture leveraging beyond-line-of-sight millimeter-wave signals to enhance speech perception and robustness.  
- Designed a **real-time speech processing algorithm** that fuses millimeter-wave sensing with audio signals for improved noise resilience and speaker localization
- Optimized hardware architecture for low-latency multi-modal data acquisition and processing
- Implemented and validated the system on a prototype platform, achieving high accuracy and real-time performance under challenging acoustic environments



Education 
------------------------
**Fudan University**, Shanghai, China    
Ph.D. Candidate in Electronic Information  
*Sep. 2023 – Present* 

**Fudan University**, Shanghai, China    
B.Eng. in Electronic Information Science and Technology  
*Sep. 2019 – Jun. 2023*  



Publications
------------------------
- **A 3.64μJ/Frame Visual-Aided Speech Enhancement Processor Tolerating -10dB SNR Input for Hearing Aids in 22nm CMOS**  
  Nan Wu, **Shenyu Wang**, Peng Wang, Heyue Li, Kaiji Liu, Xiao Liu, Zhihua Wang, Hanjun Jiang  
  *IEEE Asian Conference on Solid-State Circuits (ASSCC)*, 2025. [DOI/Link]
- **A 14.15 TOPS/W Energy-Efficient CNN Processing Architecture with Beyond-Sparsity Computing Engine towards Edge Devices**  
  **Shenyu Wang**, Nan Wu, Tian Tian, Yanshu Guo, Zhihua Wang, Xiao Liu, Fei Chen, Hanjun Jiang  
  *IEEE International Midwest Symposium on Circuits and Systems (MWSCAS)*, 2025. [DOI/Link]  
- **A 470 μW and 875 fps Throughput JPEG-LS Accelerator in 65nm CMOS**  
  Nan Wu, **Shenyu Wang**, Yaoyu Li, Tian Tian, Yanshu Guo, Zhihua Wang, Hanjun Jiang  
  *IEEE International Conference on Integrated Circuits, Technologies and Applications (ICTA)*, 2024. [DOI/Link]  



Contact
------------------------
Email: shenyuwang23@m.fudan.edu.cn  
If you are interested in our work, please feel free to reach out to discuss potential collaborations or to exchange research ideas! 


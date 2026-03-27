---
permalink: /
title: "Home"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm an assistant researcher in Ant Research, working with [Dr. Mingzhe Zhang](https://mingzhe-zhang.github.io/). I got my Ph.D. degree from the Institute of Computing Technology, Chinese Academy of Sciences (ICT, CAS) in 2024, co-advised by [Dr. Huimin Cui](https://cuihuimin.github.io/) and [Dr. Chenxi Wang](https://wangchenxi7.github.io/home/). I got my Bachelor degree from University of Chinese Academy of Sciences (UCAS) in 2018.

Research Interests
====
My research interest is to build hard-core system/runtime for new hardware and new application, such as non-volatile memory, resource-disaggregated datacenter, FHE accelerators and FHE applications.

**System Support for FHE**

Fully Homomorphic Encryption (FHE) is a promising solution for privacy-preserving computation. However, the huge data amplification in FHE introduces severe storage I/O bottlenecks, which are often overlooked.
I analyze the impact of storage I/O on FHE performance [\[APPT'25\]](https://arxiv.org/abs/2511.04946), revealing that I/O can degrade the performance of FHE accelerators by orders of magnitude. I am exploring solutions from system perspectives to mitigate this bottleneck.

**Runtime for Hybrid Memory**

Non-volatile memory (NVM) was developed to meet the rapidly growing memory demands of data-intensive applications. Compared to DRAM, NVM provides significantly larger storage capacity, lower cost, and higher energy efficiency. However, NVM also exhibits longer access latencies and lower read/write bandwidths. Consequently, cloud infrastructures often adopt a hybrid approach by deploying NVM together with DRAM.
To maximize energy savings and minimize the performance impact of hybrid memory,
I build a runtime [\[TOCS'22\]](https://dl.acm.org/doi/full/10.1145/3511211)  to manage the data layout for cloud applications, which can identify data's hot/cold characteristics and allocate (and migrate) the data into DRAM/NVM accordingly.

**Runtime for Disaggregated Memory**

As an emerging datacenter architecture, resource disaggregation seeks to reorganize each type of datacenter hardware into dedicated resource servers. This approach aims to enhance resource utilization, improve fault tolerance, and simplify the adoption of hardware. These servers are interconnected through advanced network fabrics, such as Infiniband and CXL. Consequently, cloud applications running on these disaggregated clusters can access compute and memory resources from different servers.
I build a hybrid data plane [\[OSDI'24\]](https://www.usenix.org/conference/osdi24/presentation/chen-lei) that simultaneously enables accesses to disaggregated memory via both kernel path and runtime path to provide high efficiency for real-world applications.


Publications
====

+ [A GPU Memory Allocator with Device-Side Page Table Materialization and Deferred TLB Coherence](https://www.usenix.org/conference/osdi26) 

   Yangyu Zhang, **Lei Chen**, Chunwei Xia, Shuaijiang Li, Shuoming Zhang, Zhicheng Li, Qianqi Sun, Jiawei Xiao, Ruiyuan Xu, Ao Chen, Guangli Li, Xiaobing Feng, Huimin Cui, Chenxi Wang, Jiacheng Zhao

   The USENIX Symposium on Operating Systems Design and Implementation (OSDI), 2026

+ [From Threads to Tiles: T2T, a Compiler for CUDA-to-NPU Translation via 2D Vectorization](https://2026.cgo.org/details/cgo-2026-papers/32/From-Threads-to-Tiles-T2T-a-Compiler-for-CUDA-to-NPU-Translation-via-2D-Vectorizati) (**Distinguished Paper Award**)

   Shuaijiang Li, Jiacheng Zhao, Ying Liu, Shuoming Zhang, **Lei Chen**, Yijin Li, Yangyu Zhang, lizhicheng , Runyu Zhou, Xiyu Shi, Chunwei Xia, Yuan Wen, Xiaobing Feng, Huimin Cui

   International Symposium on Code Generation and Optimization (CGO), 2026

+ [An Efficient and Scalable Hardware Architecture for Number Theoretic Transform on FPGA with Design Automation](https://2026.hpca-conf.org/details/hpca-2026-main-conference/84/An-Efficient-and-Scalable-Hardware-Architecture-for-Number-Theoretic-Transform-on-FPG)

   Yilan Zhu, Geng Yang, Xingyu Tian, Dilshan Kumarathunga, Liang Kong, Xianglong Deng, Shengyu Fan, Guang Fan, Guiming Shi, **Lei Chen**, Bo Zhang, Yisong Chang, Shoumeng Yan, Zhenman Fang, Mingzhe Zhang

   IEEE International Symposium on High-Performance Computer Architecture (HPCA), 2026

+ [The Future of Fully Homomorphic Encryption System: from a Storage I/O Perspective](https://arxiv.org/abs/2511.04946)

   **Lei Chen**, Erci Xu, Yiming Sun, Shengyu Fan, Xianglong Deng, Guiming Shi, Guang Fan, Liang Kong, Yilan Zhu, Shoumeng Yan, Mingzhe Zhang

   Advanced Parallel Processing Technology (APPT), 2025

+ [HAWK: Fully Homomorphic Encryption Accelerator with Fixed-Word Key Decomposition Switching](https://dl.acm.org/doi/full/10.1145/3725843.3756123)

   Liang Kong, Shengyu Fan, Xianglong Deng, **Lei Chen**, Guang Fan, Guiming Shi, Yilan Zhu, Geng Yang, Shoumeng Yan, Mingzhe Zhang

   IEEE/ACM International Symposium on Microarchitecture (MICRO), 2025


+ [A Tale of Two Paths: Toward a Hybrid Data Plane for Efficient Far-Memory Applications](https://www.usenix.org/conference/osdi24/presentation/chen-lei)

   **Lei Chen**, Shi Liu (co-first), Chenxi Wang, Haoran Ma, Yifan Qiao, Zhe Wang, Chenggang Wu, Youyou Lu, Xiaobing Feng, Huimin Cui, Shan Lu, and Harry Xu

   The USENIX Symposium on Operating Systems Design and Implementation (OSDI), 2024
   \[[paper](https://www.usenix.org/system/files/osdi24-chen-lei.pdf)\]\[[code](https://github.com/wangchenxi7/Atlas)\]

+ [Unified Holistic Memory Management Supporting Multiple Big Data Processing Frameworks over Hybrid Memories](https://dl.acm.org/doi/full/10.1145/3511211)

  **Lei Chen**, Jiacheng Zhao, Chenxi Wang, Ting Cao, John Zigman, Haris Volos, Onur Mutlu, Fang Lv, Xiaobing Feng, Harry Xu, Huimin Cui

  ACM Transactions on Computer Systems (TOCS), 2022
  \[[paper](https://dl.acm.org/doi/pdf/10.1145/3511211)\]
  


Awards
====
+ 2026 CGO Distinguished Paper
+ 2024 ChinaSys Best Spotlight Paper









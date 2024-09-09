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

**Runtime for Hybrid Memory**

Non-volatile memory (NVM) was developed to meet the rapidly growing memory demands of data-intensive applications. Compared to DRAM, NVM provides significantly larger storage capacity, lower cost, and higher energy efficiency. However, NVM also exhibits longer access latencies and lower read/write bandwidths. Consequently, cloud infrastructures often adopt a hybrid approach by deploying NVM together with DRAM.
To maximize energy savings and minimize the performance impact of hybrid memory,
I build a runtime [\[TOCS'22\]](https://dl.acm.org/doi/full/10.1145/3511211)  to manage the data layout for cloud applications, which can identify data's hot/cold characteristics and allocate (and migrate) the data into DRAM/NVM accordingly.

**Runtime for Disaggregated Memory**

As an emerging datacenter architecture, resource disaggregation seeks to reorganize each type of datacenter hardware into dedicated resource servers. This approach aims to enhance resource utilization, improve fault tolerance, and simplify the adoption of hardware. These servers are interconnected through advanced network fabrics, such as Infiniband and CXL. Consequently, cloud applications running on these disaggregated clusters can access compute and memory resources from different servers.
I build a hybrid data plane [\[OSDI'24\]](https://www.usenix.org/conference/osdi24/presentation/chen-lei) that simultaneously enables accesses to disaggregated memory via both kernel path and runtime path to provide high efficiency for real-world applications.


Publications
====
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
+ 2024 ChinaSys Best Spotlight Paper (5/54)









---
layout: archive
permalink: /
title: "Homepage"
author_profile: true
classes: wide
---

## Biography
<p style="text-align: justify;">I graduated from Northwestern Polytechnical University (Xi’an) with a bachelor's degree in Electric Engineering in 2012 and from Peking University (Beijing) with a doctoral degree in Microelectronics in 2018. After that, I joined the Institute of Computing Technology, Chinese Academy of Sciences in 2018 and was promoted to associate professor in 2021. With more than ten years of experience in Electric Engineering, now I’m doing research in the field of computer architecture, which is a thriving field aiming to make better use of electric devices and circuits. I have experiences in making various prototypes such as a Monte Carlo device simulator, an Open-Accelerator-Module-based Compute-in-Memory server system, an edge AI computing system and so on. My research interest includes disaggregated memory system, binary translation for heterogenerous computing and LLM edge computing system.</p>

## Research Interest
<div align="center">
  <img src="https://yinlongsan.github.io/images/ResearchInterest.jpg" alt="描述" width="400">
</div>
  
- Disaggregated memory system
<p style="text-align: justify;">Distributed memory is considered a cornerstone technology for next-generation cloud data centers, and is expected to completely solve the "memory wall" problem. In this technology, an independent, scalable memory resource pool in computing systems is formed by decoupling memory resources tightly coupled to computing units such as CPU. This memory resource pool provides on-demand, transparent memory access capabilities to all compute units via high-speed networks such as Remote Direct Memory Access (RDMA)、Peripheral Component Interconnect Express（PCIe）、Compute Express Link（CXL）and so on. In this scenario, compute nodes no longer monopolize their local memories but can access arbitrary memory resources through the network/interconnect with low latency, which just as if it were local memory. This will enable global sharing and flexible scheduling of memory resources and make computing system upgrading more effective. However, there are also significant challenges that need to be overcome. Network/Interconnect transmission latency is significantly higher than local memory access. This requires complex system software and runtime support to eliminate the impact. What’s more，the resource management and scheduling are more complex in disaggregate memory systems than traditional computing systems, requiring efficient handling of issues such as global memory allocation, data consistency, fault tolerance, and fault isolation.</p>

- Binary translation for heterogenerous computing

- LLM edge computing system

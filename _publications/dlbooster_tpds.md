---
title: "Accelerating End-to-End Deep Learning Workflows with Codesign of Data Preprocessing and Scheduling"
collection: publications
permalink: /publication/dlbooster_tpds
excerpt: 'This paper presents the codesign of data preprocessing and computation scheduling for end-to-end DL worklow optimizations'
date: 2020-12-01
venue: 'IEEE Transactions on Parallel and Distributed Systems: Special Section on Parallel and Distributed Computing Techniques for AI, ML, and DL (IEEE TPDS-SS-AI)'
paperurl: '/publication/dlbooster_tpds'
citation: 'Yang Cheng, Dan Li, Zhiyuan Guo, Binyao Jiang, Jinkun Geng, Jiaxin Lin, Xi Fan, Xinyi Yu, Wei Bai, Lei Qu, Ran Shu, Peng Cheng, Yongqiang Xiong, and Jianping Wu. "Accelerating End-to-End Deep Learning Workflows with Codesign of Data Preprocessing and Scheduling", IEEE Transactions on Parallel and Distributed Systems: Special Section on Parallel and Distributed Computing Techniques for AI, ML, and DL (IEEE TPDS-SS-AI), accepted'
---

# Introductions

<div style="text-align:justify; text-indent:1em;"> 
This paper investigates the performance bottleneck of existing deep learning (DL) systems and proposes DLBooster to improve the running  efficiency of deploying DL applications on GPU clusters.
At its core, DLBooster leverages two-level optimizations to boost the end-to-end DL workflow.
On the one hand, DLBooster selectively offloads some key decoding workloads to FPGAs  to provide high-performance online data preprocessing services to the computing engine.
On the other hand, DLBooster reorganizes the computational workloads of training neural networks with the backpropagation algorithm and schedules them according to their dependencies  to improve the utilization of GPUs at runtime.
Based on our experiments, we demonstrate that compared with baselines, DLBooster can improve the image processing throughput by 1.4$\times$ -- 2.5$\times$  and reduce the processing latency by 1/3 in several real-world DL applications and datasets. 
Moreover, DLBooster consumes less than 1 CPU core to manage FPGA devices at runtime, which is at least 90\% less than the baselines in some cases. DLBooster shows its potential to accelerate DL workflows in the cloud.
</div>
[Read More ... ](/publication/dlbooster_tpds)


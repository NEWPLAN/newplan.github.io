---
title: "Quick NAT: High performance NAT system on commodity platforms"
collection: publications
permalink: /publication/2017-06-QuickNet-title-number-1
excerpt: 'This paper presents the optimizations for existing Network Address Translation (NAT) systems, based on DPDK'
date: 2017-06-01
venue: '23th IEEE International Symposium on Local and Metropolitan Area Networks (LANMAN 2017), Osaka, Japan, June.'
paperurl: '/publication/2017-06-QuickNet-title-number-1'

citation: 'Junfeng Li, Dan Li, Yukai Huang, Yang Cheng, and Ruilin Ling, "Quick NAT: High performance NAT system on commodity platforms". 23th IEEE International Symposium on Local and Metropolitan Area Networks (LANMAN 2017), June, 2017, Osaka, Japan.'
---

Authors: Junfeng Li, Dan Li, Yukai Huang, <es style="font:blod">Yang Cheng </es>, and Ruilin Ling
<div style="text-align:justify; text-indent:1em;">
NAT gateway is an important network system in today’s IPv4 network when translating a private IPv4 address to a public address. However, traditional NAT system based on Linux Netfilter cannot achieve high network throughput to meet modern requirements, such as data centers. To address this challenge, we improve the network performance of NAT system by three ways. (1) we leverage DPDK to enable polling and zero-copy delivery, so as to reduce the cost of interrupt and packet copies. (2) we enable multiple CPU cores to process in parallel and use lockfree hash table to minimize the contention between CPU cores. (3) we use hash search instead of sequential search when looking up the NAT rule table. Evaluation shows that our Quick NAT system significantly improves the performance of NAT on commodity platforms
</div>

[Download paper here](https://chengyang.info/me/pdfs/Quick-NAT-lanman-paper.pdf)

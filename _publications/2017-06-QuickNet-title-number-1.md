---
title: "Quick NAT: High performance NAT system on commodity platforms"
collection: publications
permalink: /publication/2017-06-QuickNet-title-number-1
excerpt: 'NAT gateway is an important network system in today’s IPv4 network when translating a private IPv4 address to a public address. However, traditional NAT system based on Linux Netfilter cannot achieve high network throughput to meet modern requirements such as data centers. To address this challenge, we improve the network performance of NAT system by three ways. First, we leverage DPDK to enable polling and zero-copy delivery, so as to reduce the cost of interrupt and packet copies. Second, we enable multiple CPU cores to process in parallel and use lockfree hash table to minimize the contention between CPU cores. Third, we use hash search instead of sequential search when looking up the NAT rule table. Evaluation shows that our Quick NAT system significantly improves the performance of NAT on commodity platforms'
date: Jun., 2017
venue: '[LANMAN 2017] 23th IEEE International Symposium on Local and Metropolitan Area Networks'
paperurl: 'https://chengyang.info/me/pdfs/Quick-NAT-lanman-paper.pdf'

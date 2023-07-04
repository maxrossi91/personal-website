---
title: 'Invited speaker at Pangenomics Bio Hacking 2021'
date: 2021-11-23
permalink: /posts/2021/11/PangenomicsBioHacking/
tags:
  - PangenomicsBio Hacking
  - Invited Speaker
  - Conference
---

I will be an invited speaker at the [Pangenomics Bio Hacking 2021](https://pgbh2021.pangenome.eu/) and I will talk about my recent work on pangenomics.

MONI is a pangenomic index for finding maximal exact matches (MEMs), that is built on top of the r-index but also includes auxiliary data structures to allow finding approximate matches on a pangenomic scale. It includes many open-source tools and data structures such as BigBWT, BigRePair, and SDSL. I will talk about MONI, which is written in C++ and freely available at [https://github.com/maxrossi91/moni](https://github.com/maxrossi91/moni).

I will present the organization of the source code and the structural choices behind MONI, the challenges of integrating all third-party open-source components, and the data-structure designs and organization strategies we used for handling large-scale data. In particular I will show how functionally equivalent implementations of the same component may drastically affect performance, even though their asymptotic complexity is the same.
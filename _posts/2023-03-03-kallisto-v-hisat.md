---
layout: post
title: Kallisto v HiSat
date: ‘2023-03-03’
categories: e5
tags: RNA-seq
---

In attempting to get quick comparison of alignment across genome, the question arises what is the difference (and accuracy) of kallisto (psuedo-align) and hisat. Spoiler - I was quite surprised with hisat w and w/o gtf. This is A pulcra RNA-seq data....

TLDR


| Genome             | kallisto                                  | HiSat                         | HiSat no splice               | Col5 | Col6 |
|------------|------------|------------|------------|------------|------------|
| Amil_v2.1          | "p_pseudoaligned": 84.9, "p_unique": 82.2 | 76.02% overall alignment rate | 76.00% overall alignment rate |      |      |
| Adig_1.1           | "p_pseudoaligned": 72.8,"p_unique": 69.8  |                               |                               |      |      |
| Ahyacinthus.chrsV1 | "p_pseudoaligned": 82.1,"p_unique": 80.4  | 57.46% overall alignment rate | 68.10% overall alignment rate |      |      |

---
sidebar: toc
title: Agile and evolvable software construction in the era of rapidly evolving hardware accelerator designs
author: Charith Mendis, UIUC
tagline: Tuesday, November 4, 2025 2PM ET
zoomreg: https://mit.zoom.us/meeting/register/usEVbrerRu2bWr599mFBxQ
date: 2025-11-04
eleventyComputed:
  eleventyNavigation:
    parent: Fastcode Seminar
    key: Charith Mendis
    order: 2
tags:
 - seminar
---

## Abstract

Modern AI workloads have become exceedingly abundant and important in the current computing landscape. As a result, there have been numerous software and hardware innovations aimed at accelerating these workloads. However, we observe a subtle disconnect between the software and hardware communities. Most software innovations target well-established hardware platforms such as CPUs (e.g., x86, ARM) and GPUs (e.g., NVidia GPUs), while hardware innovations produce plenty of other tensor accelerator designs (e.g., Gemmini, Feather) each year.

We asked the question, why aren’t the software community using these accelerators or even evaluating on them? The simple yet undeniable reason is the lack of standardized software tooling compared to CPUs and GPUs. For an architecture to be used, properly designed compiler backends, correctness, and performance testing tools should be abundant (e.g., CUDA ecosystem).

In this talk, I will describe how we bridge this gap by automatically generating the necessary software tools for a large class of accelerators through the [Accelerator Compiler Toolkit](https://adapt.cs.illinois.edu/index.html) (ACT) ecosystem. Central to ACT is an ISA definition language, TAIDL, that for the first time standardizes the hardware-software interfaces for a large class of accelerators. Departing from the traditional approach of manually constructing test oracles, performance models, or retargetable compiler backends, we instead introduce agile and evolvable methodologies to automatically generate such necessary tooling using both formal methods and machine learning techniques for any TAIDL-defined accelerator interface. I will show how such automation enables rapid software prototyping, making rapidly evolving accelerator designs usable by the software community.

## Bio

Charith Mendis is an Assistant Professor in the Siebel School of Computing and Data Science at the University of Illinois at Urbana-Champaign. His broad research interests are at the intersection of compilers, programming languages and machine learning. He received his PhD and Master’s from the Massachusetts Institute of Technology and his BSc from the University of Moratuwa. He is the recipient of the DARPA Young Faculty Award, the NSF CAREER Award, the Google ML and Systems Junior Faculty Award, the Outstanding Advisor award at UIUC, the William A. Martin outstanding master’s thesis award at MIT and the university Gold Medal for his BSc. He has won numerous paper awards including a Distinguished Paper Award at POPL, a Best Student Paper Award at the IEEE BigData conference, an honorable mention for the Best Artifact Award at SIGMOD, a Best Paper Award at ML for Systems workshop at ISCA and an IEEE Top Picks Honorable Mention.
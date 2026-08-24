---
title: "Study Notes: The ABCs of Social Network Analysis"
collection: essays
permalink: /essays/2026-sna-abcs
excerpt: 'A beginner-friendly note on social network analysis: adjacency matrices and connection tables, four classic centrality measures, and a step-by-step walkthrough of a real SNA study on collaboration patterns among Chinese economists.'
date: 2026-08-24
---

This is a short note I wrote in August 2026 while learning social network analysis (SNA) from scratch. I had no background in the topic, so the note starts with the two most basic data structures — the adjacency matrix and the connection table — then introduces the four classic centrality measures (degree, closeness, betweenness, and eigenvector centrality) with their formulas and a hand-worked example.

To show what a standard SNA workflow looks like in practice, I walk through Horvath et al. (2022), *Social Network Analysis of Collaboration Patterns among Economists in China Based on Chinese- and English-language Publications* (SSRN Working Paper 4200232). The paper is a good case study: it builds university-level and individual-level collaboration networks, examines macro characteristics (connectivity, the small-world effect) and micro characteristics (centrality, assortativity, core–periphery structure), and links network position to publication quality. I found the "985 universities in the core" pattern and the superstar-economist small-world structure particularly intuitive illustrations of what SNA can reveal.

The note is written for readers who know literally nothing about SNA. I plan to update it later with programming details (Stata/R/Python) and more advanced techniques.

**[View PDF](https://LeiLi-Econ.github.io/files/sna-abcs-notes.pdf)**

## Abstract

This document is a very brief note on social network analysis (SNA). It introduces a few of the most fundamental concepts of SNA, then explains the standard SNA workflow through an interesting paper. This is the first document of this series; I plan on updating the note with programming details and advanced techniques. Please note that this document is only suitable for those who know literally nothing about SNA.

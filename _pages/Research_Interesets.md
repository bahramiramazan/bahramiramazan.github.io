---
title: "Research Interests"
permalink: /research/
layout: page
---

## Overview

Analogies have fascinated me since my PhD. I want to understand how humans come up with analogies, and how we can make LLMs better at it.

> **What is an analogy?**
> In simple terms, an analogy is *relation similarity* across two different contexts or domains. One way to represent this is with directed graphs, where the relations in each domain are the edges of a corresponding graph.
>
> ![Example domains as colored multigraphs: the solar system (a) is like the hydrogen atom (b).](/images/logics-03-00012-g001.png)
> *Example domains as colored multigraphs: the solar system (a) is like the hydrogen atom (b). Figure from Ott et al. (2025).*

My own work so far includes computational models for classifying relation similarity between words or entities (outperforming the state of the art on all benchmarks I tested), and a benchmark based on graph isomorphisms for evaluating the reasoning abilities of LLMs. See [Selected Publications](#selected-publications) below.

## Research Interests

All of my interests are rooted in analogy and analogical reasoning.

### 1. ML techniques for relation classification in text

Current models are limited by the fixed set of relation labels in existing benchmarks. I am interested in unsupervised approaches in which relations are learned directly from textual contexts, without labeled data. I already have motivation and proof-of-concept results for this direction.

### 2. Improving analogy generation in LLMs for education

Analogies are one of the best ways to explain complex phenomena in simple, understandable language, yet generating good analogies with LLMs has received little attention. I have a clear motivation and an initial proof of concept. The plan is to take existing word-analogy benchmarks, augment them creatively, and train an LLM with reinforcement learning (e.g. GRPO), with evaluation by human annotators.

The resulting model is intended to be used in an online university entrance exam preparation platform, set up by former colleagues of mine for students from Afghanistan, where AI helps learners study and prepare for their exams: [yar.bamaa.org](https://yar.bamaa.org/en).

### 3. Analogies for brainstorming and scientific idea generation

The "AI scientist" is an emerging research area, and I believe analogies can have a significant impact on scientific idea generation. This is the idea I am most excited about for my future research. So far I have done a preliminary study of the field and some exploratory experiments with LLMs: I prompt agents to first construct a knowledge graph of current research, move that graph into an abstract space, and then use the triples of the abstracted graph to find analogical cases.

## Selected Publications

- **Bahrami, R. A.** and Yahyapour, R. "Graph Mapping and LLM Thinking Speed." *INLG 2026* (accepted). [PDF](https://bahramiramazan.github.io/assets/pdf/Final_INLG_GM.pdf) · [Code](https://github.com/bahramiramazan/graphmapping)
- **Bahrami, R.** and Yahyapour, R. "Re-Representation in Sentential Relation Extraction with Sequence Routing Algorithm." *ICNLSP 2025*, pp. 315-327.

More code and material on [GitHub](https://github.com/bahramiramazan).
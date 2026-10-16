---
layout: page
permalink: /research_Interests/
title: research interests
description: My research is rooted in analogy and analogical reasoning.
nav: true
nav_order: 2
---

## Overview

Analogies have fascinated me since my PhD. I want to understand how humans come up with analogies, and how we can make LLMs better at it.

> **What is an analogy?**
> In simple terms, an analogy is _relational similarity_ across two different contexts or domains. One way to represent this is with directed graphs, where the relations in each domain are the edges of a corresponding graph.
{: .block-tip }

<!-- Adjust the image size here: change the width value (e.g. 40%, 60%, 80%, 400px) -->
<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.liquid loading="eager" path="assets/img/logics-03-00012-g001.png" class="img-fluid rounded z-depth-1" style="width: 60%;" zoomable=true %}
    </div>
</div>
<div class="caption">
    Example domains as colored multigraphs: the solar system (a) is like the hydrogen atom (b). Figure from Ott et al. (2025).
</div>
My work so far includes computational models for classifying relational similarity between words or entities, which outperform the state of the art on all benchmarks I tested, and a benchmark based on graph isomorphisms for evaluating the reasoning abilities of LLMs. See [Selected Publications](#selected-publications) below.

---

## Research Interests



### 1. ML techniques for relation classification in text

Current models are limited by the fixed set of relation labels in existing benchmarks. I am interested in unsupervised approaches in which relations are learned directly from textual contexts, without labeled data. I already have the motivation and proof-of-concept results for this direction.

### 2. Improving analogy generation in LLMs for education

Analogies are one of the best ways to explain complex phenomena in simple language, yet generating good analogies with LLMs has received little attention. I have a clear motivation and an initial proof of concept. The plan is to take existing word-analogy benchmarks, augment them creatively, and train an LLM with reinforcement learning (e.g., GRPO), with evaluation by human annotators.

The resulting model is intended for an online university entrance exam preparation platform, set up by former colleagues of mine for students from Afghanistan, where AI helps learners study and prepare for their exams: [yar.bamaa.org](https://yar.bamaa.org/en).

### 3. Analogies for brainstorming and scientific idea generation

The "AI scientist" is an emerging research area, and I believe analogies can have a significant impact on scientific idea generation. This is the idea I am most excited about for my future research. So far, I have done a preliminary study of the field and some exploratory experiments with LLMs. In these experiments, I prompt agents to first construct a knowledge graph of current research, move that graph into an abstract space, and then use the triples of the abstracted graph to find analogical cases.


---

## Importance of Analogy in Everyday Conversation

Analogy, where my background lies, plays an important role in conversation. Logic, another aspect of analogical reasoning, can also improve the reasoning of individual agents, and I am familiar with its use in LLMs. I elaborate on both below.

### Analogies at the heart of everyday communication

Analogies are part of our everyday communication, and we are especially inclined to use them when they help us convey our true intention, narrative, or understanding of a matter. The example below is taken from Gentner (2012). It comes from a discussion of a 2002 decision by a US judge ordering Microsoft to include Java as part of its operating system, and it shows how common analogies are in everyday discussions.

> **Examples of analogy in everyday discussions**
>
> One writer wrote: "Please explain to me why Microsoft should be forced to include third-party software in their OS? Every time I buy a six-pack of Coke, should a can of Pepsi be included?" and another wrote, "That would be like (my attorney) being forced to refer clients to his competition, since they didn't have as much business as him." Defending the decision, another writer wrote, "If Ford had a monopoly on cars, they certainly would not be allowed to sell their cars with only Ford-brand radios and tires..."



---

## What I Hope to Contribute and Learn

I am always looking for opportunities to learn from colleagues while contributing meaningfully to the work, and I am open to collaboration.


## Selected Publications

- **Bahrami, R. A.** and Yahyapour, R. "Graph Mapping and LLM Thinking Speed." _INLG 2026_ (accepted). [PDF](https://bahramiramazan.github.io/assets/pdf/Final_INLG_GM.pdf) · [Code](https://github.com/bahramiramazan/graphmapping)
- **Bahrami, R.** and Yahyapour, R. "Re-Representation in Sentential Relation Extraction with Sequence Routing Algorithm." _ICNLSP 2025_, pp. 315–327.

More code and material on [GitHub](https://github.com/bahramiramazan).
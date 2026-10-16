---
layout: page
permalink: /research_profile/
title: Research Profile
description: Exploring computational models of analogy, structural reasoning, and generative AI.
nav: true
nav_order: 2
---

<div class="row align-items-center my-4">
  <div class="col-md-12">
    <p class="lead">
      My research centers on <strong>analogy and analogical reasoning</strong>. I bridge computational linguistics, graph neural networks, and modern Large Language Models (LLMs) to understand how structural relations can be represented, reasoned over, and generated automatically.
    </p>
  </div>
</div>

---

## <i class="fa-solid fa-compass me-2"></i>Research Overview

Analogical reasoning—the human capability to recognize relational similarities between distinct domains—is foundational to cognition, abstract thinking, and problem-solving. My research focuses on formalizing these processes for machine learning models.

{% stroke_box title="What is an Analogy?" %}
In computational terms, an **analogy** represents <em>relational similarity across distinct domains</em>. We can formalize domains as directed, multi-relational graphs, where entities form nodes and conceptual relationships represent edges.
{% endstroke_box %}

<div class="card my-4 border-0 shadow-sm">
  <div class="card-body bg-light text-center rounded p-4">
    {% include figure.liquid loading="eager" path="assets/img/logics-03-00012-g001.png" class="img-fluid rounded z-depth-1" style="max-width: 65%;" zoomable=true %}
    <div class="caption text-muted mt-2 small">
      <strong>Figure 1:</strong> Relational structures as colored multigraphs demonstrating the classic structural alignment between the solar system (a) and the hydrogen atom (b). <em>(Figure adapted from Ott et al., 2025)</em>.
    </div>
  </div>
</div>

My work spans **state-of-the-art relation similarity classification** (outperforming existing benchmarks) and **graph-isomorphism benchmarks** designed to stress-test abstract reasoning in state-of-the-art LLMs.

---

## <i class="fa-solid fa-lightbulb me-2"></i>Core Focus Areas

<div class="row g-4 my-2">

  <div class="col-md-12">
    <div class="card h-100 border-start border-4 border-primary shadow-sm">
      <div class="card-body">
        <h3 class="h5 card-title text-primary"><i class="fa-solid fa-diagram-project me-2"></i>1. Machine Learning for Unsupervised Relation Classification</h3>
        <span class="badge bg-primary mb-2">Computational Linguistics</span>
        <span class="badge bg-secondary mb-2">Graph ML</span>
        <p class="card-text">
          Existing benchmarks rely on rigid, pre-defined sets of relation labels. My work focuses on <strong>unsupervised relation learning</strong>, extracting rich relational representations directly from unstructured textual contexts without reliance on human-labeled data.
        </p>
      </div>
    </div>
  </div>

  <div class="col-md-12">
    <div class="card h-100 border-start border-4 border-success shadow-sm">
      <div class="card-body">
        <h3 class="h5 card-title text-success"><i class="fa-solid fa-graduation-cap me-2"></i>2. Analogy Generation in LLMs for Educational Technology</h3>
        <span class="badge bg-success mb-2">RL / Alignment</span>
        <span class="badge bg-secondary mb-2">EdTech</span>
        <p class="card-text">
          Analogies are critical for making abstract concepts intuitive. I am developing methodologies that combine creative augmentation of word-analogy benchmarks with preference alignment via Reinforcement Learning (e.g., GRPO/DPO) and human evaluation.
        </p>
        <div class="p-2 bg-light rounded mt-2 border">
          <small><i class="fa-solid fa-heart me-1 text-danger"></i> <strong>Applied Impact:</strong> Integrating these models into an AI-powered study platform for students in resource-constrained regions (<a href="https://yar.bamaa.org/en" target="_blank" rel="noopener noreferrer">yar.bamaa.org</a>).</small>
        </div>
      </div>
    </div>
  </div>

  <div class="col-md-12">
    <div class="card h-100 border-start border-4 border-warning shadow-sm">
      <div class="card-body">
        <h3 class="h5 card-title text-warning"><i class="fa-solid fa-robot me-2"></i>3. Analogies for AI-Driven Scientific Discovery</h3>
        <span class="badge bg-warning text-dark mb-2">LLM Agents</span>
        <span class="badge bg-secondary mb-2">Knowledge Graphs</span>
        <p class="card-text">
          Targeting the emerging field of "AI Scientists", I investigate how LLMs can formulate novel hypotheses via analogy. By translating domain-specific literature into abstract knowledge graphs, LLM agents can perform cross-domain mapping to generate novel research ideas.
        </p>
      </div>
    </div>
  </div>

</div>

---

## <i class="fa-solid fa-comments me-2"></i>Cognitive Foundations & Logical Reasoning

<div class="row align-items-center">
  <div class="col-md-12">
    <h3>Analogical Mapping in Communication</h3>
    <p>
      Analogy is deeply embedded in human dialogue and argumentative discourse. It allows speakers to map structural logic from familiar domains to complex or disputed topics.
    </p>

    <blockquote class="blockquote border-start border-3 ps-3 my-3 text-muted" style="font-size: 0.95rem;">
      <p><em>"Please explain to me why Microsoft should be forced to include third-party software in their OS? Every time I buy a six-pack of Coke, should a can of Pepsi be included?"</em></p>
      <footer class="blockquote-footer">Analogy in public discourse regarding Microsoft antitrust cases <cite title="Source Title">(Gentner, 2012)</cite></footer>
    </blockquote>

    <h3 class="mt-4">Formal Logic & Spatial Contexts</h3>
    <p>
      Beyond text generation, formal logic and spatial reasoning are vital for grounded AI systems. In multi-modal environments and spatial navigation tasks (e.g., Kranti et al., 2025), language models must adhere to underlying environmental constraints and logical axioms to reason effectively.
    </p>
  </div>
</div>

---

## <i class="fa-solid fa-book-bookmark me-2"></i>Selected Publications

<div class="list-group list-group-flush shadow-sm rounded border">
  
  <div class="list-group-item p-3">
    <div class="d-flex w-100 justify-content-between align-items-center">
      <h5 class="mb-1 text-primary">Graph Mapping and LLM Thinking Speed</h5>
      <span class="badge bg-primary rounded-pill">INLG 2026 (Accepted)</span>
    </div>
    <p class="mb-1"><strong>Bahrami, R. A.</strong> and Yahyapour, R.</p>
    <div class="mt-2">
      <a href="https://bahramiramazan.github.io/assets/pdf/Final_INLG_GM.pdf" class="btn btn-sm btn-outline-danger" target="_blank"><i class="fa-solid fa-file-pdf me-1"></i> Paper PDF</a>
      <a href="https://github.com/bahramiramazan/graphmapping" class="btn btn-sm btn-outline-dark ms-1" target="_blank"><i class="fa-brands fa-github me-1"></i> Code Repository</a>
    </div>
  </div>

  <div class="list-group-item p-3">
    <div class="d-flex w-100 justify-content-between align-items-center">
      <h5 class="mb-1 text-primary">Re-Representation in Sentential Relation Extraction with Sequence Routing Algorithm</h5>
      <span class="badge bg-secondary rounded-pill">ICNLSP 2025</span>
    </div>
    <p class="mb-1"><strong>Bahrami, R.</strong> and Yahyapour, R. (pp. 315–327)</p>
  </div>

</div>

<div class="text-end mt-3">
  <a href="https://github.com/bahramiramazan" class="text-decoration-none fw-bold" target="_blank">
    View complete codebase on GitHub <i class="fa-solid fa-arrow-right ms-1"></i>
  </a>
</div>
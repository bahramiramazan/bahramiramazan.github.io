---
layout: page
permalink: /research_profile/
title: Research Profile
description: Exploring computational models of analogy, structural reasoning, and generative AI.
nav: true
nav_order: 2
---

<!-- Hero Summary Header -->
<div class="card border-0 bg-light shadow-sm my-4">
  <div class="card-body p-4">
    <p class="lead mb-0 text-dark" style="font-size: 1.15rem; line-height: 1.7;">
      My research centers on <strong>analogy and analogical reasoning</strong>. I bridge computational linguistics, graph neural networks, and modern Large Language Models (LLMs) to understand how structural relations can be represented, reasoned over, and generated automatically.
    </p>
  </div>
</div>

<hr class="my-5 border-secondary opacity-25">

<!-- Section 1: Overview -->
<section class="mb-5">
  <h2 class="h3 fw-bold text-dark mb-4">
    <i class="fa-solid fa-compass text-primary me-2"></i>Research Overview
  </h2>

  <p class="text-secondary" style="font-size: 1.05rem; line-height: 1.7;">
    Analogical reasoning—the human capability to recognize relational similarities between distinct domains—is foundational to cognition, abstract thinking, and problem-solving. My research focuses on formalizing these structural processes for machine learning models.
  </p>

  {% stroke_box title="What is an Analogy?" %}
  In computational terms, an <strong>analogy</strong> represents <em>relational similarity across distinct domains</em>. We can formalize domains as directed, multi-relational graphs, where entities form nodes and conceptual relationships represent edges.
  {% endstroke_box %}

  <div class="card my-4 border-0 shadow-sm overflow-hidden">
    <div class="card-body bg-light text-center p-4">
      {% include figure.liquid loading="eager" path="assets/img/logics-03-00012-g001.png" class="img-fluid rounded z-depth-1" style="max-width: 65%;" zoomable=true %}
      <div class="caption text-muted mt-3 small">
        <strong>Figure 1:</strong> Relational structures as colored multigraphs demonstrating the classic structural alignment between the solar system (a) and the hydrogen atom (b). <em>(Figure adapted from Ott et al., 2025)</em>.
      </div>
    </div>
  </div>

  <p class="text-secondary" style="font-size: 1.05rem; line-height: 1.7;">
    My work spans <strong>state-of-the-art relation similarity classification</strong> (outperforming existing benchmarks) and <strong>graph-isomorphism benchmarks</strong> designed to stress-test abstract reasoning in state-of-the-art LLMs.
  </p>
</section>

<hr class="my-5 border-secondary opacity-25">

<!-- Section 2: Core Focus Areas -->
<section class="mb-5">
  <h2 class="h3 fw-bold text-dark mb-4">
    <i class="fa-solid fa-lightbulb text-warning me-2"></i>Core Research Pillars
  </h2>

  <div class="row g-4 my-2">

    <!-- Pillar 1 -->
    <div class="col-12">
      <div class="card h-100 border-0 border-start border-4 border-primary shadow-sm bg-light">
        <div class="card-body p-4">
          <div class="d-flex justify-content-between align-items-center mb-2">
            <h3 class="h5 card-title text-primary fw-bold mb-0">
              <i class="fa-solid fa-diagram-project me-2"></i>1. Machine Learning for Unsupervised Relation Classification
            </h3>
          </div>
          <div class="mb-3">
            <span class="badge bg-primary me-1">Computational Linguistics</span>
            <span class="badge bg-secondary">Graph ML</span>
          </div>
          <p class="card-text text-secondary mb-0">
            Existing benchmarks rely on rigid, pre-defined sets of relation labels. My work focuses on <strong>unsupervised relation learning</strong>, extracting rich relational representations directly from unstructured textual contexts without reliance on human-labeled data.
          </p>
        </div>
      </div>
    </div>

    <!-- Pillar 2 -->
    <div class="col-12">
      <div class="card h-100 border-0 border-start border-4 border-success shadow-sm bg-light">
        <div class="card-body p-4">
          <div class="d-flex justify-content-between align-items-center mb-2">
            <h3 class="h5 card-title text-success fw-bold mb-0">
              <i class="fa-solid fa-graduation-cap me-2"></i>2. Analogy Generation in LLMs for Educational Technology
            </h3>
          </div>
          <div class="mb-3">
            <span class="badge bg-success me-1">RL / Alignment</span>
            <span class="badge bg-secondary">EdTech</span>
          </div>
          <p class="card-text text-secondary mb-3">
            Analogies are critical for making abstract concepts intuitive. I am developing methodologies that combine creative augmentation of word-analogy benchmarks with preference alignment via Reinforcement Learning (e.g., GRPO/DPO) and human evaluation.
          </p>
          <div class="p-3 bg-white rounded border border-success-subtle">
            <small class="text-dark"><i class="fa-solid fa-heart me-1 text-danger"></i> <strong>Applied Impact:</strong> Integrating these models into an AI-powered study platform for students in resource-constrained regions (<a href="https://yar.bamaa.org/en" target="_blank" rel="noopener noreferrer" class="fw-bold">yar.bamaa.org</a>).</small>
          </div>
        </div>
      </div>
    </div>

    <!-- Pillar 3 -->
    <div class="col-12">
      <div class="card h-100 border-0 border-start border-4 border-warning shadow-sm bg-light">
        <div class="card-body p-4">
          <div class="d-flex justify-content-between align-items-center mb-2">
            <h3 class="h5 card-title text-dark fw-bold mb-0">
              <i class="fa-solid fa-robot text-warning me-2"></i>3. Analogies for AI-Driven Scientific Discovery
            </h3>
          </div>
          <div class="mb-3">
            <span class="badge bg-warning text-dark me-1">LLM Agents</span>
            <span class="badge bg-secondary">Knowledge Graphs</span>
          </div>
          <p class="card-text text-secondary mb-0">
            Targeting the emerging field of "AI Scientists", I investigate how LLMs can formulate novel hypotheses via analogy. By translating domain-specific literature into abstract knowledge graphs, LLM agents can perform cross-domain mapping to generate novel research ideas.
          </p>
        </div>
      </div>
    </div>

  </div>
</section>

<hr class="my-5 border-secondary opacity-25">

<!-- Section 3: Cognitive Foundations -->
<section class="mb-5">
  <h2 class="h3 fw-bold text-dark mb-4">
    <i class="fa-solid fa-comments text-info me-2"></i>Cognitive Foundations & Logical Reasoning
  </h2>

  <div class="card border-0 shadow-sm p-4 bg-light">
    <h3 class="h5 fw-bold text-dark"><i class="fa-solid fa-quote-left me-2 text-muted"></i>Analogical Mapping in Communication</h3>
    <p class="text-secondary">
      Analogy is deeply embedded in human dialogue and argumentative discourse. It allows speakers to map structural logic from familiar domains to complex or disputed topics.
    </p>

    <blockquote class="blockquote border-start border-4 border-info ps-3 my-3 bg-white p-3 rounded" style="font-size: 0.95rem;">
      <p class="mb-2 italic">"Please explain to me why Microsoft should be forced to include third-party software in their OS? Every time I buy a six-pack of Coke, should a can of Pepsi be included?"</p>
      <footer class="blockquote-footer mb-0">Analogy in public discourse regarding Microsoft antitrust cases <cite title="Source Title">(Gentner, 2012)</cite></footer>
    </blockquote>

    <hr class="my-4 border-secondary opacity-25">

    <h3 class="h5 fw-bold text-dark"><i class="fa-solid fa-brain me-2 text-muted"></i>Formal Logic & Spatial Contexts</h3>
    <p class="text-secondary mb-0">
      Beyond text generation, formal logic and spatial reasoning are vital for grounded AI systems. In multi-modal environments and spatial navigation tasks (e.g., Kranti et al., 2025), language models must adhere to underlying environmental constraints and logical axioms to reason effectively.
    </p>
  </div>
</section>

<hr class="my-5 border-secondary opacity-25">

<!-- Section 4: Publications -->
<section class="mb-5">
  <h2 class="h3 fw-bold text-dark mb-4">
    <i class="fa-solid fa-book-bookmark text-danger me-2"></i>Selected Publications
  </h2>

  <div class="card border-0 shadow-sm overflow-hidden">
    <div class="list-group list-group-flush">
      
      <!-- Publication 1 -->
      <div class="list-group-item p-4">
        <div class="d-flex w-100 justify-content-between align-items-center flex-wrap gap-2">
          <h5 class="mb-1 text-primary fw-bold">Graph Mapping and LLM Thinking Speed</h5>
          <span class="badge bg-primary rounded-pill px-3 py-2">INLG 2026 (Accepted)</span>
        </div>
        <p class="mb-2 text-muted"><strong>Bahrami, R. A.</strong> and Yahyapour, R.</p>
        <div class="mt-3">
          <a href="https://bahramiramazan.github.io/assets/pdf/Final_INLG_GM.pdf" class="btn btn-sm btn-outline-danger me-2" target="_blank">
            <i class="fa-solid fa-file-pdf me-1"></i> Paper PDF
          </a>
          <a href="https://github.com/bahramiramazan/graphmapping" class="btn btn-sm btn-outline-dark" target="_blank">
            <i class="fa-brands fa-github me-1"></i> Code Repository
          </a>
        </div>
      </div>

      <!-- Publication 2 -->
      <div class="list-group-item p-4">
        <div class="d-flex w-100 justify-content-between align-items-center flex-wrap gap-2">
          <h5 class="mb-1 text-primary fw-bold">Re-Representation in Sentential Relation Extraction with Sequence Routing Algorithm</h5>
          <span class="badge bg-secondary rounded-pill px-3 py-2">ICNLSP 2025</span>
        </div>
        <p class="mb-0 text-muted"><strong>Bahrami, R.</strong> and Yahyapour, R. (pp. 315–327)</p>
      </div>

    </div>
  </div>

  <div class="text-end mt-4">
    <a href="https://github.com/bahramiramazan" class="btn btn-link text-decoration-none fw-bold" target="_blank">
      View complete codebase on GitHub <i class="fa-solid fa-arrow-right ms-1"></i>
    </a>
  </div>
</section>
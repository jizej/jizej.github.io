---
layout: archive
title: "CV"
permalink: /cv/
author_profile: false
---

{% include base_path %}

<p><a class="btn btn--primary" href="{{ base_path }}/files/Jize_Jiang_CV.pdf" target="_blank" rel="noopener"><i class="fas fa-file-pdf" aria-hidden="true"></i> Download CV (PDF)</a></p>

Education
======
* **Ph.D. in Computer Science**, University of Illinois Urbana-Champaign, 2025 – Present
  * Advisor: Prof. ChengXiang Zhai
* **M.S. in Computer Science**, University of Illinois Urbana-Champaign, 2023 – 2025
  * Thesis: *Diagnostic Evaluation of Logical Reasoning in LLMs*
* **B.S. in Mathematics & Computer Science and Statistics**, University of Illinois Urbana-Champaign, 2018 – 2023

Research Interests
======
Evaluation and diagnostics of logical reasoning in LLMs; memory-augmented LLM agents; neural&ndash;symbolic systems for reliable decision making; human-centered tools for understanding and steering AI agents.

Research Experience
======
* **Graduate Research Assistant** &mdash; TIMAN Research Group, UIUC (2022 &ndash; Present)
  * Advisor: Prof. ChengXiang Zhai.
  * **PlugMem (ICML 2026):** Designed a task-agnostic plugin memory module attaching to arbitrary LLM agents, structuring raw interactions into a memory graph of propositional facts and prescriptive skills with intent-aware retrieval. Evaluated unchanged across long-horizon conversational QA, multi-hop knowledge retrieval, and web agent benchmarks, outperforming both task-agnostic and task-specific memory designs while achieving the highest information density. In collaboration with Microsoft Research.
  * **VGI-Bench (EMNLP 2026):** Contributed to a benchmark of 27 tasks and 810 instances probing whether video generation models perform visually grounded reasoning rather than surface-level synthesis; the strongest model reached only 51% accuracy, with analysis showing later denoising steps refine early hypotheses instead of correcting reasoning errors.
  * **VTool-R1 (ICLR 2026):** Co-built the first framework training VLMs to produce multimodal chains of thought&mdash;interleaving text with intermediate visual reasoning steps via Python tool invocations&mdash;using outcome-based RL without process supervision. 10%+ accuracy gains on chart/table QA.
  * **HarnessLens (under review, CHI 2027):** Co-led an interactive visualization system that helps practitioners understand and evaluate agentic AI systems they did not build, surfacing execution traces and harness behavior for inspection.
  * **Cache-of-Thought (EMNLP 2025):** Designed a master-apprentice framework for cost-effective VLM reasoning, with cached QA pairs retrieved via dual-modality dense retrieval. Up to 7.7% performance gain under fixed budget; up to 36.6% apprentice VLM improvement.
  * **UOUO (EMNLP 2024):** Co-designed a benchmark and data curation pipeline for measuring VLM knowledge horizons on uncontextualized uncommon objects, combining background removal, CLIP-based filtering, XGBoost-based selection, MMD hard negatives, and mosaic grounding evaluation.
  * **Aha Moment Revisited:** Systematically evaluated self-verification capabilities of RL-tuned VLMs during inference-time scaling.
  * **M.S. Thesis &mdash; Diagnostic Evaluation of Logical Reasoning in LLMs:** Designed a diagnostic framework using self-generated synthetic ordering tasks with controlled complexity, formulating problems as two-layer representations (abstract logical structures + natural language surface forms) with controlled perturbations to test reasoning invariance. Revealed significant linguistic sensitivity and pronounced answer-type biases in GPT-4.1 and GPT-4o, indicating reliance on heuristic shortcuts over genuine logical deduction. Extended into *Competence-Based Evaluation of Logical Reasoning in Large Language Models* (in submission to ACL Rolling Review).

* **Research Intern** &mdash; Automatic Reasoning Lab, Langboat Inc. (Jan 2022 &ndash; May 2022)
  * Supervised by Dr. Ming Zhou.
  * Surveyed and benchmarked low-resource semantic parsing and automatic reasoning.
  * Built a neural-symbolic reasoning system for AR-LSAT (Analytical Reasoning) integrating explicit logical rules with end-to-end differentiable training; outperformed baselines on ordering subtasks.

* **Research Intern** &mdash; Microsoft Research Asia, System Intelligence Group (Aug 2021 &ndash; Dec 2021)
  * Mentor: Yaming Yang.
  * Researched transferable graph neural networks; developed ego-graph encoding techniques for richer node embeddings and improved cross-domain generalization.
  * Designed and evaluated structural encoding methods capturing local neighborhood topology in heterogeneous graphs.

* **Undergraduate Research Assistant** &mdash; Sanmi Koyejo Lab, UIUC (Jun 2020 &ndash; Aug 2023)
  * Mentor: Brando Miranda.
  * **IsabelleGym:** Training and testing environment for automated theorem-proving agents; translated Isabelle's proof archives into Python-friendly datasets and integrated Isabelle (Scala/ML) into a Python package.
  * **Meta-Learning to Prove via Complexity Minimization:** Meta-learned a position evaluation function (estimating remaining proof steps) as a loss to improve tactic prediction and produce shorter proofs.
  * **Ultimate-pycoq:** ML interface for the Coq theorem prover; first archive in the Coq community of proofs with proof steps and states.

* **Undergraduate Research Assistant** &mdash; Illinois Risk Lab, UIUC (Mar 2021 &ndash; Dec 2022)
  * Supervisor: Dr. Zhiyu Frank Quan.
  * Cleaned and preprocessed 500K business and insurance records with high dimensionality and mixed types.
  * Built end-to-end keyword extraction and text classification models for risk analysis, replacing the original rule-based pipeline.
  * Developed a question-answering system for risk-related queries over text and numerical sources.

Skills
======
* **Programming Languages:** Python, C++, Java, JavaScript, R, SAS, Prolog, OCaml.
* **LLM/VLM Training & Tuning:** Fine-tuning, RL fine-tuning, post-training, inference-time scaling, dataset design/curation, evaluation of LLMs, VLMs, VLAs, and agentic systems.
* **Software Development & Research Engineering:** Python package development, research infrastructure, large-scale preprocessing, retrieval/memory systems, tool-use pipelines, reproducible code release; Coq/Isabelle theorem-prover integration and proof-state processing.
* **Data & Statistical Analysis:** Statistical, temporal, and geospatial analysis; exploratory analysis; data cleaning; modeling workflows in Python, R, SAS.
* **General:** UX/UI design, visual design, video production/editing, technical presentation, visual storytelling, research communication.

Publications
======
\* indicates equal contribution.

**Conference Papers**
  <ul>{% for post in site.publications reversed %}{% if post.category == 'conferences' %}
    {% include archive-single-cv.html %}
  {% endif %}{% endfor %}</ul>

**Preprints & Under Review**
  <ul>{% for post in site.publications reversed %}{% if post.category == 'manuscripts' %}
    {% include archive-single-cv.html %}
  {% endif %}{% endfor %}</ul>

**Work in Progress**
* *PlugMem Studio: An Interactive Memory Inspection Interface for Agentic Systems.* In preparation.
* *Language-Conditioned Affordances for Grasping in a Cluttered Environment.* In preparation.

Professional Service
======
* **Reviewer:** ICML 2026

Teaching Experience
======
* **Teaching Assistant:** CS 357 Numerical Methods I, CS 450 Numerical Analysis, CS 447 Natural Language Processing
* **Course Assistant:** CS 222 Software Design Lab, CS 173 Discrete Structures, CS 125 Introduction to Computer Science

<h1 align="center">Sapram Khajesh Narayana</h1>

<p align="center">
  <b>Computer Science & AI · Machine Learning Research · Information Retrieval</b>
</p>

<p align="center">
  I build systems that learn better representations, retrieve the right information, and help us understand how intelligent models make decisions.
</p>

<p align="center">
  <a href="https://arxiv.org/abs/2608.16161">Research</a> •
  <a href="https://github.com/khajeshnarayana/Domain-Specific-Text-Embedding-Models-for-Information-Retrieval">Projects</a> •
  <a href="mailto:khajeshn@gmail.com">Contact</a>
</p>

---

## About Me

I am a Computer Science and Engineering undergraduate specializing in Artificial Intelligence at Manipal Institute of Technology Bengaluru.

My work sits primarily at the intersection of:

* Machine Learning
* Natural Language Processing
* Representation Learning
* Information Retrieval
* Entity Resolution
* LLM Reasoning & Faithfulness
* AI-driven decision systems

I am particularly interested in problems where simply making a model larger is not enough — problems that require better representations, stronger evaluation, careful experimentation, and systems that remain reliable under uncertainty.

---

## Research

### Domain-Specific Text Embedding Models for Entity Resolution

<a href="https://arxiv.org/abs/2608.16161">
  <img src="https://img.shields.io/badge/arXiv-2608.16161-b31b1b?style=flat-square&logo=arxiv" />
</a>

**Khajesh Sapram, Srivardhani Raju, Kishore Konda — 2026**

Research into adapting general-purpose sentence embedding models for identity-sensitive entity retrieval.

The work explores whether triplet-based domain adaptation can reshape embedding spaces so that models distinguish genuine entity matches from highly similar non-matching records.

Key work included:

* Fine-tuning `all-MiniLM-L6-v2` and `BAAI/bge-base-en-v1.5`
* Building a synthetic corpus of **8,130 anchor-positive-negative triplets**
* Constructing identity-preserving variations and challenging hard negatives
* Designing entity-level train/validation isolation to prevent leakage
* Developing cosine-similarity and margin-based evaluation frameworks
* Building reproducible preprocessing, training, validation, and benchmarking pipelines

At a strict **0.30 similarity margin**, domain adaptation improved BGE Base EN v1.5 performance from **15.25% to 92.70%**.

**Paper:** [Domain-Specific Text Embedding Models for Entity Resolution](https://arxiv.org/abs/2608.16161)

**Code:** [Domain-Specific Text Embedding Models for Information Retrieval](https://github.com/khajeshnarayana/Domain-Specific-Text-Embedding-Models-for-Information-Retrieval)

---

## What I'm Working On

### Chain-of-Thought Faithfulness

Exploring whether the reasoning explanations produced by large language models actually reflect the process responsible for their answers.

Current direction:

> **Evaluating Chain-of-Thought Faithfulness Through Black-Box Behavioral Interventions**

The broader question is simple:

**When a model explains its reasoning, how much should we trust that explanation?**

Areas of interest include behavioral interventions, counterfactual testing, reasoning-model evaluation, post-hoc rationalization, and the reliability of visible reasoning traces.

---

### DeltaVision

**AI-Driven Formula One Race Strategy Optimization Under Uncertainty**

A decision-support system for evaluating Formula One race strategy from evolving race state.

The system models information such as:

* Tyre compound and tyre age
* Driver position
* Gaps to surrounding cars
* Recent race pace
* Pit-loss estimates
* Safety Car / VSC state
* Weather and track conditions

The central problem:

> Given the information available at time \(t\), what was the strongest strategic decision available?

The project combines race-state reconstruction, data engineering, uncertainty-aware reasoning, and strategy optimization.

---

## Technical Stack

### Languages & Tools

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
</p>

### Machine Learning

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/Sentence%20Transformers-000000?style=flat-square" />
</p>

```text
Deep Learning
Transformer Fine-Tuning
Text & Sentence Embeddings
Representation Learning
Metric Learning
Triplet Learning
Synthetic Data Generation
```

### Information Retrieval

```text
Dense Retrieval
Semantic Search
Entity Resolution
Record Linkage
Duplicate Detection
Hard-Negative Construction
```

### Research & Evaluation

```text
Experimental Design
Model Benchmarking
Cosine-Similarity Evaluation
Entity-Level Validation
Data Preprocessing
Reproducible Research
```

---

## How I Approach Problems

I am interested in building systems from first principles rather than treating models as black-box components.

My usual workflow is:

```text
Understand the system
        ↓
Define the state and constraints
        ↓
Construct the data
        ↓
Build the smallest working pipeline
        ↓
Measure failure
        ↓
Fix the representation / architecture / evaluation
        ↓
Repeat
```

The objective is not merely to make a model produce an answer.

It is to understand **why the system succeeds, where it fails, and how to make that behavior measurable and reproducible.**

---

## Current Research Interests

```text
Representation Learning     ███████████████████
Information Retrieval       ███████████████████
LLM Reasoning               ██████████████████
AI Evaluation               █████████████████
Decision Systems            ████████████████
Machine Learning Systems    ████████████████
```

I am especially interested in:

* Domain adaptation of embedding models
* Retrieval and ranking systems
* Hard-negative learning
* Evaluation of reasoning models
* Chain-of-Thought faithfulness
* AI systems operating under uncertainty
* Reproducible machine learning research

---

## GitHub

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=khajeshnarayana&show_icons=true&hide_border=true&rank_icon=github" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=khajeshnarayana&layout=compact&hide_border=true" />
</p>

---

## Beyond the Code

I am interested in more than isolated models or benchmarks.

I like understanding **systems** — how individual components interact, where assumptions break, how decisions propagate, and how complex behavior emerges from relatively simple mechanisms.

That curiosity extends across artificial intelligence, research, engineering, strategy, and optimization.

---

<p align="center">
  <b>Build. Measure. Understand. Improve.</b>
</p>

<p align="center">
  <a href="mailto:khajeshn@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/khajeshnarayana">
    <img src="https://img.shields.io/badge/GitHub-khajeshnarayana-181717?style=flat-square&logo=github&logoColor=white" />
  </a>
  <a href="https://arxiv.org/abs/2608.16161">
    <img src="https://img.shields.io/badge/arXiv-Research-b31b1b?style=flat-square&logo=arxiv" />
  </a>
</p>

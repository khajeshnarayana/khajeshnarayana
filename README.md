<h1 align="center">Sapram Khajesh Narayana</h1>

<p align="center">
  <b>Artificial Intelligence · Machine Learning Research · Information Retrieval</b>
</p>

<p align="center">
  Building intelligent systems. Testing what they claim. Measuring what actually works.
</p>

<p align="center">
  <a href="https://github.com/khajeshnarayana">GitHub</a> •
  <a href="https://arxiv.org/abs/2608.16161">Research</a> •
  <a href="mailto:khajeshn@gmail.com">Contact</a>
</p>

---

## About

Computer Science and Engineering undergraduate specializing in **Artificial Intelligence** at Manipal Institute of Technology Bengaluru.

My work is concentrated around machine learning systems where the difficult part is not simply training a model.

It is proving that the model deserves to work.

I work across:

* Machine Learning
* Natural Language Processing
* Representation Learning
* Information Retrieval
* Entity Resolution
* LLM Reasoning
* AI Evaluation
* Decision Systems

I am interested in systems that have to perform when the data is imperfect, the distinctions are subtle, and the answer cannot be taken on faith.

---

## Research

### Domain-Specific Text Embedding Models for Entity Resolution

**Khajesh Sapram, Srivardhani Raju, Kishore Konda — 2026**

[Read the paper on arXiv](https://arxiv.org/abs/2608.16161)

[View the implementation](https://github.com/khajeshnarayana/Domain-Specific-Text-Embedding-Models-for-Information-Retrieval)

General-purpose embedding models are good at semantic similarity.

Entity resolution demands something stricter.

Two records can look nearly identical and still represent different entities. Two records can look substantially different and still refer to the same one.

That distinction was the problem.

The work involved:

* Fine-tuning `all-MiniLM-L6-v2`
* Fine-tuning `BAAI/bge-base-en-v1.5`
* Building **8,130 anchor-positive-negative triplets**
* Designing identity-preserving positive variations
* Constructing difficult hard negatives
* Enforcing entity-level train-validation isolation
* Building preprocessing, training and evaluation pipelines
* Benchmarking pretrained and domain-adapted representations
* Measuring embedding separation through cosine-similarity margins

At a strict **0.30 margin**, domain adaptation increased BGE Base EN v1.5 performance from **15.25% to 92.70%**.

The objective was not to produce embeddings that merely looked good.

It was to build an embedding space that made the right distinctions.

---

## Current Work

### Chain-of-Thought Faithfulness

Large language models can explain their reasoning.

That does not automatically mean the explanation caused the answer.

I am currently investigating the faithfulness of visible reasoning traces through **black-box behavioral interventions**.

The central question:

> **When a model tells us why it reached an answer, how much of that explanation should we believe?**

Current areas of investigation include:

* Chain-of-Thought faithfulness
* Behavioral interventions
* Counterfactual evaluation
* Post-hoc rationalization
* Reasoning-model evaluation
* Prompt-induced behavioral changes
* Reliability of visible reasoning traces

The distinction matters.

A persuasive explanation is not necessarily a faithful one.

---

### DeltaVision

**AI-Driven Formula One Race Strategy Optimization Under Uncertainty**

Race strategy is not an optimization problem with perfect information.

It is a decision problem under pressure, incomplete information and changing state.

DeltaVision reconstructs Formula One race conditions and evaluates the strongest strategic action available from the information that existed at that moment.

The system considers:

* Driver position
* Tyre compound
* Tyre age
* Recent pace
* Gaps ahead and behind
* Pit-loss estimates
* Safety Car and VSC periods
* Weather
* Track conditions
* Race-state transitions

The question behind the system:

> **Given everything known at time \(t\), what was the strongest decision available?**

Not what became obvious afterwards.

What was defensible then.

---

## Selected Work

### Domain-Specific Text Embedding Models for Information Retrieval

**Python · PyTorch · Hugging Face · Sentence Transformers**

A reproducible research pipeline covering:

`Data Generation → Model Training → Validation → Retrieval Evaluation → Benchmarking`

[View Repository](https://github.com/khajeshnarayana/Domain-Specific-Text-Embedding-Models-for-Information-Retrieval)

Key areas:

* Sentence-embedding fine-tuning
* Metric learning
* Triplet learning
* Entity resolution
* Dense retrieval
* Hard-negative construction
* Semantic similarity
* Model benchmarking
* Data-leakage prevention

---

## Technical Stack

### Core

`Python` · `Git` · `GitHub`

### Machine Learning

`PyTorch` · `Hugging Face Transformers` · `Sentence Transformers`

### ML & NLP

`Deep Learning`
`Transformer Fine-Tuning`
`Text Embeddings`
`Sentence Embeddings`
`Representation Learning`
`Metric Learning`
`Triplet Learning`
`Synthetic Data Generation`

### Information Retrieval

`Dense Retrieval`
`Semantic Search`
`Entity Resolution`
`Record Linkage`
`Duplicate Detection`
`Hard-Negative Construction`

### Research & Evaluation

`Experimental Design`
`Model Benchmarking`
`Cosine-Similarity Evaluation`
`Entity-Level Validation`
`Data Preprocessing`
`Reproducible Research`

---

## Research Interests

**Representation Learning**
Building embedding spaces where meaningful distinctions survive similarity.

**Information Retrieval**
Finding the right result, not merely a plausible one.

**Reasoning Models**
Understanding the difference between an answer and the reasoning presented for it.

**AI Evaluation**
Designing experiments capable of exposing model failure rather than concealing it behind aggregate performance.

**Decision Systems**
Making the strongest decision possible from the state of the world that actually exists.

**Machine Learning Systems**
Turning experiments into pipelines that can be tested, reproduced and challenged.

---

## Publication

### Domain-Specific Text Embedding Models for Entity Resolution

Khajesh Sapram, Srivardhani Raju, Kishore Konda
**arXiv, August 2026**

[Paper](https://arxiv.org/abs/2608.16161) · [Source Code](https://github.com/khajeshnarayana/Domain-Specific-Text-Embedding-Models-for-Information-Retrieval)

---

## Find Me

[GitHub](https://github.com/khajeshnarayana)
[arXiv](https://arxiv.org/abs/2608.16161)
[Email](mailto:khajeshn@gmail.com)

---

<p align="center">
  <b>Build what works. Measure what matters.</b>
</p>

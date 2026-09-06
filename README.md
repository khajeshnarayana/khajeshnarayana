<h1 align="center">Sapram Khajesh Narayana</h1>

<p align="center">
  <b>AI / ML Research · Information Retrieval</b>
</p>

<p align="center">
  <a href="https://github.com/khajeshnarayana">GitHub</a> •
  <a href="https://arxiv.org/abs/2608.16161">Research</a> •
  <a href="mailto:khajeshn@gmail.com">Contact</a>
</p>

---

## About

CS undergrad specializing in AI at Manipal. Training a model is table stakes. My work is in the part everyone skips — building the evidence that the model earns its claims.

I operate across representation learning, information retrieval, entity resolution, and LLM reasoning. Every one of these fields has the same failure mode: results that look strong until someone asks the right question. I ask the right question first.

---

## Research

### Domain-Specific Text Embedding Models for Entity Resolution
**Khajesh Sapram, Srivardhani Raju, Kishore Konda — arXiv, 2026**

[Paper](https://arxiv.org/abs/2608.16161) · [Code](https://github.com/khajeshnarayana/Domain-Specific-Text-Embedding-Models-for-Information-Retrieval)

General-purpose embeddings are optimized for "similar." Entity resolution has no use for "similar" — it needs "correct." Two records can be near-identical and belong to different people. Two records can look nothing alike and belong to the same one. Getting that distinction wrong isn't a rounding error, it's the whole problem.

- Fine-tuned `all-MiniLM-L6-v2` and `BAAI/bge-base-en-v1.5`
- Constructed 8,130 anchor-positive-negative triplets with strict entity-level train/validation isolation
- Engineered hard negatives built specifically to defeat shortcut learning

**Result:** at a strict 0.30 cosine-similarity margin, BGE Base EN v1.5 moved from 15.25% to 92.70%. Domain adaptation didn't nudge the model. It rebuilt it.

---

## In Progress

**Chain-of-Thought Faithfulness** — A model explaining its reasoning and a model's reasoning actually driving its answer are two different claims, frequently mistaken for one. I'm running black-box behavioral interventions and counterfactual evaluation to separate the two. Early-stage; repository will go public once there's something worth reviewing.

**DeltaVision** — Formula One race strategy under uncertainty. The standard is not the decision that looks right in hindsight — it's the strongest decision available from the information that actually existed at that moment: tyre state, gap dynamics, Safety Car probability, weather, pit-loss cost. Currently in design.

---

## Stack

`Python` · `PyTorch` · `Hugging Face Transformers` · `Sentence Transformers` · `Git`

Metric learning, triplet learning, dense retrieval, hard-negative mining, reproducible ML pipelines built to survive scrutiny, not just demos.

---

[GitHub](https://github.com/khajeshnarayana) · [arXiv](https://arxiv.org/abs/2608.16161) · [Email](mailto:khajeshn@gmail.com)

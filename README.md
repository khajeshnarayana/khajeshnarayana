<div align="center">

# SAPRAM KHAJESH NARAYANA

### AI / ML Research · Information Retrieval · Intelligent Systems

*Build the evidence. Then make the claim.*

<br>

[![GitHub](https://img.shields.io/badge/GITHUB-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/khajeshnarayana)
[![arXiv](https://img.shields.io/badge/arXiv-B31B1B?style=for-the-badge\&logo=arxiv\&logoColor=white)](https://arxiv.org/abs/2608.16161)
[![Email](https://img.shields.io/badge/CONTACT-111111?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:khajeshn@gmail.com)

</div>

<br>

---

## Profile

CS undergraduate specializing in **Artificial Intelligence** at Manipal.

Training a model is table stakes.

My work starts where the benchmark ends — determining whether the model actually deserves the conclusion being drawn from it.

I work across **representation learning, information retrieval, entity resolution, LLM reasoning, and decision systems**.

Results are easy to present.

I am more interested in whether they survive scrutiny.

<br>

---

<div align="center">

### SELECTED RESEARCH

|     **8,130**     | **15.25% → 92.70%** | **2 Models** |
| :---------------: | :-----------------: | :----------: |
| Training Triplets |  BGE @ 0.30 Margin  | MiniLM + BGE |

</div>

### Domain-Specific Text Embedding Models for Entity Resolution

**Khajesh Sapram · Srivardhani Raju · Kishore Konda**
`arXiv · 2026`

[**READ PAPER →**](https://arxiv.org/abs/2608.16161)    [**VIEW CODE →**](https://github.com/khajeshnarayana/Domain-Specific-Text-Embedding-Models-for-Information-Retrieval)

<br>

General-purpose embedding models are built to understand **similarity**.

Entity resolution demands something less forgiving:

**identity.**

Two records can look almost identical and belong to different people.

Two records can look completely different and belong to the same person.

Getting that distinction wrong is not a minor error.

**It is the problem.**

#### What I built

* Fine-tuned `all-MiniLM-L6-v2`
* Fine-tuned `BAAI/bge-base-en-v1.5`
* Constructed **8,130 anchor-positive-negative triplets**
* Designed identity-preserving positive variations
* Engineered hard negatives specifically against shortcut learning
* Enforced entity-level train / validation isolation
* Built preprocessing, training, validation and evaluation pipelines
* Benchmarked pretrained against domain-adapted representations

> **Result**
>
> At a strict `0.30` cosine-similarity margin, BGE Base EN v1.5 moved from **15.25% to 92.70%**.
>
> Not a cosmetic improvement. A materially different embedding space.

<br>

---

## Currently Building

<table>
<tr>
<td width="50%" valign="top">

### 01 — Chain-of-Thought Faithfulness

**LLM Reasoning · Evaluation · Research**

A model explaining its reasoning and that reasoning actually causing its answer are two separate claims.

They are frequently treated as one.

I am investigating the gap through:

* Black-box behavioral interventions
* Counterfactual evaluation
* Prompt perturbation
* Faithfulness measurement
* Post-hoc reasoning analysis

**The question**

> When a model tells us why it reached an answer, how much of that explanation should we believe?

`RESEARCH IN PROGRESS`

</td>

<td width="50%" valign="top">

### 02 — DeltaVision

**Formula One · Decision Systems · Optimization**

Race strategy is not about finding the decision that looks correct after the race.

It is about finding the strongest decision justified by the information available **at that moment**.

The system models:

* Tyre state
* Gap dynamics
* Recent pace
* Pit-loss cost
* Weather
* SC / VSC state
* Race-state transitions

**The question**

> Given everything known at time *t*, what was the strongest decision available?

`UNDER DEVELOPMENT`

</td>
</tr>
</table>

<br>

---

## Technical Arsenal

<div align="center">

### Core

![Python](https://img.shields.io/badge/Python-111111?style=for-the-badge\&logo=python\&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-111111?style=for-the-badge\&logo=pytorch\&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-111111?style=for-the-badge\&logo=huggingface\&logoColor=white)
![Git](https://img.shields.io/badge/Git-111111?style=for-the-badge\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-111111?style=for-the-badge\&logo=github\&logoColor=white)

</div>

<br>

<table>
<tr>
<td width="33%" valign="top">

### Machine Learning

`Deep Learning`

`Transformer Fine-Tuning`

`Representation Learning`

`Metric Learning`

`Triplet Learning`

`Sentence Embeddings`

</td>

<td width="33%" valign="top">

### Retrieval

`Dense Retrieval`

`Semantic Search`

`Entity Resolution`

`Record Linkage`

`Hard Negatives`

`Duplicate Detection`

</td>

<td width="33%" valign="top">

### Research

`Experimental Design`

`Model Evaluation`

`Benchmarking`

`Entity-Level Validation`

`Synthetic Data`

`Reproducible ML`

</td>
</tr>
</table>

<br>

---

## Areas of Interest

<table>
<tr>
<td><b>Representation Learning</b></td>
<td>Building embedding spaces where the distinction that matters survives similarity.</td>
</tr>

<tr>
<td><b>Information Retrieval</b></td>
<td>Finding the correct result rather than the merely plausible one.</td>
</tr>

<tr>
<td><b>Reasoning Models</b></td>
<td>Separating explanations models produce from mechanisms that actually influence their answers.</td>
</tr>

<tr>
<td><b>AI Evaluation</b></td>
<td>Designing experiments capable of exposing failure instead of averaging it away.</td>
</tr>

<tr>
<td><b>Decision Systems</b></td>
<td>Making defensible decisions from incomplete information under changing conditions.</td>
</tr>
</table>

<br>

---

## Publication

> ### Domain-Specific Text Embedding Models for Entity Resolution
>
> **Khajesh Sapram, Srivardhani Raju, Kishore Konda**
>
> arXiv · August 2026
>
> [**Paper →**](https://arxiv.org/abs/2608.16161)    [**Implementation →**](https://github.com/khajeshnarayana/Domain-Specific-Text-Embedding-Models-for-Information-Retrieval)

<br>

---

<div align="center">

### Sapram Khajesh Narayana

**Artificial Intelligence · Research · Systems**

[GitHub](https://github.com/khajeshnarayana)  · 
[arXiv](https://arxiv.org/abs/2608.16161)  · 
[Email](mailto:khajeshn@gmail.com)

<br>

**Build what works. Prove that it works.**

</div>

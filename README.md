<h1 align="center">Sapram Khajesh Narayana</h1>

<p align="center">
  <b>I don't chase hype. I chase what survives evaluation.</b>
</p>

<p align="center">
  <a href="https://github.com/khajeshnarayana">GitHub</a> •
  <a href="https://arxiv.org/abs/2608.16161">Research</a> •
  <a href="mailto:khajeshn@gmail.com">Contact</a>
</p>

---

## About

I'm a CS undergrad specializing in AI at Manipal. But titles don't win arguments — results do.

Anyone can train a model. That's the easy part. The hard part is standing in front of someone who doesn't believe you and proving the model deserves to work. That's the part I actually care about.

I work in machine learning, representation learning, information retrieval, entity resolution, and LLM reasoning — wherever the data is messy, the distinctions are subtle, and "trust me" isn't an acceptable answer.

---

## The Win

### Domain-Specific Text Embedding Models for Entity Resolution
**Khajesh Sapram, Srivardhani Raju, Kishore Konda — arXiv, 2026**

[Paper](https://arxiv.org/abs/2608.16161) · [Code](https://github.com/khajeshnarayana/Domain-Specific-Text-Embedding-Models-for-Information-Retrieval)

Here's the problem with general-purpose embeddings: they're good at "similar." Entity resolution doesn't care about similar. Two records can look almost identical and be two different people. Two records can look nothing alike and be the same one. Similar loses. Correct wins.

So I fixed it.

- Fine-tuned `all-MiniLM-L6-v2` and `BAAI/bge-base-en-v1.5`
- Built 8,130 anchor-positive-negative triplets by hand, with entity-level train/validation isolation — no leakage, no shortcuts, no excuses
- Constructed hard negatives that actually earn the name

**Result:** at a strict 0.30 cosine-similarity margin, BGE Base EN v1.5 went from 15.25% to 92.70%.

That's not an improvement. That's a different model.

---

## In Progress

I don't announce what I haven't built yet. These two are open — status noted, no theater.

**Chain-of-Thought Faithfulness** — A model can tell you why it got an answer. That doesn't mean the explanation is the reason. I'm running black-box behavioral interventions to find out how much of a model's stated reasoning is real and how much is a good story. *Early-stage. No public repo yet.*

**DeltaVision** — F1 race strategy under uncertainty. Not "what would've worked" with hindsight — what was the correct call with only the information available at that moment. Tyres, gaps, Safety Car windows, weather, pit-loss math. *Design phase. Nothing shipped yet — I'll link it when there's something worth linking.*

---

## Stack

`Python` · `PyTorch` · `Hugging Face Transformers` · `Sentence Transformers` · `Git`

Metric learning, triplet learning, dense retrieval, hard-negative mining, reproducible pipelines. I don't collect tools. I use the ones that get the job done.

---

<p align="center">
  <b>I don't have hobbies. I have a track record.</b>
</p>

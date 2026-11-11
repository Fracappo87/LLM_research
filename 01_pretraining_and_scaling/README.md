# 01 — Pre-training and scaling

> How LLMs are pre-trained, and how performance scales with parameters, data, and compute.

## Intent

Understand pre-training objectives and data pipelines, and the empirical scaling laws that guide how compute is split between model size and training tokens.

## Research questions

- How does loss scale with model size, dataset size, and compute?
- What is the compute-optimal ratio of parameters to tokens?
- How much do data quality and deduplication matter?

## Contents

| Path | Description |
| --- | --- |
| `notes/` | Reading notes and paper summaries |
| `notebooks/` | Exploratory notebooks |
| `experiments/` | Reproducible experiments |

## Papers

| Paper | Year | Why it matters |
| --- | --- | --- |
| [Scaling Laws for Neural Language Models](https://arxiv.org/abs/2001.08361) | 2020 | First systematic scaling laws (Kaplan et al.) |
| [Training Compute-Optimal Large Language Models](https://arxiv.org/abs/2203.15556) | 2022 | Chinchilla: revises the parameters-to-tokens trade-off |

## Other resources

- _To be added_

## Status

- [ ] Reading list collected
- [ ] Notes written
- [ ] First experiment

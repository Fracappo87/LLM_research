# 02 — Fine-tuning and alignment

> Adapting a pre-trained model to tasks and preferences: full fine-tuning, parameter-efficient methods, and preference optimisation.

## Intent

Compare fine-tuning approaches in practice, from supervised fine-tuning (SFT) to parameter-efficient methods and alignment with human preferences.

## Research questions

- When is parameter-efficient fine-tuning (LoRA, QLoRA) enough compared with full fine-tuning?
- How do RLHF and DPO differ in setup, cost, and results?
- How much data does a useful fine-tune need?

## Contents

| Path | Description |
| --- | --- |
| `notes/` | Reading notes and paper summaries |
| `notebooks/` | Exploratory notebooks |
| `experiments/` | Reproducible experiments |

## Papers

| Paper | Year | Why it matters |
| --- | --- | --- |
| [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685) | 2021 | Low-rank adapters for cheap fine-tuning |
| [QLoRA: Efficient Finetuning of Quantized LLMs](https://arxiv.org/abs/2305.14314) | 2023 | LoRA on top of a 4-bit quantized base model |
| [Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155) | 2022 | InstructGPT: the RLHF recipe |
| [Direct Preference Optimization](https://arxiv.org/abs/2305.18290) | 2023 | Preference tuning without a reward model or RL |

## Other resources

- _To be added_

## Status

- [ ] Reading list collected
- [ ] Notes written
- [ ] First experiment

# 04 — Inference and efficiency

> Running LLMs fast and cheaply: decoding strategies, quantization, attention kernels, and serving.

## Intent

Understand the main techniques that reduce latency, memory, and cost at inference time, and measure their trade-offs on our own hardware.

## Research questions

- How do decoding strategies (greedy, beam, top-k, top-p) affect output quality?
- What accuracy is lost by quantizing weights to 8 or 4 bits?
- How do KV-cache management and speculative decoding speed up generation?

## Contents

| Path | Description |
| --- | --- |
| `notes/` | Reading notes and paper summaries |
| `notebooks/` | Exploratory notebooks |
| `experiments/` | Reproducible experiments |

## Papers

| Paper | Year | Why it matters |
| --- | --- | --- |
| [FlashAttention](https://arxiv.org/abs/2205.14135) | 2022 | IO-aware exact attention |
| [Efficient Memory Management for LLM Serving with PagedAttention](https://arxiv.org/abs/2309.06180) | 2023 | vLLM: paged KV cache for high-throughput serving |
| [Fast Inference from Transformers via Speculative Decoding](https://arxiv.org/abs/2211.17192) | 2022 | Draft-and-verify decoding |

## Other resources

- _To be added_

## Status

- [ ] Reading list collected
- [ ] Notes written
- [ ] First experiment

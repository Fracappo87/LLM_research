# LLM_research

Personal research repository for studying and experimenting with large language models (LLMs): reading notes, notebooks, and reproducible experiments.

The repository is organised by **topic**. Each topic lives in its own folder, and each folder has a `README.md` that states what the folder is for, the questions it tries to answer, and the papers it builds on.

## Repository structure

| Folder | Focus |
| --- | --- |
| [`00_foundations/`](00_foundations/) | Transformer architecture, attention, tokenization, embeddings |
| [`01_pretraining_and_scaling/`](01_pretraining_and_scaling/) | Pre-training objectives, data, scaling laws |
| [`02_fine_tuning_and_alignment/`](02_fine_tuning_and_alignment/) | Supervised fine-tuning, parameter-efficient methods (LoRA, QLoRA), RLHF, DPO |
| [`03_evaluation/`](03_evaluation/) | Benchmarks, metrics, LLM-as-a-judge, evaluation pitfalls |
| [`04_inference_and_efficiency/`](04_inference_and_efficiency/) | Decoding strategies, quantization, KV cache, serving |
| [`_template/`](_template/) | Template to copy when starting a new topic folder |

Numbering keeps folders in a sensible reading order; it is not a strict dependency chain.

## Layout of a topic folder

Each topic folder follows the same layout. Subfolders are created only when they have content.

```
NN_topic_name/
├── README.md       # intent, research questions, papers, status
├── notes/          # reading notes and paper summaries (Markdown)
├── notebooks/      # exploratory Jupyter notebooks
└── experiments/    # reproducible scripts, configs, and results
```

## Adding a new topic

1. Copy [`_template/`](_template/) to a new folder named `NN_topic_name` (next free number, `snake_case`).
2. Fill in the sections of its `README.md`.
3. Add a row for it to the table above.

## Conventions

- **Papers**: link to the arXiv abstract page (`https://arxiv.org/abs/XXXX.XXXXX`) where one exists, and list them in the topic's `README.md`.
- **Notes**: one Markdown file per paper or concept in `notes/`, named after it (e.g. `notes/lora.md`).
- **Experiments**: each experiment should be runnable from its own folder and state how to reproduce it (command, config, seed) in a short `README.md`.
- **Data and model weights** are not committed; document where to get them instead.

## License

See [LICENSE](LICENSE).

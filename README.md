## MemeCULT-1K: Benchmarking South Asian Cultural Context and Humor Understanding of Multimodal Models

Accepted at **EMNLP 2026 Main Conference** | [Paper](https://arxiv.org/abs/2609.01772)


> **Code and datasets are coming soon.** This repository is being prepared for public release. Star/watch the repo to be notified when the data and evaluation code become available.

---

## Overview

Meme understanding goes beyond recognizing visual content or literal text; it requires implicit cultural knowledge and pragmatic inference that most vision-language models still lack. A model may correctly parse both a caption and the visual content, yet still fail to understand the humor when the underlying cultural reference — a person, event, idiom, or social situation — is not recognized.

**MemeCULT-1K** is a multilingual benchmark of **1,000 South Asian memes** in **Bengali, English, and Hindi**, where each meme is paired with a short **cultural context note** and **three independent human-written English explanations**. It also includes a supplementary set of **54 Bengali regional dialect memes** to probe robustness to non-standard spellings, dialectal vocabulary, and localized humor.

We evaluate **thirteen popular Vision-Language Models (VLMs)** under two settings:

- **Meme-only** — the model sees only the meme image.
- **Context-aware** — the model additionally receives the cultural context note.

Providing minimal cultural context yields consistent gains across all models and languages, motivating future work on explicit cultural knowledge integration.

---

## Dataset

| Property | Value |
| --- | --- |
| Total memes | 1,000 |
| Languages | Bengali (335), English (331), Hindi (334) |
| Per meme | 3 human-written English explanations + 1 cultural context note |
| Total text entries | 4,000 |
| Supplementary set | 54 Bengali regional dialect memes |
| Sources | Reddit, Facebook, regional meme pages (publicly available) |


---

## Evaluated Models

**Closed-source:** GPT-5 Nano, GPT-5 Mini, Gemini 2.5 Flash Lite, Gemini 2.5 Flash, Gemini 2.5 Pro

**Open-source:** Gemma-3-4B, Gemma-3-12B, InternVL3.5-2B/4B/8B, Qwen3VL-2B/4B/8B

---

## Citation

If you use MemeCULT-1K in your work, please cite:

```bibtex
@misc{dipto2026memecult1kbenchmarkingsouthasian,
      title={MemeCULT-1K: Benchmarking South Asian Cultural Context and Humor Understanding of Multimodal Models}, 
      author={Tawsif Tashwar Dipto and Mehedi Ahamed and Radib Bin Kabir and Mueeze Al Mushabbir and Mohammed Saidul Islam and Mir Rayat Imtiaz Hossain and Md Tahmid Rahman Laskar and Sabbir Ahmed},
      year={2026},
      eprint={2609.01772},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2609.01772}, 
}
```

## Authors

Tawsif Tashwar Dipto, Mehedi Ahamed, Radib Bin Kabir, Mueeze Al Mushabbir, Mohammed Saidul Islam, Mir Rayat Imtiaz Hossain, Md Tahmid Rahman Laskar, Sabbir Ahmed.

Affiliations: Islamic University of Technology; South East University; Vector Institute; University of British Columbia; York University; Queen's University.

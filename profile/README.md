<div align="center">

<br>

<img src="https://img.shields.io/badge/%E2%9C%A6-OPCEANAI-0D1117?style=for-the-badge&labelColor=0D1117" alt="OpceanAI" height="60">

<br><br>

# Independent AI Research. Zero Budget. Measurable Results.

**Open-source language models, theoretical AI frameworks, and research tooling.**<br>
**Built by a single researcher. No cloud infrastructure. No institutional funding. $0.00.**

<br>

[![HuggingFace](https://img.shields.io/badge/Models-Hugging_Face-ffd21e?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/OpceanAI)
&nbsp;
[![Zenodo](https://img.shields.io/badge/Research-Zenodo-024d8f?style=for-the-badge&logo=zenodo&logoColor=white)](https://zenodo.org)
&nbsp;
[![Sponsor](https://img.shields.io/badge/Sponsor-GitHub_Sponsors-ea4aaa?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/aguitauwu)

<br>

---

<br>

</div>

## About OpceanAI

**OpceanAI** is an independent AI research organization founded in 2026 by **awa_omg**, researcher based in Mexico. The organization operates with no institutional funding, no cloud compute budget, and no team — producing peer-reviewed research, competitive language models, and open-source tooling from consumer hardware.

OpceanAI's work spans three domains: small language model development under extreme hardware constraints, a theoretical framework connecting information theory to fundamental physics (the Imprint Theory), and open-source infrastructure for local AI deployment.

The organization's central thesis — that training data quality systematically outperforms training data quantity — has been validated empirically across the entire NxG model family.

<br>

---

<br>

<div align="center">

## Research Focus

</div>

<br>

<table>
<tr>
<td width="50%" valign="top">

**Small Language Model Development**

OpceanAI develops the NxG model family — language models fine-tuned on curated datasets of approximately 5,000 examples. Despite minimal training data and consumer hardware, NxG models consistently outperform larger models on factual honesty benchmarks, validating the organization's core research hypothesis.

<br>

**Imprint Theory**

A theoretical framework connecting information science, thermodynamics, and fundamental physics. The theory proposes a universal minimum imprint constant — designated **Գ** (Armenian letter Gim) — governing the minimum energetic cost of any irreversible physical or informational event. Six universal theorems have been formalized, including resolutions to the Boltzmann-Loschmidt-Zermelo paradox and a formal distinction between Gibbs entropy and physically observable entropy.

</td>
<td width="50%" valign="top">

**Zero-Budget Methodology**

All OpceanAI models are trained on owned consumer hardware with no external compute expenditure. Training hardware has included a Redmi 12 smartphone (Snapdragon 685), a MacBook Pro Intel 2020, and Google Colab Pro. This constraint is deliberate — it forces data efficiency over scale and produces findings applicable to edge deployment.

<br>

**Open Infrastructure**

OpceanAI publishes all models, datasets, and tooling under permissive open-source licenses. Every benchmark is conducted with full methodology disclosure. Evaluation uses lm-evaluation-harness under 0-shot conditions, a stricter protocol than the few-shot standard used by most comparable model releases.

</td>
</tr>
</table>

<br>

---

<br>

<div align="center">

## Model Family — NxG

</div>

<br>

<table>
<tr>
<td width="33%" valign="top">

**Yuuki NxG**

3B parameter language model fine-tuned from Qwen2.5-3B for open-ended conversation and general-purpose reasoning. Achieves the highest TruthfulQA score among all compared 3B-scale models under 0-shot evaluation — including the base model from which it was derived.

[![Model](https://img.shields.io/badge/Yuuki_NxG-HuggingFace-ffd21e?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/OpceanAI/Yuuki-NxG)
&nbsp;
[![DOI](https://img.shields.io/badge/DOI-10.57967%2Fhf%2F7915-024d8f?style=flat-square)](https://huggingface.co/OpceanAI/Yuuki-NxG)

</td>
<td width="33%" valign="top">

**Yuuki NxG Nano**

81M parameter language model fine-tuned from GPT-2. The smallest model in the NxG family. Achieves TruthfulQA parity with Llama-3.2-3B — a model 37 times larger — under stricter 0-shot evaluation conditions. Second only to Yuuki NxG 3B in TruthfulQA among all compared models.

[![Model](https://img.shields.io/badge/Yuuki_NxG_Nano-HuggingFace-ffd21e?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/OpceanAI/Yuuki-NxG-nano)
&nbsp;
[![DOI](https://img.shields.io/badge/DOI-10.57967%2Fhf%2F7926-024d8f?style=flat-square)](https://huggingface.co/OpceanAI/Yuuki-NxG-nano)

</td>
<td width="33%" valign="top">

**Yuuki NxG VL**

7B parameter vision-language model fine-tuned from Qwen2.5-VL-7B-Instruct. Extends the NxG family to multimodal tasks — text and image understanding. Trained on Google Colab A100. Community-quantized GGUF versions available independently.

[![Model](https://img.shields.io/badge/Yuuki_NxG_VL-HuggingFace-ffd21e?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/OpceanAI/Yuuki-NxG-vl)

</td>
</tr>
</table>

<br>

---

<br>

<div align="center">

## Benchmark Results — TruthfulQA

</div>

<br>

All OpceanAI results are evaluated 0-shot using lm-evaluation-harness. Competitor scores use few-shot prompting (5–25 shots), which systematically favors base models in direct comparisons.

<br>

| Model | Parameters | TruthfulQA | Evaluation |
|:------|:----------:|:----------:|:----------:|
| **Yuuki NxG** | **3B** | **50.87%** | **0-shot** |
| **Yuuki NxG Nano** | **81M** | **44.10%** | **0-shot** |
| Llama-3.2-3B | 3B | 44.0% | few-shot |
| Mistral-7B-v0.3 | 7B | 47.0% | few-shot |
| Phi-3-mini (3.8B) | 3.8B | 45.0% | few-shot |
| Gemma-2-2B | 2B | 39.0% | few-shot |
| GPT-2 (125M) | 125M | 31.73% | few-shot |

OpceanAI holds first and second place in TruthfulQA across all compared models. Both results are achieved under stricter evaluation conditions than all competitors.

<br>

---

<br>

<div align="center">

## Imprint Theory

</div>

<br>

The Imprint Theory is a universal framework proposing that every irreversible physical or informational event leaves a minimum measurable trace — an imprint — governed by a fundamental constant **Գ**. The theory connects thermodynamics, information science, quantum mechanics, and the arrow of time under a single formalism.

<br>

<table>
<tr>
<td width="50%" valign="top">

**Formalized Theorems**

| Theorem | Status |
|:--------|:------:|
| Generative Invariance | Complete |
| Second Law (Imprint) | Complete |
| Arrow of Time | Complete |
| Minimum Energetic Cost | Complete |
| Teorema 5 | Complete |
| Teorema 6 | Complete |

</td>
<td width="50%" valign="top">

**Key Results**

Resolution of the 154-year Boltzmann-Loschmidt-Zermelo paradox through formal distinction between Gibbs entropy and physically observable entropy S_obs.

Extension of the framework to approximately 50 scientific theories and 12 classical philosophical dilemmas.

The constant **Գ** (Armenian letter Gim) is the first fundamental constant in modern physics designated with an Armenian letter.

</td>
</tr>
</table>

Publication in progress. DOI registration via Zenodo pending.

<br>

---

<br>

<div align="center">

## Published Assets

</div>

<br>

| Asset | Type | Description |
|:------|:----:|:------------|
| [Yuuki NxG](https://huggingface.co/OpceanAI/Yuuki-NxG) | Model | 3B flagship language model |
| [Yuuki NxG Nano](https://huggingface.co/OpceanAI/Yuuki-NxG-nano) | Model | 81M lightweight variant |
| [Yuuki NxG VL](https://huggingface.co/OpceanAI/Yuuki-NxG-vl) | Model | 7B vision-language model |
| [Yuuki-dataset](https://huggingface.co/datasets/OpceanAI/Yuuki-dataset) | Dataset | Curated fine-tuning dataset (~5,000 examples) |
| [Imprint-Train-v3](https://huggingface.co/datasets/OpceanAI/Imprint-Train-v3) | Dataset | Training data for Imprint Theory experiments |
| [NHE-Benchmark](https://huggingface.co/datasets/OpceanAI/NHE-Benchmark) | Benchmark | Custom evaluation suite |

<br>

---

<br>

<div align="center">

## Tooling

</div>

<br>

<table>
<tr>
<td width="50%" valign="top">

**[yuy](https://github.com/YuuKi-OS/yuy)**<br>
CLI for downloading, managing, and running Yuuki models locally. Built in Rust for performance and reliability. Model registry, version management, and local inference in one tool.

<br>

**[yuy-chat](https://github.com/YuuKi-OS/yuy-chat)**<br>
Terminal-based TUI chat interface for local AI conversations. Conversation history, syntax highlighting, and terminal UI powered by Ratatui.

</td>
<td width="50%" valign="top">

**[Kaide](https://github.com/OpceanAI/kaide)** *(in development)*<br>
Terminal IDE with integrated AI assistance. Editor-agnostic, backend-configurable (Ollama, llama.cpp, remote VPS), git integration, and inline code completion. Designed for developers who work exclusively in terminal environments.

<br>

**[Yuuki Chat](https://yuuki-chat.vercel.app)**<br>
Web-based chat interface with research mode, YouTube integration, and support for multiple model variants.

</td>
</tr>
</table>

<br>

---

<br>

<div align="center">

## Roadmap

</div>

<br>

<table>
<tr>
<td width="50%" valign="top">

**Models**

| Project | Status |
|:--------|:------:|
| Yuuki NxG | Released |
| Yuuki NxG Nano | Released |
| Yuuki NxG VL | Released |
| OwO (QwQ-32B fine-tune) | Planned |
| Yuuki NxG VL Phase 2–10 | Planned |

</td>
<td width="50%" valign="top">

**Research**

| Paper | Status |
|:------|:------:|
| Imprint Theory (comprehensive) | In progress |
| Teoremas 1–6 | Complete |
| Zenodo DOI registration | Pending |
| Academic peer review submission | Planned |
| P≠NP connection | In progress |

</td>
</tr>
</table>

<br>

---

<br>

<div align="center">

## Infrastructure

</div>

<br>

OpceanAI operates a self-hosted infrastructure stack running entirely on a $7/month VPS (Hostinger KVM2, AMD EPYC 9355P, 8GB RAM) extended by HuggingFace Spaces as distributed compute workers. Total infrastructure cost: under $100/year.

| Component | Technology |
|:----------|:-----------|
| Git hosting | Forgejo (self-hosted) |
| Model serving | Ollama + HuggingFace Spaces |
| Distributed compute | Celery + Redis + frp tunnel |
| STT | Faster Whisper |
| TTS | Kokoro |
| Storage | HuggingFace Bucket + Nextcloud |

<br>

---

<br>

<div align="center">

## Philosophy

</div>

<br>

<table>
<tr>
<td width="50%" valign="top">

**Data Quality Over Scale**

The NxG family demonstrates consistently that 5,000 carefully selected training examples outperform models trained on orders of magnitude more data on factual honesty benchmarks. This finding is reproducible, documented, and challenges the prevailing assumption that model capability scales primarily with data volume.

<br>

**Radical Transparency**

Every evaluation is conducted with full methodology disclosure. Benchmark conditions that favor OpceanAI models — such as 0-shot vs few-shot evaluation — are explicitly noted rather than concealed. The goal is accurate representation of results, not optimized optics.

</td>
<td width="50%" valign="top">

**Accessibility**

Meaningful AI research does not require institutional affiliation, GPU clusters, or significant funding. OpceanAI exists as evidence of this. All models, datasets, benchmarks, and tooling are released under Apache 2.0 or equivalent permissive licenses.

<br>

**Theoretical Grounding**

The Imprint Theory provides a formal explanation for why data quality outperforms data quantity — rooted in physics rather than empirical observation alone. OpceanAI's practical results and theoretical framework are designed to reinforce each other.

</td>
</tr>
</table>

<br>

---

<br>

<div align="center">

## Community

</div>

<br>

<div align="center">

[![Discord](https://img.shields.io/badge/Discord-Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/j8zV2u8k)
&nbsp;&nbsp;
[![HuggingFace](https://img.shields.io/badge/HuggingFace-OpceanAI-ffd21e?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/OpceanAI)
&nbsp;&nbsp;
[![Sponsor](https://img.shields.io/badge/Sponsor-GitHub_Sponsors-ea4aaa?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/aguitauwu)

</div>

<br>

---

<br>

<div align="center">

## Citation

</div>

---

<br>

<div align="center">

**Independent research. Reproducible results. Open source.**

<br>

[![OpceanAI](https://img.shields.io/badge/OpceanAI-2026-0D1117?style=for-the-badge)](https://huggingface.co/OpceanAI)

<br>

*The evidence that meaningful AI research does not require a data center.*

</div>


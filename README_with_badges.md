![License: ARL](https://img.shields.io/badge/license-ARL-blue)
![Reasoning Type: Modular](https://img.shields.io/badge/reasoning-modular-critical)
![Use Case: AI](https://img.shields.io/badge/use--case-AI%20Logic%20Layers-yellowgreen)

# Authorship Reasoning Licenses (ARL)

This repository defines three modular, open-source licenses for AI reasoning components designed to work independently of large language models (LLMs). These licenses are tailored for use with prompt logic, reasoning adapters, symbolic flows, and agent policies.

## 🔍 Overview

Reasoning layers in AI systems—like chain-of-thought templates, IRAC frameworks, symbolic rule chains, and decision agents—require distinct treatment from foundation models. These licenses standardize how those components can be reused, shared, and attributed.

### 🧾 Included Licenses

- **Herbert** – ARL-Permissive (MIT-style, fully open): `Herbert.txt`
- **Asimov** – ARL-Balanced (Apache-style): `Asimov.txt`
- **Heinlein** – ARL-Restricted (Meta-style): `Heinlein.txt`

📘 Learn more about each in [`LICENSE_VARIANTS.md`](./LICENSE_VARIANTS.md)

## 🛠 Use Cases

These licenses cover:
- Prompt scaffolding files (YAML/JSON/TXT)
- Reasoning adapters (LoRA / delta)
- Logic policies and symbolic rule chains
- Agent control flows (e.g., ReAct, decision graphs)

They **do not** cover:
- Foundation model weights
- Training datasets
- Tokenizers or embeddings

## 🧠 Why ARL?

- Modular reasoning should be shareable
- Attribution preserves integrity
- Technical separation from foundation models is enforceable
- Licensing helps balance innovation, research, and commercial application

## 📤 How to Use

Include the license file you choose in your repo and make sure your reasoning logic is technically separable from model weights. Attribution must be shown in public deployments or documentation.

## 📫 Contact

For questions or commercial licensing:
**legal@authorship.com**

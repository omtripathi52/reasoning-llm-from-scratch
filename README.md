<div align="center">

# 🧠 Reasoning LLM From Scratch

### Modern Reasoning Techniques for Large Language Models in PyTorch

<p align="center">

![Python](https://img.shields.io/badge/Python-3.12+-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-2.x-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Reasoning](https://img.shields.io/badge/Focus-Reasoning%20LLMs-6C63FF?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-success?style=flat-square)

</p>

An educational implementation exploring modern techniques for improving the reasoning capabilities of large language models, covering evaluation, inference-time scaling, self-refinement, reinforcement learning, and knowledge distillation.

</div>

---

## 📖 Overview

This repository explores a collection of practical techniques used to improve reasoning performance in modern language models.

The implementation progresses from pretrained model inference and evaluation to advanced reasoning methods such as inference-time scaling, reinforcement learning, and knowledge distillation, with each script focusing on a specific stage of the reasoning pipeline.

---

## ✨ Features

- ✅ Pretrained language model inference
- ✅ Reasoning evaluation
- ✅ Inference-time scaling
- ✅ Self-refinement
- ✅ Reinforcement learning
- ✅ GRPO optimization
- ✅ Knowledge distillation

---

## 📂 Repository Structure

| Script | Description |
|---------|-------------|
| `01-generating_text_with_a_pretrained_llm.py` | Text generation using a pretrained language model |
| `02-evaluating_reasoning_models.py` | Reasoning evaluation and answer analysis |
| `03-improving_reasoning_with_inference_time_scaling.py` | Inference-time scaling strategies |
| `04-inference_time_scaling_via_self_refinement.py` | Iterative self-refinement techniques |
| `05-training_reasoning_models_with_reinforcement_learning.py` | Reinforcement learning for reasoning models |
| `06-improving_grpo_for_reinforcement_learning.py` | GRPO optimization techniques |
| `07-distilling_reasoning_models_for_efficient_reasoning.py` | Knowledge distillation for efficient reasoning models |

---

## 🏗️ Implementation Pipeline

```mermaid
flowchart LR

A["Pretrained LLM"]
B["Reasoning Evaluation"]
C["Inference-Time Scaling"]
D["Self-Refinement"]
E["Reinforcement Learning"]
F["Knowledge Distillation"]
G["Reasoning Model"]

A --> B
B --> C
C --> D
D --> E
E --> F
F --> G
```

---

## 🚀 Getting Started

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the scripts sequentially to explore the complete reasoning pipeline.

```bash
python 01-generating_text_with_a_pretrained_llm.py

python 02-evaluating_reasoning_models.py

python 03-improving_reasoning_with_inference_time_scaling.py

python 04-inference_time_scaling_via_self_refinement.py

python 05-training_reasoning_models_with_reinforcement_learning.py

python 06-improving_grpo_for_reinforcement_learning.py

python 07-distilling_reasoning_models_for_efficient_reasoning.py
```

Each script can also be executed independently to explore a specific reasoning technique.

---

## 🧩 Topics Covered

- Pretrained Language Models
- Reasoning Evaluation
- Inference-Time Scaling
- Self-Refinement
- Reinforcement Learning
- GRPO Optimization
- Knowledge Distillation

---
<div align="center">

# Reasoning LLM From Scratch

### Implementing Modern Reasoning Techniques for Large Language Models in PyTorch

![Python](https://img.shields.io/badge/Python-3.12+-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-2.x-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-success?style=flat-square)

A PyTorch implementation demonstrating how reasoning capabilities can be added to pretrained large language models through inference-time scaling, reinforcement learning, and model distillation.

</div>

---

## Features

- Reasoning LLM pipeline
- Pretrained base LLM inference
- Chain-of-Thought prompting
- Self-Consistency decoding
- Self-Refinement
- Reinforcement Learning (GRPO)
- Reasoning model distillation
- Evaluation pipeline

---

## Pipeline

```mermaid
flowchart LR

A["Pretrained LLM"]
B["Inference-Time Scaling"]
C["Self-Refinement"]
D["Reinforcement Learning"]
E["Knowledge Distillation"]
F["Reasoning LLM"]

A --> B
B --> C
C --> D
D --> E
E --> F
```

---

## Project Structure

```text
reasoning-llm-from-scratch/

├── src/
│   ├── inference.py
│   ├── evaluation.py
│   ├── inference_scaling.py
│   ├── self_refinement.py
│   ├── reinforcement_learning.py
│   ├── distillation.py
│   ├── model.py
│   └── utils.py
│
├── examples/
├── checkpoints/
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Installation

```bash
git clone https://github.com/<your-username>/reasoning-llm-from-scratch

cd reasoning-llm-from-scratch

pip install -r requirements.txt
```

---

## Usage

Run inference

```bash
python src/inference.py
```

Evaluate the model

```bash
python src/evaluation.py
```

Train using reinforcement learning

```bash
python src/reinforcement_learning.py
```

Generate distilled models

```bash
python src/distillation.py
```

---

## Example

**Question**

```text
If Alice has 12 apples and gives 5 away, then buys 8 more, how many apples does she have?
```

**Reasoning Output**

```text
12 - 5 = 7

7 + 8 = 15

Answer: 15
```

---

## References

This project was built for educational purposes while studying modern reasoning language models.

---

## Acknowledgements

A PyTorch implementation exploring modern techniques for improving the reasoning capabilities of large language models.

---

## License

MIT License

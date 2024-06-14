# LLM_visual_persona

### Visual Persona for LLM Experiments

This repository contains the official code for running Visual Persona for LLM experiments and subsequent analyses presented in the paper.

## Data

Our curated dataset of 5185 novel, fantasy-like avatar images is available at:

```python
from datasets import load_dataset

dataset = load_dataset("NOTKNOWN/FAData")
```
## Assigning Visual Persona to LLMs

- `study1_GPT4o.ipynb` and `study1_Claude3_haiku.ipynb`: These notebooks involve assigning a visual persona to the LLM, followed by a participation in a four-round ultimatum game with a confederate who exhibits fixed behavior.

- `study2_GPT4o.ipynb` and `study2_Claude3_haiku.ipynb`: These notebooks involve assigning a visual persona to each LLM, followed by a participation in a four-round ultimatum game between two LLMs.

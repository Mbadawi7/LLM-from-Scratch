# LLM from Scratch 🧠

This project is a **learning exercise** where I followed the book  
[*Build a Large Language Model (From Scratch)* by Sebastian Raschka](https://github.com/rasbt/LLMs-from-scratch).  

The goal is to understand, step by step, how modern LLMs work —  
from dataset preparation → tokenization → embeddings → transformer blocks → training loop.

---

## Dataset
We use the **YouTube Spam Collection Dataset** (included as CSVs in `youtube+spam+collection/`).

---

## Features
- Data loading and cleaning with pandas
- Tokenization using [tiktoken](https://github.com/openai/tiktoken)
- Token and positional embeddings
- Transformer block (multi-head attention + feed-forward network)
- Training loop with PyTorch DataLoader

---

## Requirements
See `requirements.txt` for dependencies.

```bash
pip install -r requirements.txt

## Notes
- This is an **educational project** — not a production-ready LLM.
- All steps are inside one notebook for clarity.
- Project was implemented and tested on a **MacBook Air (Apple Silicon, macOS)**.

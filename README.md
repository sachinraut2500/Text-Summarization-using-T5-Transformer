# 📝 Text Summarization using T5 Transformer

This project uses the pretrained **T5** transformer model for abstractive text summarization.

---

## ⚙️ Requirements

```bash
pip install transformers torch
📌 How to Use
Run the script to summarize example text or modify the input in main():

bash

python text_summarization_t5.py

Model Details
Model: t5-small (can be switched to larger models like t5-base, t5-large)

Uses beam search for better summaries

Handles input truncation to max length 512 tokens

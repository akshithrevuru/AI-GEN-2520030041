# Week 7 – Generative AI Programming Practical

Inspect next-token logits and top-k candidate probabilities from `openai-community/gpt2` using PyTorch and Hugging Face Transformers.

## Files
- `main.py` – Loads GPT-2, runs inference on sample prompts, displays top-5 next-token candidates with probabilities, and exports results to CSV.
- `requirements.txt` – Python dependencies (`torch`, `transformers`).
- `week7_probability_results.csv` – Generated CSV containing prompts, ranks, candidate tokens, token IDs, and probabilities.

## Setup & Usage
```bash
pip install -r requirements.txt
python main.py
```

# Week 6 – Generative AI Programming (Release v0.1)

Create the golden question set (`golden_set.json`) with expected answers, keywords, and sources, and run the first baseline evaluation (`v0.1`) using Ollama (`llama3.2`).

## Files
- `golden_set.json` – 30 golden questions with expected answers, expected keywords, and documentation sources.
- `main.py` – Queries `llama3.2` via the local Ollama API, computes keyword-coverage scores, prints a summary, and exports `baseline_results.csv`.
- `requirements.txt` – Python dependencies (`requests`).
- `baseline_results.csv` – Baseline evaluation results (`Release: v0.1`).

## Baseline Evaluation Results (Release v0.1)
- **Model:** `llama3.2`
- **Total Questions:** 30
- **Successful Responses:** 30
- **Passed Questions (>= 60%):** 12
- **Questions for Review (< 60%):** 18
- **Failed Requests:** 0
- **Average Keyword Coverage:** 47.22 %

## Setup & Usage
```bash
ollama pull llama3.2
pip install -r requirements.txt
python main.py
```

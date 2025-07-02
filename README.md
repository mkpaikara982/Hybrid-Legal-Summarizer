# Hybrid Approach to Legal Long Document Summarization

This project explores a hybrid summarization approach for long legal documents using transformer models (BERT, T5) and OpenAI LLMs via LangChain.

## 🧠 Models Used

- BERT (Extractive)
- T5 (Abstractive)
- OpenAI GPT (via LangChain)

## 📂 Folder Structure

- `notebooks/` – Jupyter notebooks used for training, inference, and evaluation
- `data/` – Contains ROUGE score outputs and model-generated summaries
- `src/` – Modularized code (optional, if converting notebooks to scripts)
- `results/` – Evaluation results or plots

## 🧪 Evaluation

ROUGE scores were computed for all summarizers. Final comparison is stored in:
- `consolidated_rogue_scores.csv`

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/Hybrid-Legal-Summarizer.git
cd Hybrid-Legal-Summarizer
pip install -r requirements.txt

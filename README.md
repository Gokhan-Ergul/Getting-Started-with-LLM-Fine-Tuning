# Getting Started with LLM Fine-Tuning

This repository demonstrates how to fine-tune a pre-trained transformer model on a GLUE benchmark task using Hugging Face 🤗 Transformers and Datasets.  
We use **BERT (bert-base-uncased)** as the base model and fine-tune it on the **MRPC** (Microsoft Research Paraphrase Corpus) dataset.  
Training logs and metrics are tracked with **Weights & Biases (wandb)**.

---

## 📂 Project Structure

- `fine_tuning.ipynb` → Jupyter Notebook with the full fine-tuning pipeline    
- Trained model checkpoints can be logged and visualized via [Weights & Biases](https://wandb.ai)  

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Gokhan-Ergul/<your-repo>.git
cd <your-repo>

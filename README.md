# 📰 News Topic Classifier using BERT

This project fine-tunes a pre-trained **BERT (bert-base-uncased)** model to classify news articles into one of four categories using the **AG News dataset**. It uses Hugging Face Transformers for model training and **Gradio** for deployment via a simple web interface.

---

## 📚 Dataset

- **AG News Dataset**
- Source: [Hugging Face Datasets](https://huggingface.co/datasets/ag_news)
- Classes:
  - `World`
  - `Sports`
  - `Business`
  - `Sci/Tech`

---

## 🚀 Features

- Combines **title** and **description** into a single input for classification
- Uses Hugging Face `transformers` and `datasets` libraries
- Preprocesses data using `BertTokenizer`
- Fine-tunes `bert-base-uncased` using `Trainer`
- Evaluates using **Accuracy** and **F1 Score**
- Provides an interactive **Gradio** interface for real-time predictions

---

## 📦 Libraries Used

```bash
transformers
datasets
evaluate
gradio
sklearn
torch
pandas


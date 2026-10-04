# 🤖 Question Answering System

## 📌 Objective

The objective of this project is to build a Question Answering system that can understand a given passage and extract the most relevant answer to a user's question.

## 🛠️ Technologies Used

- Python
- Hugging Face Transformers
- DistilBERT
- PyTorch
- Gradio
- Google Colab

## 🧠 Model

This project uses:

`distilbert-base-cased-distilled-squad`

The model is a DistilBERT model fine-tuned for extractive Question Answering using the SQuAD dataset.

## 🔄 Workflow

Context + Question
        ↓
DistilBERT Tokenizer
        ↓
Question Answering Model
        ↓
Start & End Answer Positions
        ↓
Extract Answer
        ↓
Display Answer + Confidence

## ✨ Features

- Accepts custom passages
- Accepts natural-language questions
- Extracts answers directly from the passage
- Displays confidence score
- Interactive Gradio interface
- Uses a pretrained Transformer model

## 🧪 Example

### Context

Machine Learning is a subset of Artificial Intelligence. It allows computers to learn patterns from data and make predictions without being explicitly programmed for every task.

### Question

What is Machine Learning?

### Answer

A subset of Artificial Intelligence.

## 🚀 How to Run

1. Open the notebook in Google Colab.
2. Install the required libraries.
3. Load the pretrained DistilBERT model.
4. Enter a context/passage.
5. Enter a question.
6. Click **Get Answer**.

## 📦 Installation

```bash
pip install transformers torch gradio

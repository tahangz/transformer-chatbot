# Transformer Chatbot 🤖
A simple chatbot built using the vanilla Transformer architecture.
This project implements a basic chatbot using the original Transformer architecture introduced by Google in the paper ["Attention Is All You Need"](https://arxiv.org/abs/1706.03762).

> 🧠 This work is inspired by Google's groundbreaking research on attention mechanisms and sequence modeling.

## 🔧 Model Overview
The Transformer uses:
- Multi-head self-attention
- Positional encoding to preserve word order
- Encoder-decoder blocks with residual connections

### Key Parameters
- `d_model`: Embedding size
- `n_heads`: Number of attention heads
- `num_layers`: Number of encoder/decoder layers
- `dropout`: Dropout rate for regularization

## 🧪 Pipeline
1. **Preprocessing** – Tokenize and pad sentence pairs
2. **Training** – Minimize cross-entropy between predicted and target tokens
3. **Inference** – Generate replies using greedy decoding

## 🛠 Requirements
- Python 3.8+
- PyTorch
- NumPy
- Jupyter Notebook

## 🚀 Usage
Open `transformer_chatbot.ipynb` and run all cells to train and chat with the model.

---


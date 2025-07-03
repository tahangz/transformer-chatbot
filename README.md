# Transformer Chatbot 🤖
A simple chatbot built using the vanilla Transformer architecture.
This project implements a basic chatbot using the original Transformer architecture introduced by Google in the paper ["Attention Is All You Need"](https://arxiv.org/abs/1706.03762).

> 🧠 This work is inspired by Google's groundbreaking research on attention mechanisms and sequence modeling.


<p align="center">
  <img src="Screenshot 2025-07-03 031652.png" alt="Sample Gesture" width="900"/>
</p>

## 🔧 Model Overview
The Transformer uses:
- Multi-head self-attention
- Positional encoding to preserve word order
- Encoder-decoder blocks with residual connections

### Key Parameters
- `d_model`: Embedding size (e.g. 512)
- `n_heads`: Number of attention heads (e.g. 8)
- `num_layers`: Layers in encoder/decoder (e.g. 4)
- `dropout`: Regularization to prevent overfitting

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


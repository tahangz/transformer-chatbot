# Transformer Chatbot 🤖

A simple chatbot built using the vanilla Transformer architecture (Vaswani et al., 2017). It uses the encoder-decoder attention mechanism to learn basic conversational patterns from paired text data.

## Features
- Encoder-Decoder Transformer (vanilla version)
- Positional Encoding
- Trained on basic dialogue pairs
- Inference with greedy decoding

## 🔧 Model Overview
The Transformer uses:
- Multi-head self-attention
- Positional encodings to retain word order
- Feed-forward layers and residual connections

### Key Parameters
- `d_model`: Embedding size (512)
- `n_heads`: Number of attention heads (8)
- `num_layers`: Layers in encoder/decoder (4)
- `dropout`: Regularization to prevent overfitting

## 🧪 Pipeline
1. **Preprocessing** – Tokenize and pad sentence pairs
2. **Training** – Minimize cross-entropy between predicted and target tokens
3. **Inference** – Generate replies token-by-token using greedy decoding

## 🛠 Requirements
- Python 3.8+
- PyTorch
- NumPy
- Jupyter Notebook

## 🚀 Usage
Open `transformer_chatbot.ipynb` and run all cells to train and interact with the chatbot.

---


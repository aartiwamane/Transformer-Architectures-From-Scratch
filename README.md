# Transformer Architectures from Scratch

A practical implementation of three major Transformer architectures using **Python, TensorFlow, and Keras**. This repository demonstrates how Transformer models process natural language through attention mechanisms, positional embeddings, encoder-decoder architectures, and autoregressive text generation.

## Project Overview

This repository contains three independent implementations demonstrating different applications of Transformer architectures.

### 1. Transformer Encoder – Sentiment Classification

**File:** `1_Transformer_Encoder_Sentiment_Classification.py`

Implements an Encoder-based Transformer model for binary sentiment classification of text sentences.

**Key Concepts:**
- Text Tokenization and Padding
- Token Embedding
- Positional Embedding
- Multi-Head Self-Attention
- Transformer Encoder Block
- Feed Forward Neural Network
- Layer Normalization and Dropout
- Binary Classification using Sigmoid Activation

**Objective:** Classify input sentences into Positive or Negative sentiment categories.

### 2. Transformer Encoder-Decoder – Neural Machine Translation

**File:** `2_Transformer_Encoder_Decoder_Translation.py`

Implements an Encoder-Decoder Transformer architecture for a simple English-to-Marathi translation task.

**Key Concepts:**
- Source and Target Text Vectorization
- Token and Positional Embeddings
- Transformer Encoder
- Masked Multi-Head Self-Attention
- Encoder-Decoder Cross-Attention
- Feed Forward Network
- Causal Attention Masking
- Sequence-to-Sequence Learning
- Autoregressive Translation

**Objective:** Learn English-to-Marathi sentence mappings and generate translated output one token at a time.

### 3. Decoder-Only Transformer – Mini GPT

**File:** `3_Transformer_Decoder_Only_Mini_GPT.py`

Implements a simplified GPT-style Decoder-Only Transformer architecture for next-word prediction and text generation.

**Key Concepts:**
- Text Tokenization
- Input and Target Sequence Preparation
- Token and Positional Embeddings
- Masked Self-Attention
- Causal Attention Mask
- Transformer Decoder Blocks
- Next-Word Prediction
- Autoregressive Text Generation

**Objective:** Predict the next word from a given input sequence and generate text iteratively.

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Natural Language Processing (NLP)
- Deep Learning
- Transformer Architecture

## Project Structure

```text
Transformer-Architectures-From-Scratch/
│
├── 1_Transformer_Encoder_Sentiment_Classification.py
├── 2_Transformer_Encoder_Decoder_Translation.py
├── 3_Transformer_Decoder_Only_Mini_GPT.py
├── requirements.txt
└── README.md
```

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/aartiwamane/Transformer-Architectures-From-Scratch.git
```

### 2. Navigate to the Project Directory

```bash
cd Transformer-Architectures-From-Scratch
```

### 3. Create a Virtual Environment (Recommended)

```bash
python -m venv venv
```

Activate the environment on Windows:

```bash
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Execute the Programs

Run each implementation independently:

```bash
python 1_Transformer_Encoder_Sentiment_Classification.py
```

```bash
python 2_Transformer_Encoder_Decoder_Translation.py
```

```bash
python 3_Transformer_Decoder_Only_Mini_GPT.py
```

## Learning Outcomes

Through these implementations, this repository demonstrates practical understanding of:

- Fundamental Transformer architecture and its components.
- Differences between Encoder, Encoder-Decoder, and Decoder-Only architectures.
- Self-Attention and Multi-Head Attention mechanisms.
- Positional information in sequential data.
- Masked attention and causal masking.
- Sequence-to-sequence learning.
- Next-token prediction and autoregressive generation.
- Building and training NLP models using TensorFlow and Keras.

## Important Note

These implementations use small, manually created datasets for educational and experimentation purposes. They demonstrate the fundamental working principles of Transformer architectures and are not intended to provide production-level translation, sentiment analysis, or language generation.

The Decoder-Only implementation is a simplified GPT-style model trained from scratch on a small dataset. It is not a pretrained GPT model.

## Author

**Aarti Wamane**

M.Tech Computer Engineering | Deep Learning | Machine Learning | Python | Software Development

- GitHub: [@aartiwamane](https://github.com/aartiwamane)
- LinkedIn: [Aarti Wamane](https://linkedin.com/in/aarti-wamane-5276562a6)

---

*Exploring Deep Learning and Natural Language Processing through practical implementations.*


# Transformer From Scratch

## Overview
This project implements a Transformer encoder from the ground up using PyTorch. It helps demystify each building block—multi-head attention, positional encodings, and feedforward networks—by re-creating them with minimal abstractions.

We train it on a synthetic **copy task** where the model must predict the input sequence, testing whether it's learning position-sensitive relationships.

## Architecture
Input → Embedding + PositionalEncoding →
[EncoderLayer × N] →
LayerNorm →
Linear Projection →
CrossEntropy Loss

---

## Structure
transformer_from_scratch/
├── main.py # Core model and training loop
├── requirements.txt # Python dependencies
└── README.md # Project documentation

---

## Run It
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   
python main.py



# Encoder-Decoder Transformer Model for Neural Machine Translation (NMT)

This repository contains the implementation of an Encoder-Decoder Transformer model for Neural Machine Translation (NMT). The model follows the Transformer architecture proposed by Vaswani et al. (2017) and is designed to handle sequence-to-sequence tasks such as language translation.

## Overview

The model consists of two main components:
1. **Encoder**: Takes the source sequence (e.g., a sentence in the source language) and produces a set of hidden states that represent the input sequence.
2. **Decoder**: Uses the encoder's output and generates the target sequence (e.g., the translated sentence).

The model utilizes self-attention mechanisms and multi-head attention for both encoding and decoding, with a feed-forward network in each transformer block. It also includes token and positional embeddings to process the input sequences.

## Features
- **Encoder-Decoder Architecture**: A sequence-to-sequence model for tasks like language translation.
- **Multi-Head Self-Attention**: Each encoder and decoder block uses multi-head self-attention to model complex dependencies in the input and output sequences.
- **Learned Positional Embeddings**: Instead of using fixed sinusoidal embeddings, the model uses learned positional embeddings.
- **Customizable Layers**: The number of encoder and decoder layers, attention heads, and hidden size can be adjusted for different tasks.

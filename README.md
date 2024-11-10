# Self-Attention and Positional Encoding in NLP

This repository contains a hands-on lab project focused on understanding and implementing self-attention mechanisms and positional encoding, two foundational techniques in natural language processing (NLP). This project was completed as part of IBM's Generative AI Engineering with LLMs Specialization course.

## Overview

Self-attention and positional encoding are critical for modern NLP models, such as transformers, where they help the model understand the relationships between words in a sequence. This project demonstrates:
- The theory behind self-attention
- Implementation of tokenization and encoding methods
- Creation of matrix-based translation functions
- Use of softmax functions for attention layers
- Translating sequences using learned attention weights

## Table of Contents

1. [Self-Attention Mechanism](#self-attention-mechanism)
2. [Positional Encoding](#positional-encoding)
3. [Implementation Details](#implementation-details)
    - Tokenization
    - One-Hot Encoding
    - Translation Functions
    - Softmax and Similarity Measures
4. [Requirements](#requirements)
5. [References](#references)

## Self-Attention Mechanism

In this section, we explore the self-attention mechanism, allowing the model to focus on different words depending on their context in a sequence. This part includes both theoretical explanations and practical code implementations.

## Positional Encoding

Positional encoding is used to retain the order of words in a sequence, which is crucial for context in NLP tasks. Here, we dive into different encoding methods and their importance in language models.

## Implementation Details

This project includes:
- **Tokenization**: Encoding and decoding tokens using one-hot vectors.
- **Translation Functions**: Matrix-based translation function with attention weights.
- **Attention Mechanisms**: Implementing softmax functions for attention scores and translating sequences using learned weights.

## Requirements

- Python 3.7+
- NumPy
- PyTorch

## References

- [IBM AI Engineering Professional Certificate](https://www.coursera.org/professional-certificates/ai-engineer?)
- [Generative AI Engineering with LLMs Specialization](https://www.coursera.org/specializations/generative-ai-engineering-with-llms)
- [Generative AI Language Modeling with Transformers](https://www.coursera.org/learn/generative-ai-language-modeling-with-transformers?specialization=generative-ai-engineering-with-llms)

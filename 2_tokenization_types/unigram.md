# Unigram Language Model Tokenization

Unigram tokenization treats token selection as a probabilistic process.

## How It Works

- Start with a large candidate vocabulary
- Remove tokens that reduce likelihood
- Final vocabulary is probabilistically optimal

## Used By

- SentencePiece
- LLaMA models

## Advantages

- Multiple tokenization paths
- Robust to noise
- Language independent

## Drawbacks

- Computationally expensive
- Harder to interpret

Unigram tokenization is flexible and research-driven.

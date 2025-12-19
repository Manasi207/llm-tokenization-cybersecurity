# Tokenization Pipeline Overview

Tokenization is a multi-stage pipeline tightly integrated with the LLM.

## Pipeline Flow

1. Text normalization (Unicode, casing)
2. Pre-tokenization (splitting rules)
3. Subword segmentation
4. Token-to-ID mapping
5. Embedding lookup

## Visualization

Raw Text
↓
Tokenizer
↓
Token IDs
↓
Embedding Layer
↓
Transformer Model

Each stage influences accuracy and security.

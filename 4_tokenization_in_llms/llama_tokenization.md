# Tokenization in LLaMA Models

LLaMA models use SentencePiece with Unigram tokenization.

## Why This Matters

- Language-agnostic
- No whitespace assumptions
- Better multilingual handling

## Security Angle

- Byte-level fallback prevents crashes
- Reduced OOV attack vectors

LLaMA tokenization balances research and production needs.

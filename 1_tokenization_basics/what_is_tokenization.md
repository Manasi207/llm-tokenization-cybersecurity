# What is Tokenization?

Tokenization is the foundational process that allows Large Language Models (LLMs) to understand human language.
Since LLMs operate on numbers rather than raw text, tokenization converts input text into smaller units called tokens, which are then mapped to numerical IDs.

In simple terms:

> Tokenization = Text → Tokens → Numbers

## Example

Input:
"Cybersecurity is evolving fast"

Possible tokens:
["Cyber", "security", "is", "evolving", "fast"]

Mapped token IDs:
[4312, 9821, 45, 12987, 341]

## Why Tokenization Exists

- Neural networks cannot process raw text
- Tokenization creates a structured, machine-readable representation
- Enables vocabulary control and generalization

## Key Characteristics

- Tokens can be words, subwords, characters, or bytes
- Tokenization strategy affects accuracy, speed, and cost
- Every LLM is tightly coupled with its tokenizer

Tokenization is not preprocessing — it is **part of the model itself**.

# Byte Pair Encoding (BPE)

Byte Pair Encoding is a subword tokenization algorithm widely used in GPT-based models.

## How BPE Works

1. Start with character-level tokens
2. Count most frequent adjacent pairs
3. Merge the most frequent pair
4. Repeat until vocabulary limit is reached

## Example

Initial:
["l", "o", "w", "e", "r"]

After merges:
["low", "er"]

## Advantages

- Efficient vocabulary size
- Handles unknown words gracefully
- Language-agnostic

## Limitations

- Greedy merging
- Not probabilistic
- Sensitive to training data

BPE is fast, scalable, and production-proven.

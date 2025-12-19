# Word, Character, and Subword Tokenization

## Word-level Tokenization

Splits text by whitespace or punctuation.

Example:
"network security" → ["network", "security"]

Pros:

- Simple
- Human-readable

Cons:

- Large vocabulary
- Fails on unseen words (OOV problem)

## Character-level Tokenization

Splits text into characters.

Example:
"hack" → ["h", "a", "c", "k"]

Pros:

- No OOV issue
- Fine-grained control

Cons:

- Very long sequences
- Weak semantic understanding

## Subword Tokenization

Breaks words into meaningful sub-parts.

Example:
"tokenization" → ["token", "ization"]

Pros:

- Best balance of efficiency and semantics
- Handles rare and new words

This is the **industry standard** for LLMs.

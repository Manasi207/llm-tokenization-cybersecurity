# WordPiece Tokenization

WordPiece is used in models like BERT and focuses on maximizing likelihood rather than frequency.

## Core Idea

Select subwords that maximize the probability of the training corpus.

## Example

"unhappiness" → ["un", "happi", "ness"]

## Key Features

- Probabilistic selection
- Uses continuation markers (##)
- Optimized for masked language models

## Strengths

- Better semantic consistency
- Strong performance in NLP tasks

## Weaknesses

- Slower training
- Vocabulary dependent

WordPiece prioritizes linguistic quality over speed.

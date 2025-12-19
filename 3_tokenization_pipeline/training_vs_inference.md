# Tokenization During Training vs Inference

## Training Phase

- Vocabulary is learned
- Token statistics are collected
- Token distribution is optimized

## Inference Phase

- Vocabulary is frozen
- Only encoding & decoding happens
- Token limits enforce safety and cost

## Key Difference

Training defines _what the model can understand_  
Inference defines _how the model behaves in production_

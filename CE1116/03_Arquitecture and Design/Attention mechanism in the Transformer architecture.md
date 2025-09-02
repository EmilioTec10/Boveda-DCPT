---
Last Modification: 2025-08-08 09:09
tags:
  - Sofware-Engineering
  - LLMs
  - Transformers
Theme: AI
---


## 📚 Idea/Concept 
The attention mechanism in the Transformer architecture is a method that allows the model to weigh the relevance of each token in a sequence with respect to the others, instead of processing them uniformly. The most widely used is self-attention, where each token generates three representations: query, key, and value.

The similarity calculation between query and key determines how important one token is relative to another, and this relevance is used to combine the values into a contextualized representation. This process, repeated in parallel through multi-head attention, enables the Transformer to capture different semantic relationships and dependencies at various scales within the sequence.
## 📌 Key points (Optional)
- The attention mechanism lets the model weigh the relevance of each token in a sequence instead of treating them uniformly.
- In self-attention, each token generates three representations: query, key, and value. The similarity between query and key determines importance, which is then used to combine values into contextualized representations.
- Multi-head attention repeats this process in parallel, allowing the Transformer to capture semantic relationships and dependencies at multiple scales.

## 🔗 Connections
- [[Large Language Models (LLMs)]]
- [[Tokenization]]


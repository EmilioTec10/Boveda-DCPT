---
Last Modification: 2025-08-08 09:09
tags:
  - Sofware-Engineering
  - LLMs
  - Transformers
Theme: AI
---


## 📚 Idea/Concept 
The context window of a model is the maximum number of tokens it can process simultaneously when generating or interpreting text. It acts as an active memory, as it determines how much prior content the model can use to maintain coherence in long sequences.

From a computational perspective, this limit constitutes a bottleneck: in each layer of the self-attention mechanism, the computational cost scales with a complexity of O(n²·d), where n is the sequence length (tokens in the window) and d is the embedding dimension.
## 📌 Key points (Optional)
- The context window defines the maximum number of tokens a model can process at once, acting as active memory to preserve coherence in long sequences.
- It represents a computational bottleneck because in each self-attention layer the cost scales with O(n²·d), where n is the sequence length and d is the embedding dimension.

## 🔗 Connections
- [[Large Language Models (LLMs)]]
- [[Tokenization]]


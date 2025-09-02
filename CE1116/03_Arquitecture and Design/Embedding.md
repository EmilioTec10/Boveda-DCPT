---
Last Modification: 2025-08-08 09:09
tags:
  - Sofware-Engineering
  - LLMs
  - Transformers
Theme: AI
---


## 📚 Idea/Concept 
An embedding is a vector representation in a high-dimensional space that assigns each token a numerical point capturing its semantic, syntactic, and contextual relationships.

In models such as Transformers, the initial embeddings come from a lookup table, where each token is associated with a trainable vector. These vectors are then refined in the attention layers, which incorporate sequence context to dynamically adjust the meaning of each token according to its surroundings.

Training adjusts these vectors through backpropagation and gradient descent, optimizing the representation according to the target task (for example, predicting the next token).
## 📌 Key points (Optional)
- An embedding is a vector representation in a high-dimensional space that encodes the semantic, syntactic, and contextual relationships of tokens.
- In Transformers, initial embeddings come from a lookup table with trainable vectors, which are later refined in the attention layers to incorporate context.
- These vectors are learned and optimized during training through backpropagation and gradient descent.

## 🔗 Connections
- [[Tokenization]]
- [[Large Language Models (LLMs)]]


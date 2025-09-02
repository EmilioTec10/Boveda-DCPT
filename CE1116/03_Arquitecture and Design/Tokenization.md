---
Last Modification: 2025-08-08 09:09
tags:
  - Sofware-Engineering
  - LLMs
  - Transformers
Theme: AI
---


## 📚 Idea/Concept 
Tokenization is the process of converting raw text into minimal units called tokens, which are then mapped to numerical identifiers. This step is fundamental because machine learning algorithms can only process information in numerical form.

Tokens can correspond to whole words, subwords, characters, or special symbols, depending on the chosen scheme. In modern architectures such as Transformers, subword-based methods (Byte Pair Encoding, WordPiece, SentencePiece) are used to maintain a finite vocabulary and mitigate the out-of-vocabulary (OOV) problem by breaking down rare terms into known fragments.
## 📌 Key points (Optional)
- Tokenization converts raw text into tokens mapped to numerical identifiers, making it possible for machine learning models to process text.
- Tokens can represent words, subwords, characters, or special symbols, depending on the method used.
- Modern Transformer models use subword methods like BPE, WordPiece, or SentencePiece to keep the vocabulary finite and handle out-of-vocabulary words by splitting them into smaller known fragments.

## 🔗 Connections
- [[Large Language Models (LLMs)]]
- [[Embedding]]
- [[Attention mechanism in the Transformer architecture]]
- [[Context window of a model]]


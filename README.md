# Deep Unfolding / Unrolling

This repository contains code and experiments for Deep Unfolding/Unrolling.

## 📌 Overview
The project explores **deep unfolding (unrolling)** – a method of designing neural networks by mapping optimization algorithms into learnable architectures. Instead of treating optimization and deep learning as separate, this approach merges them, making networks interpretable and efficient.

Key topics covered:
- **Sparsity & Robustness:** Comparing estimators under different norms (L1, L2, L0).  
- **Sparse Contrastive Models:** Using sparse signal recovery with CLIP embeddings for interpretable zero-shot classification.  
- **ISTA & LISTA:** Implementing the Iterative Soft Thresholding Algorithm and unfolding it into a learnable neural network.  
- **Rank Constraints & Matrices:** Extending to images/videos via Robust PCA and low-rank + sparse decomposition.  
- **Mixed Norms:** Exploring (p, q)-norms for structured sparsity in unfolded neural networks.  

The repo demonstrates how optimization principles (like sparsity and low-rank structure) can be embedded into deep models for interpretability and performance improvements:contentReference[oaicite:0]{index=0}.

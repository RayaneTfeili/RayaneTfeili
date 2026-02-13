<h1 align="left">Rayane Tfeili</h1>
<p align="left"><b>Data & AI engineer</b> · <b>ML learner</b> · <b>Optimization × Transformers</b> · <b>Quant-curious</b></p>

<p align="left">
I work at the intersection of <b>modern deep learning</b> and <b>mathematical optimization</b>, with a growing focus on
<b>Transformers/LLMs</b> and <b>quantitative finance</b>. I enjoy building systems that are both <i>theoretically grounded</i>
and <i>practically deployable</i>.
</p>

---

## 🎓 Master thesis
<b>Convex Optimization Meets Attention: Mathematical Insights into Transformers and LLM</b>

My master thesis explores the mathematical foundations of modern deep learning with an emphasis on practical transformer architectures.
This work includes an implementation-from-scratch of a <b>convexified Transformer</b> model to study the effect of reformulated attention
mechanisms on model performance. The goal is to bridge theoretical optimization principles with practical deep learning architectures used
in modern AI systems.

### Thesis focus
- Attention mechanisms viewed through an <b>optimization lens</b> (reformulations, relaxations, constraints)
- A clean <b>from-scratch implementation</b> of a convexified Transformer variant
- Empirical study via <b>ablation</b>, <b>stability</b>, and <b>performance</b> metrics

---

## 🔭 What I’m working on now
- 🧠 Convexification of attention / LLMs (thesis)
- 🧩 RAG project: retrieval, reranking, evaluation, deployment-friendly pipelines
- 💹 Quant finance project: research/backtesting mindset + risk-aware metrics
- 🦀 Learning Rust (systems thinking, performance, safety)

---

## 🧠 Convex optimization view of attention (conceptual)
```mermaid
flowchart LR
  X[Inputs / tokens] --> E[Embeddings]
  E --> P[Positional encoding]
  P --> QKV[Q, K, V projections]
  QKV --> A[Attention: reformulated / convexified]
  A --> M[Mixing / aggregation]
  M --> FFN[Feed-forward block]
  FFN --> Y[Outputs]
  A -.->|analysis| O[Optimization view\n(convex constraints / relaxations)]

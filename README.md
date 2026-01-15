<div align="center">
  <h1>Survey on AI Memory: Theories, Taxonomies, Evaluations, and Emerging Trends</h1>

  <p align="center">
    <a href="https://arxiv.org/abs/2601.xxxxx">
      <img src="https://img.shields.io/badge/Arxiv-2601.xxxxx-red.svg" alt="Arxiv">
    </a>
    <a href="https://huggingface.co/papers/xxxx.xxxxx">
      <img src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Paper-black.svg" alt="Hugging Face">
    </a>
    <a href="https://github.com/BAI-LAB/Survey-on-AI-Memory/stargazers">
      <img src="https://img.shields.io/github/stars/BAI-LAB/Survey-on-AI-Memory.svg?color=green&label=Stars" alt="Stars">
    </a>
    <a href="https://github.com/BAI-LAB/Survey-on-AI-Memory/blob/main/LICENSE">
      <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License">
    </a>
  </p>
</div>

## 🌟 Abstract
Memory is a cornerstone of cognitive capability in AI systems. This survey provides a comprehensive overview of AI memory mechanisms anchored in a unified theoretical framework. We bridge **Cognitive Psychology** (e.g., Atkinson-Shiffrin, Working Memory, CLS) and **AI Architectures** to propose a structured **4W Memory Taxonomy**. Our work systematically analyzes memory processes in both **Single-Agent** and **Multi-Agent** systems while establishing a multidimensional evaluation framework.

---

## 🛠 The 4W Memory Taxonomy
The paper categorizes AI memory research through four critical dimensions:

* **When (Lifecycle):** * *Instantaneous:* Input buffers and transient states.
    * *Session:* Temporary storage within a specific context.
    * *Persistent:* Long-term storage across different sessions.
* **What (Information Type):** * *Procedural:* "How-to" skills and execution logic.
    * *Declarative:* "What-is" facts and semantic knowledge.
    * *Metacognitive:* Self-reflections and reasoning logs.
    * *Social & Personalized:* User profiles and interpersonal dynamics.
* **How (Storage Implementation):** * *Implicit:* Encoded in parametric weights or latent states.
    * *Explicit:* Stored as raw text, vector embeddings, or structured graphs.
* **Which (Modality):** * *Unimodal:* Text-centric memory.
    * *Multimodal:* Fusion of visual, audio, and sensor data.

---

## 🏗 Key Frameworks & Mechanisms

### 1. Interdisciplinary Design Patterns
* **Index and Content Separation:** Decoupling retrieval pointers from actual memory content.
* **Multiphase Consolidation:** Simulating the process of transforming short-term experiences into long-term knowledge.
* **Structured Coordination:** Managing dynamic information flow similar to the Working Memory Model.

### 2. Memory Processes
* **Basic Functions:** Analysis of *Storage*, *Retrieval*, and *Updating* (including Incremental, Corrective, and Consolidation).
* **Advanced Capabilities:** Focus on **Self-Evolution** (learning from history) and **Association** (cross-modal and temporal indexing).

### 3. Multi-Agent Memory (MAS)
* **Communication Mechanism:** Explicit (language-based) vs. Implicit (latent-based).
* **Sharing Paradigm:** Differentiating between **Task-Level** sharing (common knowledge) and **Step-Level** sharing (real-time coordination).

---

## 📊 Systematic Evaluation Taxonomy
The survey identifies four key dimensions for benchmarking AI memory:

| Dimension | Metrics & Focus |
| :--- | :--- |
| **Retrieval Capability** | Accuracy, Recall@k, NDCG, Ranking quality. |
| **Updating Capability** | Corrective updates, handling conflicting information. |
| **Advanced Cognition** | Generalization, Temporal perception, Personalization. |
| **System Efficiency** | Latency, Token consumption, Scalability. |

---

## 📝 Citation
If you find our research helpful, please cite

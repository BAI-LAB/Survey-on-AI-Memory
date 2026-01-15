<div align="center">
  <h1>Survey on AI Memory: Theories, Taxonomies, Evaluations, and Emerging Trends</h1>

  <p align="center">
    <a href="https://arxiv.org/abs/[Your_Arxiv_ID]">
      <img src="https://img.shields.io/badge/Arxiv-xxxx-red.svg" alt="Arxiv">
    </a>
    <a href="https://huggingface.co/papers/[Your_HF_ID]">
      <img src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-xxxx-black.svg" alt="Hugging Face">
    </a>
    <a href="https://github.com/BAI-LAB/Survey-on-AI-Memory/stargazers">
      <img src="https://img.shields.io/github/stars/BAI-LAB/Survey-on-AI-Memory.svg?color=green&label=Stars" alt="Stars">
    </a>
    <a href="https://github.com/BAI-LAB/Survey-on-AI-Memory/blob/main/LICENSE">
      <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License">
    </a>
  </p>
</div>

## 📢 News
* **[2026/01/15]** 🚀 Full survey released! [cite_start]We establish a unified framework for AI memory mechanisms[cite: 9, 120].
* **[2026/01/07]** 🚀 Please wait for our update......

---

## 🌟 Introduction

[cite_start]Memory is a cornerstone of cognitive capability in AI systems, empowering them with dynamic adaptation, complex reasoning, and experiential learning[cite: 5]. [cite_start]With the advent of LLM-driven agents, memory architectures have evolved from simple context windows to sophisticated systems that integrate parametric and non-parametric storage, fuse multimodal information, and facilitate knowledge sharing within multi-agent ecosystems[cite: 6].

[cite_start]This survey presents a comprehensive overview of AI memory mechanisms anchored in a unified theoretical framework, bridging cognitive theories with engineering benchmarks[cite: 9, 12].

### 🛠 The 4W Memory Taxonomy
[cite_start]We propose the structured **4W Memory Taxonomy** to enable consistent analysis across diverse architectures[cite: 10, 250]:
- [cite_start]**When (Lifecycle Dimension):** Focuses on temporal span, ranging from **Transient** (input buffers), **Session** (working memory), to **Persistent** (cross-session storage)[cite: 252, 253, 319].
- [cite_start]**What (Type Dimension):** Categorizes the nature of captured information, including **Procedural** (skills), **Declarative** (facts), **Metacognitive** (reflections), and **Social/Personalized** (user models)[cite: 255, 256, 363].
- [cite_start]**How (Storage Dimension):** Explores technical representation, including **Implicit** (Parametric/Latent within models) and **Explicit** (External Raw, Vector, or Graph-based storage)[cite: 257, 258, 401].
- [cite_start]**Which (Modality Dimension):** Classifies memory by information formats, distinguishing between **Single-modal** (text-only) and **Multimodal** (integrated image, audio, and video)[cite: 259, 261, 320].

---

## 🏗 Theoretical Foundations & Frameworks

### Interdisciplinary Foundations
[cite_start]We derive three essential architectural patterns for AI memory from cognitive psychology and neuroscience[cite: 131, 133, 155]:
* [cite_start]**Index and Content Separation:** Inspired by the Complementary Learning Systems (CLS) theory to enable efficient retrieval beyond context window limits[cite: 158, 193].
* [cite_start]**Multiphase Consolidation:** Transforming recent episodic traces into summaries and reusable skills for structured long-term memory[cite: 197, 198].
* [cite_start]**Structured Coordination:** Organizing active workspaces into specialized buffers overseen by a central controller[cite: 201, 202].

### Memory in Multi-Agent Systems (MAS)
[cite_start]Shared memory serves as the substrate for collective intelligence in MAS[cite: 673]:
* [cite_start]**Communication:** Ranging from **Explicit** (natural language/structured schemas) to **Implicit** (latent thoughts/compressed states)[cite: 597, 635, 663].
* [cite_start]**Sharing Mechanisms:** Optimized at **Task-Level** (experience accumulation across cycles) and **Step-Level** (dynamic context allocation within workflows)[cite: 598, 674].

---

## 📊 Evaluation Metrics
[cite_start]We establish a comprehensive taxonomy for standardized assessment of AI memory[cite: 704, 712]:

| Dimension | Representative Metrics | Description |
| :--- | :--- | :--- |
| **Retrieval Capability** | Recall@k, NDCG@k, Accuracy | [cite_start]Measures the quality and ranking of fetched memory segments[cite: 718, 721]. |
| **Updating Capability** | Update Accuracy, Hallucination Rate | [cite_start]Evaluates the ability to modify states and manage forgetting/unlearning[cite: 741, 751]. |
| **Advanced Cognition** | Success Rate, Kendall's r | [cite_start]Assesses generalization to unseen tasks and temporal perception[cite: 773, 776]. |
| **System Efficiency** | Latency, Token Overhead, Storage Cost | [cite_start]Examines engineering viability and operational overhead[cite: 797, 804]. |

---

## 📝 Citation

If you find this survey helpful, please cite our work

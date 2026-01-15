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

  <img src="images/Fig1.jpg" width="100%" alt="Survey Roadmap Overview">
  <p><em>Fig. 1. The Evolutionary Landscape of AI Memory: A Content Roadmap of the Survey.</em></p>
</div>

---

## 📢 News
* **[2026/01/15]** 🚀 Full survey released! We establish a unified framework for AI memory mechanisms.
* **[2026/01/07]** 🚀 Project repository initialized.

---

## 🌟 Introduction

This survey presents a comprehensive overview of AI memory
mechanisms anchored in a unified theoretical framework. We propose a structured "4W Memory Taxonomy" to enable consistent
analysis across diverse architectures. Building on this foundation, we systematically review memory systems in both single- and
multi-agent contexts, examining their architectures, functions, applications, and evaluation methodologies. By synthesizing cognitive
theories with engineering benchmarks, this work provides a coherent roadmap for advancing the theoretical understanding and
technological development of AI memory. 

### 🧩 Conceptual Boundaries
To clarify the scope of AI memory, we distinguish between three interrelated layers:
* [cite_start]**LLM Memory**: The low-level computational kernel for prediction, consisting of **Parametric Weights** (static) and **Context Window** (runtime)[cite: 210, 211].
* [cite_start]**Agent Memory**: The functional workflow supporting autonomous operation and complex task execution via perception-planning-action loops[cite: 213, 214].
* [cite_start]**AI Memory**: The overarching cognitive concept aimed at lifelong evolution, long-term persistence, and adaptation[cite: 219].

<div align="center">
  <img src="images/Fig2.png" width="80%" alt="AI Memory Boundaries">
  <p><em>Fig. 2. An AI Boundary to Clarify the Interrelationships Among LLM Memory, Agent Memory, and AI Memory.</em></p>
</div>

---

## 🛠 The 4W Memory Taxonomy

[cite_start]We establish a structured **4W Memory Taxonomy** to enable consistent analysis across diverse architectures[cite: 250]:

* [cite_start]**When (Lifecycle Dimension)**: Examines the temporal span of memory, including **Transient** (extremely short-lived), **Session** (task duration), and **Persistent** (cross-session retention)[cite: 253, 276, 281, 324].
* [cite_start]**What (Type Dimension)**: Categorizes by the nature of stored information, including **Procedural** (skills), **Declarative** (facts), **Metacognitive** (reflections), and **Social/Personalized** (user models)[cite: 256, 363].
* [cite_start]**How (Storage Dimension)**: Explores technical implementation, from **Implicit Storage** (Parametric/Latent) within model weights to **Explicit Storage** (Raw Text, Vector DB, or Structured Graphs) outside the model[cite: 258, 404, 418].
* [cite_start]**Which (Modality Dimension)**: Classifies by information formats, covering **Single-modal** (text-only) and **Multimodal** (fusing images, audio, and video)[cite: 259, 260, 261].

<div align="center">
  <img src="images/Fig3.jpg" width="100%" alt="4W Memory Taxonomy">
  <p><em>Fig. 3. 4W Memory Taxonomy for Systematic Classification of AI Memory Systems.</em></p>
</div>

---

## 🏗 Memory in Multi-Agent Systems (MAS)

[cite_start]Effective collaboration within MAS hinges on communication mediated by memory sharing[cite: 634]. We organize these mechanisms into two core dimensions:

* [cite_start]**Communication Mechanisms**: Ranges from **Explicit Communication** (interpretable symbols like natural language or structured schemas) to **Implicit Communication** (latent representations/hidden embeddings)[cite: 597].
* [cite_start]**Memory Sharing Mechanisms**: Categorized into **Task-Level** (experience accumulation and knowledge transfer) and **Step-Level** (precise context allocation and role-aware filtering)[cite: 598].

<div align="center">
  <img src="images/Fig4.jpg" width="100%" alt="MAS Memory Mechanisms">
  <p><em>Fig. 4. Framework Categorizing Memory Mechanisms in MAS into Communication Mechanisms and Memory Sharing Mechanisms.</em></p>
</div>

---

## 📊 Evaluation Taxonomy

[cite_start]We categorize memory evaluation into four essential dimensions to provide a structured assessment of agent memory[cite: 712]:

| Dimension | Description | Representative Metrics |
| :--- | :--- | :--- |
| **Retrieval Capability** | [cite_start]Evaluates the ability to fetch relevant memory segments[cite: 715, 716]. | [cite_start]Recall@k, Precision@k, NDCG@k [cite: 718, 721] |
| **Updating Capability** | [cite_start]Measures the ability to correctly modify, write, and forget information[cite: 737]. | [cite_start]Update Accuracy, Hallucination Rate, F1-score [cite: 741, 742, 749] |
| **Cognitive Capability** | [cite_start]Assesses higher-order reasoning such as generalization and temporal perception[cite: 769]. | [cite_start]Success Rate, Kendall's $r$, Accuracy [cite: 773, 777, 778] |
| **System Efficiency** | [cite_start]Evaluates engineering viability, including operational overhead[cite: 797]. | [cite_start]Latency, Token Overhead, Storage Cost [cite: 801, 804, 806] |

---

## 📝 Citation

If you find this survey or the established taxonomy helpful in your research, please cite our work

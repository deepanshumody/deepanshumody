# Hi, I'm Deepanshu 👋

### NYU MS Data Science '26

Ranking methodology, probability calibration, and evaluation design on messy real-world data.
On the systems side: real-time retrieval and ranking, multi-agent pipelines, and inference tuned
for latency and cost, grounded by research in LLM safety and tokenization.

📍 New York, NY  ·  🌐 [deepanshumody.com](https://deepanshumody.com)

---

## 🔧 What I work on

- **Applied modeling & experimentation** — Bradley-Terry ranking with bootstrap confidence intervals, probability calibration, survival/risk modeling, and evaluation design on imbalanced, out-of-distribution data.
- **ML systems & retrieval** — RAG, retrieval & ranking services, multi-agent pipelines, and real-time inference, built to hold accuracy under latency, cost, and safety constraints.
- **LLM safety & efficiency research** — refusal robustness, tokenizer optimization, interpretability, and evaluation harnesses.

## 🚀 Featured projects

| Project | What it is |
| --- | --- |
| **[discovery-agents](https://github.com/deepanshumody/discovery-agents)** | Multi-agent product-discovery pipeline — cluster evidence into insights, then generate, critique & score directions (LangGraph, guardrails, MCP) |
| **[increasing-refusal-intervention-robustness](https://github.com/deepanshumody/increasing-refusal-intervention-robustness)** | LLM-safety research — raised refusal attack-rank from K=1 → K≥16 |
| **[physiocoach](https://github.com/deepanshumody/physiocoach)** | Fully-local real-time VLM physical-therapy coach · Top-8/30, Dell × NVIDIA Hackathon |
| **[RNA-GNN](https://github.com/deepanshumody/RNA-GNN)** | GNNs for Mg²⁺ binding-site prediction in RNA 3D structures · +6.2pp ROC-AUC · [live demo](https://gnnrna.streamlit.app/) |
| **[PLM_interpretability](https://github.com/deepanshumody/PLM_interpretability)** | Sparse-autoencoder feature circuits in an ESM-2 protein LM · [interactive viewer](https://deepanshumody.github.io/PLM_interpretability/) |
| **[Analysis_RMP_Ratings](https://github.com/deepanshumody/Analysis_RMP_Ratings)** | Statistical analysis of 89,893 RateMyProfessor records · from-scratch ML, tested package + site |

## 📄 Selected research

- **Joint Optimization for Greedy Longest-match Tokenization (JOLT)** — Kensho/MIT EECS, advised by Dr. Craig Schmidt & Dr. Chris Tanner; *COLM 2026 Tokshop (accepted)*. Vocabulary selection as an integer program with greedy-consistency constraints; up to 0.78% fewer tokens than BPE, closing 89.6-99.4% of the remaining compression gap. [Preprint](https://arxiv.org/abs/2607.23362)
- **Robustness & Evaluation of Refusal in Open-Weight LLMs** — with Acey Vogelstein & Jonathan Merchan (NYU); preprint coming soon. Training-time defense raising the linear-ablation rank needed to break refusal from K=1 to K≥16, with baseline behavior preserved. [Explainer](https://deepanshumody.github.io/increasing-refusal-intervention-robustness/refusal-robustness-explainer.html) · [Code](https://github.com/deepanshumody/increasing-refusal-intervention-robustness)
- **World-Model Training & Forecasting for Robot Locomotion** — *CoRL 2026 (planned)*. Multimodal ROS2 dataset; DINOv2 / TD-JEPA encoders with GRU-RSSM dynamics; multi-horizon ADE/FDE evaluation.
- **Validity of ML-Based COVID-19 Prediction** — *PLOS ONE (2025)*. 7 models on 195k clinical records; quantified ~20% AUROC degradation under cross-continental shift + an open-source evaluation toolkit. [Paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0316467)

## 💼 Experience

**Living Brands AI** — Data Analyst Intern · **Pfizer** — Statistics & AI/ML Intern · **Incedo** — Data Scientist / SWE · **Kinara AI** (→ acquired by NXP) — SWE Intern

Evidence-grounded biomedical QA on AWS (LangGraph, six agents, ~18K-entity / ~95K-relationship knowledge graph), real-time retrieval & ranking (top-1 41% → 84%, 92.0 token-level F1), inference tuned across FP32→INT8 precision configurations, and a model-monitoring system (React/TypeScript on AWS, PostgreSQL) tracking confidence distributions, category drift, and failure modes.

## 🛠️ Tech

**Languages**&nbsp;&nbsp;Python · SQL · C++ · TypeScript
**ML / LLMs**&nbsp;&nbsp;PyTorch · QLoRA fine-tuning · post-training & KL distillation · RAG · retrieval & ranking · GNNs · model evaluation & safety · calibration · drift & OOD validation
**Infra & tools**&nbsp;&nbsp;AWS · Azure ML · PostgreSQL · Docker · FAISS · Neo4j · FastAPI · LangGraph · LangChain

## 🤝 Connect

[![Website](https://img.shields.io/badge/Website-deepanshumody.com-0a0b0d?style=flat-square)](https://deepanshumody.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-deepanshu--mody-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/deepanshu-mody-1202921b7/)
[![Email](https://img.shields.io/badge/Email-dm6262%40nyu.edu-2563eb?style=flat-square&logo=maildotru&logoColor=white)](mailto:dm6262@nyu.edu)

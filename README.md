# Hi, I'm Deepanshu 👋

### Applied Scientist · NLP, Retrieval & LLM Evaluation

I build retrieval, classification, and LLM evaluation systems.
I pair production ownership with rigorous experimentation, model validation, and research on model robustness and efficiency.
MS in Data Science at NYU ('26).

📍 New York, NY  ·  🌐 [deepanshumody.com](https://deepanshumody.com)

---

## 🔧 What I work on

- **Retrieval systems built for production** - hybrid retrieval, ranking, and multi-agent systems with traceable evidence, calibrated routing, and latency and cost measured against real constraints.
- **Evaluation that holds up on real data** - benchmarks, confidence thresholds, and out-of-domain checks that expose failure modes and make model quality useful for operational decisions.
- **Safer, more efficient language models** - research on refusal robustness, activation-level interpretability, and tokenizer optimization.

## 🚀 Featured projects

| Project | What it is |
| --- | --- |
| **[discovery-agents](https://github.com/deepanshumody/discovery-agents)** | Multi-agent product-discovery pipeline - cluster evidence into insights, then generate, critique & score directions (LangGraph, guardrails, MCP) |
| **[increasing-refusal-intervention-robustness](https://github.com/deepanshumody/increasing-refusal-intervention-robustness)** | LLM-safety research - raised refusal attack-rank from K=1 → K≥16 |
| **[physiocoach](https://github.com/deepanshumody/physiocoach)** | Fully-local real-time VLM physical-therapy coach · Top-8/30, Dell × NVIDIA Hackathon |
| **[RNA-GNN](https://github.com/deepanshumody/RNA-GNN)** | GNNs for Mg²⁺ binding-site prediction in RNA 3D structures · +6.2pp ROC-AUC · [live demo](https://gnnrna.streamlit.app/) |
| **[PLM_interpretability](https://github.com/deepanshumody/PLM_interpretability)** | Sparse-autoencoder feature circuits in an ESM-2 protein LM · [interactive viewer](https://deepanshumody.github.io/PLM_interpretability/) |
| **[Analysis_RMP_Ratings](https://github.com/deepanshumody/Analysis_RMP_Ratings)** | Statistical analysis of 89,893 RateMyProfessor records · from-scratch ML, tested package + site |

## 📄 Selected research

- **Joint Optimization for Greedy Longest-match Tokenization (JOLT)** - Kensho/MIT EECS, advised by Dr. Craig Schmidt & Dr. Chris Tanner; *COLM 2026 Tokshop (accepted)*. Vocabulary selection as an integer program with greedy-consistency constraints; up to 0.78% fewer tokens than BPE, closing 89.6-99.4% of the remaining compression gap. [Preprint](https://arxiv.org/abs/2607.23362)
- **Minimizing Targeted Activations: Input-Only Suppression of Evaluation-Awareness Latents in LLMs** - with Samarth Agarwal, Utkarsh Mittal & Dipesh Tharu Mahato (NYU); *arXiv preprint (2026)*. Fluent prompts that suppress five types of targeted internal features across two Llama families without changing model weights - with control experiments showing that readable activations do not always control behavior. [Preprint](https://arxiv.org/abs/2607.25907)
- **Robustness & Evaluation of Refusal in Open-Weight LLMs** - with Acey Vogelstein & Jonathan Merchan (NYU); *manuscript in preparation*. Training-time defense raising the linear-ablation rank needed to break refusal from K=1 to K≥16, with baseline behavior preserved. [Explainer](https://deepanshumody.github.io/increasing-refusal-intervention-robustness/refusal-robustness-explainer.html) · [Code](https://github.com/deepanshumody/increasing-refusal-intervention-robustness)
- **World-Model Training & Forecasting for Robot Locomotion** - *manuscript in preparation*. Multimodal ROS2 dataset from aligned camera, depth, IMU, odometry, and action streams; three visual encoders benchmarked with recurrent world-model dynamics; forecasts evaluated at 1.6 / 3.2 / 5.0 s horizons.
- **Validity of ML-Based COVID-19 Prediction** - *PLOS ONE (2025)*. 7 models on 195k clinical records; quantified ~20% AUROC degradation under cross-continental shift + an open-source evaluation toolkit. [Paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0316467)

## 💼 Experience

**Living Brands AI** - Data Analyst Intern · **Pfizer** - Statistics & AI/ML Intern · **Incedo** - Data Scientist · **Kinara AI** (→ acquired by NXP) - SWE Intern

Highlights: a production platform benchmarking brand prominence across six LLMs and 10,000+ weekly prompts, processing ~1M responses at ~93% intent accuracy.
An AWS oncology knowledge graph (~18K entities, ~95K evidence-weighted relationships in Neo4j) with eight retrieval tools returning auditable evidence paths.
Hybrid BM25 + dense retrieval with cross-encoder reranking over 1,200+ technical manuals: top-1 exact match 41% → 84%, answer F1 68% → 92%, p95 latency 2.3 s → 900 ms.
A RISC-V vector-extension and LLVM-backend prototype accelerating ML kernels.

## 🛠️ Tech

**Languages**&nbsp;&nbsp;Python · SQL · C++ · TypeScript  
**ML & Data Science**&nbsp;&nbsp;PyTorch · scikit-learn · NLP · LLM fine-tuning · retrieval & ranking · calibration & OOD validation · feature engineering  
**Optimization & Evaluation**&nbsp;&nbsp;Gurobi · mixed-integer programming · experiment design · model validation · safety evaluation  
**Infra & tools**&nbsp;&nbsp;AWS · Azure ML · PostgreSQL · Docker · FAISS · Neo4j · FastAPI · data pipelines & ETL

## 🤝 Connect

[![Website](https://img.shields.io/badge/Website-deepanshumody.com-0a0b0d?style=flat-square)](https://deepanshumody.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-deepanshu--mody-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/deepanshu-mody-1202921b7/)
[![Email](https://img.shields.io/badge/Email-dm6262%40nyu.edu-2563eb?style=flat-square&logo=maildotru&logoColor=white)](mailto:dm6262@nyu.edu)

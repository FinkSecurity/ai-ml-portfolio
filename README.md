# ML for Cybersecurity

A hands-on, follow-along curriculum for building machine learning models applied to real cybersecurity problems — from scratch, using Jupyter notebooks.

No prior ML experience needed. Every module builds on the last.

---

## Who This Is For

Security professionals, students, or anyone curious about how ML is applied in the cybersecurity space. The goal is to build practical intuition for how models work by training them on real security data — malware samples, network traffic, log data, and more.

---

## Curriculum

| Module | Topic | Cybersecurity Application | Status |
|--------|-------|--------------------------|--------|
| [01 - ML Fundamentals](01-ml-fundamentals/) | Supervised & Unsupervised Learning | Malware Classification, Anomaly Detection | 🔄 In Progress |
| [02 - Deep Learning](02-deep-learning/) | Neural Networks, CNNs, RNNs | Intrusion Detection, Log Analysis | 🔜 Coming Soon |
| [03 - NLP & LLMs](03-nlp-and-llms/) | Transformers, Claude API, RAG | Threat Intel Summarization, Phishing Detection | 🔜 Coming Soon |
| [04 - Local Models](04-local-models/) | Ollama, Quantization, Agents | On-Prem AI for Security Tools | 🔜 Coming Soon |
| [05 - Multimodal](05-multimodal/) | Vision + Language, Audio | Screenshot Analysis, Alert Triage | 🔜 Coming Soon |
| [06 - Capstone](06-capstone/) | End-to-End Pipeline | AI Security Assistant | 🔜 Coming Soon |

---

## Stack

- **Language:** Python 3
- **Notebooks:** Jupyter
- **ML:** scikit-learn → PyTorch
- **LLMs:** Claude API, Ollama
- **Data:** Public security datasets (Kaggle, CICIDS, VirusTotal, etc.)

---

## How to Follow Along

Each module has its own README with context, setup, and instructions. Start at Module 01 and work forward — concepts carry over.

**Prerequisites:**
- Python 3.8+
- Jupyter installed (`pip install jupyter`)
- Basic Python familiarity (loops, functions, lists)

```bash
git clone https://github.com/FinkSecurity/ml-for-cybersecurity.git
cd ml-for-cybersecurity
pip install jupyter
jupyter notebook
```

Open the notebook for the module you're on and run cells top to bottom.

---

## Why Cybersecurity + ML?

Attackers already use ML. Defenders should too. This repo is about building that fluency — not using off-the-shelf tools, but understanding how the models underneath them actually work.

---

*Built by a security professional learning ML in public. Questions or contributions welcome.*

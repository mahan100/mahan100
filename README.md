<h1 align="center">Mehdi Mohseni Mahani</h1>

<p align="center">
  <b>Deep Learning Researcher · Time-Series Transformers · LLM Infrastructure</b><br>
  PhD student in Artificial Intelligence, Shahid Bahonar University of Kerman
</p>

---

## About

I work on **sequence models for time series** — transformer architectures, recurrent and hybrid recurrent–attention designs, and the training pipelines that make them reproducible. Most of my public code is experimentation around a single question: *how much structure can a model exploit before the data stops supporting it?*

Alongside research I build and operate the infrastructure around models: PyTorch training loops, experiment tracking, containerised serving, and the evaluation and observability layer that LLM systems need before they can be trusted.

- 🔬 **Research:** time-series transformers, attention variants, hybrid LSTM/attention models, decomposition-based forecasting
- ⚙️ **Engineering:** PyTorch, TensorFlow, reproducible training pipelines, Optuna/Darts hyper-parameter search
- 🚀 **LLM systems:** serving and optimisation (SGLang, TensorRT-LLM, TorchServe), RAG, evaluation (DeepEval, RAGAS), tracing (LangSmith, Langfuse)
- 📊 **MLOps:** Docker, MLflow, experiment tracking, model packaging and deployment

---

## Research themes

| Theme | What I explore |
| :--- | :--- |
| **Transformer variants for time series** | Patch/token design, attention sparsity, parity- and frequency-aware blocks, cross-head and gated attention |
| **Hybrid recurrent models** | LSTM + attention hybrids, decomposed inputs (VMD), long-horizon regression |
| **Forecasting benchmarks** | Multi-horizon regression on financial and sensor-like series, ablation-driven comparison |
| **LLM infrastructure** | Serving throughput and KV-cache behaviour, retrieval pipelines, evaluation harnesses |

---

## Toolbox

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white">
  <img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white">
</p>
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white">
</p>
<p>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square">
  <img src="https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square">
  <img src="https://img.shields.io/badge/RAG-4B8BBE?style=flat-square">
  <img src="https://img.shields.io/badge/SGLang-2F4858?style=flat-square">
  <img src="https://img.shields.io/badge/TensorRT--LLM-76B900?style=flat-square&logo=nvidia&logoColor=white">
  <img src="https://img.shields.io/badge/TorchServe-EE4C2C?style=flat-square">
</p>

---

## Currently

- Finishing coursework and early experiments for the PhD, focused on attention design for long-horizon forecasting.
- Reading and re-implementing recent time-series foundation-model papers to see which ideas survive an honest ablation.
- Building small, end-to-end LLM services — retrieval, serving, evaluation — as a way to keep the infrastructure side honest.

## Open to

Research collaboration on time-series representation learning, and applied work where forecasting or LLM systems have to run in production rather than in a notebook. If something here overlaps with what you are building, open an issue or reach out on LinkedIn.

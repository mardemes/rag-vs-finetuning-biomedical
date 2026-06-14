# RAG vs. Fine-Tuning in Biomedical LLMs: Factual Accuracy vs. Latency Trade-Off

This repository contains the source code, experimental notebooks, and benchmarks evaluated in our paper accepted at **KDMiLe 2026** (Symposium on Knowledge Discovery, Mining and Learning). 

The project presents a rigorous empirical investigation into the operational and qualitative trade-offs between parametric knowledge retrieval via **Parameter-Efficient Fine-Tuning (PEFT/QLoRA)** and non-parametric context injection through **Retrieval-Augmented Generation (RAG)**. Using an open-source **Llama-3 8B** architecture tested against the clinical gold-standard **PubMedQA** dataset, we map how context expansion minimizes hallucinations at the cost of quadratic attention overhead on infrastructure hardware (Nvidia A100 GPU).

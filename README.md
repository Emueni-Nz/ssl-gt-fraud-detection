# SSL-GT Fraud Detection — MSc Research

**Title:** A Self-Supervised Graph-Temporal Model for Fraud Detection in Digital Bank Account Opening  
**Author:** Esther Mueni Nzau | C004/600171/2024  
**Institution:** The Cooperative University of Kenya  

## Research Objectives
1. Analyze BAF dataset variables for heterogeneous graph construction
2. Develop SSL-GT model integrating Graph Contrastive Learning & Temporal Transformer
3. Evaluate detection accuracy under class imbalance and label latency
4. Compare SSL-GT against supervised and self-supervised baselines

## Dataset
NeurIPS 2022 Bank Account Fraud (BAF) Dataset

## Environment
- Google Colab (GPU: T4)
- Python 3.10+

## Notebook Structure
| Notebook | Description |
|----------|-------------|
| 01_univariate_analysis | Class imbalance, per-variable distributions |
| 02_bivariate_analysis | Shared identifiers, velocity patterns |
| 03_multivariate_analysis | Correlations, PCA, fraud clusters |
| 04_graph_design | NetworkX edge justification |

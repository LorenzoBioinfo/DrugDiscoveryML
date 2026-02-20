# 💊 Drug Discovery with Machine Learning

A comprehensive repository covering the application of machine learning, deep learning, and AI techniques to modern drug discovery pipelines — from molecular filtering to generative design.

> **Acknowledgment**: The foundational ideas, methodologies, and some datasets in this repository are inspired by and derived from *Machine Learning for Drug Discovery* by **Noah Flynn** and its companion repository. Several sections have been modified, extended, and expanded upon.

---

## 📚 Contents

### 1. The Drug Discovery Process
Introduction to the drug discovery pipeline: target identification, hit discovery, lead optimization, and clinical development. Overview of the computational approaches used at each stage and why machine learning is transforming the field.

---

### 2. Ligand-based Screening: Filtering & Similarity Searching
Core concepts in ligand-based virtual screening. Molecular representations and fingerprints (ECFP, MACCS keys, topological). Physicochemical property filtering (Lipinski's Rule of Five, ADMET). Tanimoto similarity and nearest-neighbor searching across compound libraries.

---

### 3. Ligand-based Screening: Machine Learning
Supervised learning applied to virtual screening. Feature engineering from molecular fingerprints. Binary classification models to predict bioactivity. Model evaluation strategies specific to imbalanced chemical datasets.

---

### 4. Solubility Deep Dive with Linear Models
Predicting aqueous solubility (logS) as a regression task. Linear models (Ridge, Lasso, ElasticNet) and their regularization tradeoffs. Feature importance and interpretability in the context of molecular descriptors.

---

### 5. Classification: Cytochrome P450 Inhibition
Multi-target classification for CYP450 isoform inhibition prediction. Handling multi-label problems in ADMET profiling. Comparison of classical classifiers and analysis of class imbalance strategies.

---

### 6. Case Study: Small Molecule Binding to an RNA Target
End-to-end case study targeting a non-traditional biological target. Molecular docking concepts, binding affinity estimation, and integration of structure-based information into ligand-based models.

---

### 7. Unsupervised Learning: Repurposing Drugs, Curating Compounds & Screening Fragments
Dimensionality reduction techniques: PCA, UMAP, t-SNE applied to chemical space visualization. Clustering algorithms for compound library curation and diversity analysis. Drug repurposing through chemical space mapping. Fragment-based screening and scaffold analysis.

---

### 8. Introduction to Deep Learning
Fundamentals of neural networks for molecular property prediction. Feedforward networks, activation functions, regularization, and optimization. Comparison with classical ML approaches on benchmark ADMET tasks.

---

### 9. Structure-based Drug Design with Active Learning
Integration of molecular docking into machine learning workflows. Active learning strategies to iteratively improve predictive models with minimal experimental cost. Uncertainty quantification and acquisition functions for compound prioritization.

---

### 10. Generative Models for De Novo Design
Generative approaches to designing novel molecules from scratch. Variational Autoencoders (VAEs) and Generative Adversarial Networks (GANs) in chemical space. SMILES-based and latent space generation with property optimization.

---

### 11. Graph Neural Networks for Predicting Drug-Target Affinity
Molecular graphs as input to GNNs. Message passing neural networks (MPNN) for learning atomic and bond-level representations. Predicting binding affinity (Ki, Kd, IC50) directly from molecular structure.

---

### 12. Transformers for Protein Structure Prediction
Attention mechanisms and transformer architectures applied to biological sequences. Overview of protein language models and structure prediction (AlphaFold paradigm). Applications to target characterization and binding site identification.

---

### 13. Multimodal AI Systems
Integration of heterogeneous data modalities: molecular graphs, protein sequences, 3D structures, gene expression, and clinical data. Multimodal architectures for drug-target interaction prediction and holistic ADMET modeling.

---

## 🛠️ Tech Stack

- **Cheminformatics**: RDKit, DeepChem
- **Machine Learning**: scikit-learn
- **Deep Learning**: PyTorch, PyTorch Geometric
- **Data**: pandas, numpy
- **Visualization**: matplotlib, seaborn

---

## ⚠️ Credits & Attribution

The core conceptual framework, several methodologies, and portions of the data used throughout this repository are based on the work of **Noah Flynn** — *Machine Learning for Drug Discovery* (book and repository).  
This repository represents a personal reworking, extension, and expansion of those ideas for educational and research purposes.  
All original credit for foundational concepts goes to the respective author.

---


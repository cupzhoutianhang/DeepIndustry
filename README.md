# AMP: Amine Molecule Prediction

![Logo](logo.png)

![Linux Test](https://img.shields.io/badge/Code%20tests%20Linux-passing-brightgreen?logo=github)
![Windows Test](https://img.shields.io/badge/Code%20tests%20Windows%20%28uv%2Fpip%29-passing-brightgreen?logo=github)
![macOS Test](https://img.shields.io/badge/Code%20tests%20macOS-passing-brightgreen?logo=github)

---

**AMP (Amine Molecule Prediction)** is an open-source platform that combines machine learning, cheminformatics, and symbolic reasoning to predict the structure, properties, and reactivity of amine-based molecules. Designed for research in molecular design, drug discovery, and materials chemistry, AMP provides interpretable and reproducible predictions with built-in reasoning chains.

Whether you're building predictive pipelines, screening molecular libraries, or exploring structure–activity relationships (SAR), AMP helps you move from data to insight with clarity and control.

---

## 🌟 Key Highlights

- 🧠 **Reasoning Chain Framework**  
  Every prediction is backed by a logic-driven explanation, improving interpretability and trust.

- ⚗️ **Amine-Focused Architecture**  
  Tailored for molecules containing –NH₂, –NHR, –NR₂ groups across primary, secondary, and tertiary amines.

- 📈 **Molecular Property Prediction**  
  Predicts boiling point, reactivity, bioactivity, solubility, or custom-trained targets.

- 🔍 **Explainable AI**  
  Built-in tools to visualize decision flow, feature contributions, and molecular fragments.

---

## 📦 Installation

### 1. Requirements

- Python 3.8+
- [RDKit](https://www.rdkit.org/)
- NumPy, Pandas, Scikit-learn
- PyTorch or TensorFlow (optional, depending on model backend)

### 2. Install AMP

```bash
git clone https://github.com/your-username/AMP.git
cd AMP
pip install -r requirements.txt

# 🧬 Generative AI for Science

<p align="center">
  <img src="book_cover.png" alt="Generative AI for Science Book Cover" width="300"/>
</p>

<p align="center">
  <a href="https://leanpub.com/generativeaiforscience"><img src="https://img.shields.io/badge/Leanpub-Purchase%20Book-yellow?style=for-the-badge&logo=leanpub" alt="Leanpub"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python" alt="Python"/></a>
  <a href="#"><img src="https://img.shields.io/badge/PyTorch-2.0+-red?style=for-the-badge&logo=pytorch" alt="PyTorch"/></a>
  <a href="#"><img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License"/></a>
</p>

<p align="center">
  <strong>A Hands-On Guide to Transformers, Diffusion Models, and AI-Driven Discovery</strong>
</p>

<p align="center">
  <em>By Dr. J. Paul Liu</em>
  <br> https://leanpub.com/generativeaiforscience
</p>

---

## 📖 About This Book

**Generative AI for Science** is a comprehensive, hands-on guide for researchers, students, and practitioners who want to apply cutting-edge AI techniques to scientific discovery. This book bridges the gap between AI/ML expertise and domain science, providing practical implementations across chemistry, biology, physics, geoscience, and beyond.

> *"Generative AI does not replace the scientific method—it enhances it. It expands the space of hypotheses we can explore, sharpens experimental design, and reveals patterns hidden in complexity."*

### ✨ What Makes This Book Different

| Feature | Description |
|---------|-------------|
| 🔬 **Theory Meets Practice** | Every concept is paired with ready-to-run code |
| 💻 **Interactive Learning** | All examples provided as Google Colab notebooks—no installation required |
| 🧪 **Real Scientific Problems** | Examples from authentic research across multiple domains |
| 📊 **Accessible Yet Rigorous** | Suitable for domain scientists exploring AI and ML experts entering scientific applications |

---

## 🎯 What You Will Learn

By the end of this book, you will:

- ✅ Understand key AI architectures: **Transformers**, **Diffusion Models**, **VAEs**, and **GNNs**
- ✅ Represent scientific data types effectively for AI models
- ✅ Apply generative models to problems in **climate science**, **drug discovery**, **genomics**, **materials science**, and more
- ✅ Follow best practices around **ethics**, **reproducibility**, and **deployment**
- ✅ Stay current with emerging methods and future directions
- ✅ Develop the intuition to know *when* and *how* to apply AI to scientific research

---

## 📚 Table of Contents

### Part I: Foundations

| Chapter | Title | Topics |
|---------|-------|--------|
| 1 | **Generative AI: A New Frontier for Scientific Discovery** | AI revolution in science, core technologies, cross-cutting capabilities |
| 2 | **Generative AI Fundamentals** | Transformers, LLMs, Diffusion Models, VAEs, GANs, attention mechanisms |
| 3 | **Scientific Data & Workflows** | Data challenges, FAIR principles, data preparation, workflow automation |
| 4 | **Text, Code & Knowledge Generation** | Literature synthesis, RAG, hypothesis generation, code generation, scientific writing |

### Part II: Core Techniques

| Chapter | Title | Topics |
|---------|-------|--------|
| 5 | **Data-to-Data Models** | Missing data imputation, synthetic data with GANs, VAEs, Gaussian processes, time series |
| 6 | **Physics-Informed AI and Simulation** | PINNs, neural surrogates, code optimization, automated testing |

### Part III: Domain Applications

| Chapter | Title | Topics |
|---------|-------|--------|
| 7 | **Domain Applications** | Chemistry & Materials, Biology & Biomedicine, Physics & Engineering, Geoscience & Climate |

**Part I: Chemistry & Materials Science**
- Molecular Graph Learning (GNNs)
- Molecular Generation with Diffusion Models
- Crystal Structure Prediction
- Reaction Outcome Prediction with Transformers

**Part II: Biology & Biomedicine**
- Protein Structure Prediction (ESMFold, AlphaFold2)
- Protein Sequence Generation (ProteinMPNN, RFDiffusion)
- Genomic Variant Analysis
- Clinical Trial Optimization

**Part III: Physics & Engineering**
- Particle Physics Applications
- Quantum Systems
- Materials Characterization

**Part IV: Geoscience & Climate**
- Ocean Forecasting
- Hurricane Prediction
- Climate Modeling
- Weather AI (GenCast, Aurora)

**Part V: Cross-Cutting Applications**
- Transfer Learning
- Multi-task Learning
- Foundation Models

### Part IV: Production & Best Practices

| Chapter | Title | Topics |
|---------|-------|--------|
| 8 | **Fine-Tuning & Domain Adaptation** | LoRA, PEFT, domain-specific training, evaluation strategies |
| 9 | **Multimodal Generative AI** | Vision-language models, graph-text models, multimodal fusion |
| 10 | **Evaluation, Validation & Benchmarking** | Metrics, validation strategies, uncertainty quantification, robustness testing |
| 11 | **Ethics & Responsible AI** | Reproducibility, bias & fairness, environmental impact, dual-use, data privacy |
| 12 | **Deployment & MLOps** | Experiment tracking, data versioning, model lifecycle, continuous training |
| 13 | **Future Directions & Conclusion** | Emerging architectures, foundation models, AI reasoning, open challenges |

---

## 🚀 Getting Started

### Prerequisites

- **Python programming**: Functions, loops, data structures
- **Statistics**: Distributions, hypothesis testing (undergraduate level)
- **Scientific computing**: NumPy, Matplotlib (helpful but not required)
- **No prior deep learning experience necessary**

### Technical Requirements

```
✅ A web browser
✅ Curiosity
Everything else runs in the cloud!
```

### Quick Start

1. **Get the 500-page book**
   [https://leanpub.com/generativeaiforscience](https://leanpub.com/generativeaiforscience)
   
2.   **Clone this repository**
```bash
git clone https://github.com/jpliu168/Generative_AI_For_Science.git
cd Generative_AI_For_Science
```

3. **Open any notebook in Google Colab**
   - Click the "Open in Colab" badge in each notebook
   - Or upload directly to [colab.research.google.com](https://colab.research.google.com)

4. **Read a chapter and Run the code**
   - Each notebook is self-contained with all dependencies
   - GPU runtime recommended for deep learning examples

---

## 📂 Repository Structure

```
Generative_AI_For_Science/
├── 📁 Chapter01_Introduction/
│   └── 📓 Ch01_AI_Scientific_Discovery.ipynb
├── 📁 Chapter02_Fundamentals/
│   ├── 📓 Ch02_Transformers.ipynb
│   ├── 📓 Ch02_Diffusion_Models.ipynb
│   └── 📓 Ch02_VAEs_GANs.ipynb
├── 📁 Chapter03_Data_Workflows/
│   └── 📓 Ch03_Scientific_Data.ipynb
├── 📁 Chapter04_Text_Code_Knowledge/
│   ├── 📓 Ch04_RAG_Literature.ipynb
│   └── 📓 Ch04_Code_Generation.ipynb
├── 📁 Chapter05_Data_to_Data/
│   ├── 📓 Ch05_Autoencoders.ipynb
│   ├── 📓 Ch05_GANs.ipynb
│   ├── 📓 Ch05_VAEs.ipynb
│   └── 📓 Ch05_Time_Series.ipynb
├── 📁 Chapter06_Physics_Informed/
│   ├── 📓 Ch06_PINNs.ipynb
│   └── 📓 Ch06_Neural_Surrogates.ipynb
├── 📁 Chapter07_Domain_Applications/
│   ├── 📓 Ch07_Chemistry_GNNs.ipynb
│   ├── 📓 Ch07_Molecular_Diffusion.ipynb
│   ├── 📓 Ch07_Protein_Structure.ipynb
│   ├── 📓 Ch07_Genomics.ipynb
│   └── 📓 Ch07_Climate_AI.ipynb
├── 📁 Chapter08_FineTuning/
│   └── 📓 Ch08_LoRA_PEFT.ipynb
├── 📁 Chapter09_Multimodal/
│   └── 📓 Ch09_Vision_Language.ipynb
├── 📁 Chapter10_Evaluation/
│   └── 📓 Ch10_Metrics_Validation.ipynb
├── 📁 Chapter11_Ethics/
│   └── 📓 Ch11_Responsible_AI.ipynb
├── 📁 Chapter12_Deployment/
│   └── 📓 Ch12_MLOps.ipynb
├── 📁 slides/
│   └── 📊 PowerPoint slides for each chapter
├── 📁 assets/
│   └── 🖼️ Figures and images
└── 📄 README.md
```

---

## 💡 How to Use This Book

| Use Case | Recommendation |
|----------|----------------|
| 📖 **As a course text** | Follow chapters sequentially for structured introduction |
| 🔍 **As a reference** | Jump directly to sections relevant to your research domain |
| 💻 **As a hands-on guide** | Open Colab notebooks alongside each chapter, run and modify code |
| 🚀 **As a research launchpad** | Use provided implementations as starting points for your projects |

---

## 🔬 Featured Applications

### 🧪 Chemistry & Materials
- **Molecular Property Prediction** with Graph Neural Networks
- **Drug Design** with Diffusion Models
- **Crystal Structure Prediction** with AI
- **Reaction Prediction** with Transformers

### 🧬 Biology & Biomedicine
- **Protein Structure Prediction** (ESMFold, AlphaFold2)
- **Protein Design** (ProteinMPNN, RFDiffusion)
- **Variant Effect Prediction** for genomics
- **Clinical Trial Optimization**

### 🌍 Geoscience & Climate
- **Weather Forecasting** with GenCast
- **Ocean Dynamics** modeling
- **Climate Projection** with surrogates
- **Extreme Event Prediction**

### ⚛️ Physics & Engineering
- **Physics-Informed Neural Networks** (PINNs)
- **Neural Network Surrogates** for simulations
- **Uncertainty Quantification**

---

## 📊 Key Technologies Covered

| Architecture | Use Cases | Scientific Applications |
|--------------|-----------|------------------------|
| **Transformers & LLMs** | Text, code, sequences | Literature synthesis, protein sequences, code generation |
| **Diffusion Models** | Structured outputs, images | Molecular structures, protein folding, climate data |
| **VAEs & GANs** | Latent space learning | Synthetic data, anomaly detection, compression |
| **Graph Neural Networks** | Molecular graphs | Property prediction, reaction prediction |
| **Physics-Informed NNs** | PDEs, conservation laws | Fluid dynamics, heat transfer, wave propagation |

---

## 🛠️ Installation (Optional Local Setup)

While all notebooks run in Google Colab, you can also set up locally:

```bash
# Create virtual environment
python -m venv genai-science
source genai-science/bin/activate  # Linux/Mac
# or: genai-science\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt
```

### Core Dependencies

```
torch>=2.0
transformers>=4.30
rdkit
numpy
pandas
matplotlib
scikit-learn
```

---

## 📈 Computational Requirements

| Model Type | GPU Memory | Recommended Platform |
|------------|------------|---------------------|
| Small models (GNNs, VAEs) | < 4 GB | Colab Free Tier |
| Medium models (Diffusion) | 4-8 GB | Colab Pro |
| Large models (LLMs, ESMFold) | 16+ GB | Colab Pro+, A100 |

---

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### Ways to Contribute
- 🐛 Report bugs or issues
- 💡 Suggest new examples or applications
- 📝 Improve documentation
- 🔧 Submit code improvements
- 🌍 Translate content

---

## 📜 Citation

If you use this book or code in your research, please cite:

```bibtex
@book{liu2026generativeai,
  title     = {Generative AI for Science},
  author    = {Liu, J. Paul},
  year      = {2026},
  publisher = {Leanpub},
  url       = {https://leanpub.com/generativeaiforscience}
}
```

---

## 📬 Contact & Community

- 📧 **Email**: [Contact through Leanpub] (https://leanpub.com/generativeaiforscience)  
- 🐦 **Twitter / X**: Follow for updates  
- 💼 **LinkedIn**: Connect for professional updates  
- 💬 **Discussions**: Use GitHub Discussions for Q&A  
- 🐛 **Issues**: Report bugs via GitHub Issues

## Update Note
- This book will be updated regularly based on feedback from students and users.
---

## 🙏 Acknowledgements

This book was developed through:
- Graduate courses at the Data Science and AI Academy
- Bioinformatics Research Center workshops
- Cross-campus AI for Research training programs
- Research Triangle AI Society–LLM intensive bootcamps
- Collaborations in oceanography, materials science, protein engineering, and literature mining

Special thanks to all students and colleagues who provided feedback and helped refine the material.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

The book content is © 2026 J. Paul Liu. Code examples are provided under MIT License for educational use.

---

## ⭐ Star History

If you find this resource helpful, please consider giving it a star! ⭐

---

<p align="center">
  <strong>🚀 Ready to accelerate your scientific discovery with AI?</strong>
  <br><br>
  <a href="https://leanpub.com/generativeaiforscience">
    <img src="https://img.shields.io/badge/Get%20the%20Book-Leanpub-yellow?style=for-the-badge&logo=leanpub" alt="Get the Book"/>
  </a>
</p>

---

<p align="center">
  <em>"Combine human creativity with machine assistance, and new discoveries become possible."</em>
  <br>
  — Dr. J. Paul Liu
</p>

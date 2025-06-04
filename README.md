# 🌿 PlantCLEF 2025 - Multi-Species Plant Identification

## 📝 Overview

This repository contains my solution for the **PlantCLEF 2025** challenge hosted as part of **LifeCLEF 2025** and the **CVPR-FGVC workshop**. The task involves **multi-species plant identification** in **high-resolution vegetation quadrat images**.

A quadrat is a rectangular frame placed on the ground to define a fixed area for ecological sampling. Each image may contain **multiple plant species**, making this a **multi-label classification** problem with **fine-grained visual recognition** challenges and **environmental variability** (e.g., different lighting, angles, growth stages).

---

## 🔍 Objective

- Identify all plant species present in each image.
- Learn robust representations for fine-grained, multi-label classification.
- Explore hierarchical taxonomies and model uncertainty in species prediction.

---

## 📂 Contents

- `plantclef2025_solution.ipynb` – Detailed step-by-step notebook including:
  - Data preprocessing
  - Patch extraction and resizing
  - Feature extraction using ViT-based models
  - Multi-label prediction pipeline
  - Evaluation metrics
- `submission.csv` – Final prediction file submitted to the challenge.

---

## 🧪 Scores

| Split        | Score    |
|--------------|----------|
| Public Score | 0.23680  |
| Private Score| 0.21712  |

---

## 🛠️ Tools & Technologies

- Python, NumPy, Pandas
- PyTorch / TorchVision / Timm
- Vision Transformer (`vit_base_patch14_reg4_dinov2`)
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## 🏆 Competition Credits

This work is based on the **PlantCLEF 2025 Challenge**, part of the **LifeCLEF 2025 Lab** under the **CLEF Initiative** and associated with the **FGVC workshop @ CVPR**.

**Organizers & Host Institutions:**
- LifeCLEF & CLEF Initiative
- FGVC (Fine-Grained Visual Categorization) Workshop
- CIRAD, Inria, Tela Botanica, and other partners

Competition details and dataset are hosted on:  
👉 [https://www.imageclef.org/LifeCLEF/2025/Plant](https://www.imageclef.org/LifeCLEF/2025/Plant)

---

## 📊 Dataset

The dataset was provided by the organizers and hosted via **Kaggle**:  
👉 [Kaggle PlantCLEF 2025 Dataset](https://www.kaggle.com/competitions/plantclef2025)

All data used is for academic/research purposes as allowed by the challenge terms.

---

## 🤝 Acknowledgements

- **Kaggle** for competition hosting and baseline notebooks.
- **Timm** library for access to pretrained ViT models.
- **PlantCLEF 2025 organizers** for designing a challenging and impactful ecological problem.
- Resources and community discussion on [Kaggle forums](https://www.kaggle.com/competitions/plantclef2025/discussion) were invaluable.

---

## 🔗 Links

- 📘 [My LinkedIn](www.linkedin.com/in/ubaid-ur-rehman-422212177)  
- 🔬 [More about the LifeCLEF Challenges](https://www.imageclef.org/LifeCLEF2025)

---

## 📜 License

This repository is shared for **educational and research purposes**. Please cite appropriately if reusing content or code.


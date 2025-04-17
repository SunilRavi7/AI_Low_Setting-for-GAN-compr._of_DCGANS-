# 🧠 DCGAN vs Conditional GAN – A Comparative Study in Low-Resource Settings

> 🚀 Developed by **Sunil R** (sunilr31r@gmail.com)  
> 📍 Focused on healthcare-related synthetic data generation using GANs

This project showcases a **comparative analysis between DCGAN and Conditional GAN** models, optimized for **low-resource environments**, with a key focus on **healthcare applications**. It uses visualizations like loss curves, radar charts, and dimensionality reductions to prove Conditional GAN's superiority in generating synthetic, privacy-preserving medical data.

![Banner](results/banner.png)

---

## 📌 Table of Contents

- [🧠 Project Overview](#-project-overview)
- [❤️ Healthcare Applications](#️-healthcare-applications)
- [📊 Results & Visualizations](#-results--visualizations)
- [💻 Installation & Running](#-installation--running)
- [🌐 Clone This Project](#-clone-this-project)
- [👤 Author & Contact](#-author--contact)
- [📜 License](#-license)

---

## 🧠 Project Overview

This repo provides:

✅ Implementation of **DCGAN** and **Conditional GAN**  
📉 Side-by-side visual evaluation of both models  
📊 Includes **loss graphs**, **radar performance**, **PCA**, **t-SNE**, and **heatmaps**  
🧠 Primary use-case: **Healthcare synthetic data modeling in low-resource environments**

---

## ❤️ Healthcare Applications

This GAN-based system is designed for:

- 🧬 **Synthetic medical data** generation  
- 🩺 **Data augmentation** in healthcare datasets  
- 🔐 **Privacy-preserving learning** (no real patient data)  
- 🤖 Deep learning for **rare conditions** or low-availability samples

---

## 📊 Results & Visualizations

### 🎨 Generated Samples

| DCGAN Output | Conditional GAN Output |
|--------------|------------------------|
| ![DCGAN](results/dcgan_sample.png) | ![CGAN](results/cgan_sample.png) |

---

### 📉 Training Loss Curves

![Loss](results/loss_curve.png)

---

### 🔥 Heatmaps – Feature Distribution

![Heatmap](results/heatmap_comparison.png)

---

### 🧭 Radar Chart – Performance Metrics

![Radar](results/radar_chart.png)

---

### 🧬 Dimensionality Reduction

| PCA | t-SNE |
|-----|-------|
| ![PCA](results/pca_plot.png) | ![t-SNE](results/tsne_plot.png) |

---

## 💻 Installation & Running

### 🧰 Requirements

```bash
pip install numpy matplotlib seaborn scikit-learn tensorflow

🌐 Clone This Project
git clone https://github.com/your-username/low-resource-gans-comparison.git
cd low-resource-gans-comparison
python untitled4.py

👤 Author & Contact
👨‍💻 Developed by: Sunil R
📧 Email: sunilr31r@gmail.com
🔗 GitHub: @your-username

If you use this work or are inspired by it, please consider giving credit or dropping a thank-you email. 🙌


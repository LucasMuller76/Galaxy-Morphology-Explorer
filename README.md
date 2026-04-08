# Galaxy Morphology Explorer 🔭

A deep learning research project focused on understanding galaxy morphology through representation learning, unsupervised clustering, and astrophysically meaningful latent spaces.

---

## 🚀 Overview

Galaxy morphology classification is a fundamental problem in astrophysics. With modern sky surveys generating massive volumes of data, automated, scalable, and interpretable solutions have become essential.

This project aims to go beyond traditional supervised classification by investigating whether classical galaxy morphology structures — such as ellipticals, spirals, and irregulars — can **emerge naturally from data** through modern deep learning techniques.

Rather than only predicting labels, this project focuses on learning **rich latent representations** of galaxy images and analyzing their structure to uncover meaningful patterns aligned with astrophysical theory.

---

## 🎯 Objectives

- Learn meaningful representations of galaxy images using deep learning
- Investigate whether morphological classes emerge in latent space
- Compare different representation learning approaches:
  - Convolutional Autoencoders
  - Variational Autoencoders (VAE, β-VAE)
  - Contrastive Learning (SimCLR-style)
- Perform clustering and evaluate latent space structure using:
  - UMAP / t-SNE
  - Silhouette Score
  - Linear Probing
- Analyze interpretability using:
  - Grad-CAM
  - Activation Maps
- Bridge machine learning outputs with astrophysical interpretation

---

## 📊 Dataset

This project uses the Galaxy Zoo 2 dataset:

- ~240,000 galaxy images
- Morphological classifications provided by human volunteers
- Based on SDSS (Sloan Digital Sky Survey) data

Source:
https://www.kaggle.com/datasets/jaimetrickz/galaxy-zoo-2-images

---

## 🧠 Research Questions

- Do galaxy morphology classes emerge naturally in learned latent spaces?
- Are morphological categories inherently discrete or continuous?
- Which representation learning method produces the most structured and interpretable embeddings?
- Can models capture physically meaningful features without explicit supervision?
- How does latent space geometry relate to known astrophysical properties?

---

## 🏗️ Project Structure


galaxy-morphology-explorer/
├── data/
│ ├── raw/
│ ├── processed/
│ └── catalogs/
├── src/
│ ├── data/
│ ├── models/
│ ├── training/
│ ├── analysis/
│ └── utils/
├── notebooks/
├── experiments/
├── tests/
└── paper/


---

## ⚙️ Tech Stack

- Python 3.11+
- PyTorch
- torchvision
- NumPy / Pandas
- Matplotlib / Seaborn
- scikit-learn
- UMAP-learn
- Weights & Biases (experiment tracking)
- astropy (astronomical data handling)

---

## 🧪 Methodology

The project is structured around three main approaches:

### 1. Supervised Learning
Baseline CNN models trained on labeled galaxy data to establish performance benchmarks.

### 2. Unsupervised Representation Learning
- Convolutional Autoencoders
- Variational Autoencoders (VAE, β-VAE)

Goal: learn compact latent representations and analyze their structure.

### 3. Self-Supervised Learning
- Contrastive learning (SimCLR-style)

Goal: learn robust representations without relying on labels.

---

## 🔬 Latent Space Analysis

Key techniques used to analyze learned representations:

- Dimensionality reduction: UMAP, t-SNE, PCA
- Clustering: K-Means, DBSCAN
- Metrics:
  - Silhouette Score
  - Mutual Information
  - Linear Probing

---

## 🧠 Interpretability

To ensure scientific validity and transparency:

- Grad-CAM for visual explanations
- Activation maps to identify relevant regions
- Feature attribution methods

---

## 🧪 Roadmap

- [ ] Baseline CNN (supervised classification)
- [ ] Autoencoder (latent space exploration)
- [ ] Variational Autoencoder (VAE)
- [ ] β-VAE experiments
- [ ] Contrastive Learning (SimCLR)
- [ ] Latent space analysis (UMAP / clustering)
- [ ] Interpretability analysis
- [ ] Research contribution
- [ ] Paper submission

---

## 📈 Expected Contributions

- Comparative study of representation learning methods for galaxy morphology
- Insights into the structure of latent spaces in astronomical data
- Identification of emergent morphological patterns
- Reproducible pipeline for astrophysical machine learning research
- Potential foundation for scientific publication

---

## 📄 License

This project is licensed under the MIT License.

---

## 🤝 Acknowledgements

- Galaxy Zoo Project
- Sloan Digital Sky Survey (SDSS)
- Open-source machine learning and astronomy communities

---

## 📬 Contact

Feel free to open issues or reach out for collaboration.

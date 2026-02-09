<div align="center">
  <h1> Deep Learning Project Hub</h1>
  <p><b>Advanced Neural Architectures & Research</b></p>

  <br/>

  <img src="https://img.shields.io/badge/Status-Active%20Research-success?style=for-the-badge&logo=statuspage" />
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Accelerator-GPU%20Enabled-red?style=for-the-badge&logo=nvidia" />
  <img src="https://img.shields.io/badge/Framework-TensorFlow%20%2F%20Keras-orange?style=for-the-badge&logo=tensorflow" />

  <br/><br/>

  <a href="#-medical-imaging-research">
    <img src="https://img.shields.io/badge/🏥_Medical-AI-34495E?style=for-the-badge" />
  </a>
  <a href="#-computer-vision-systems">
    <img src="https://img.shields.io/badge/👁️_Computer-Vision-34495E?style=for-the-badge" />
  </a>
  <a href="#-financial-analytics">
    <img src="https://img.shields.io/badge/📊_Finance-Analytics-34495E?style=for-the-badge" />
  </a>
</div>

---

## Distinction & Features

This repository serves as a centralized hub for advanced deep learning implementations, moving beyond basic tutorials into research-grade architectures.

* ** Multi-Scale Architectures:** Implementation of both lightweight (MobileNet-style) and complex (ResNet/Inception) models for performance benchmarking.
* ** Integrated Pipelines:** Notebooks contain end-to-end logic: `Data Augmentation` ➡️ `Normalization` ➡️ `Training` ➡️ `Evaluation`.
* ** Transfer Learning:** Utilizes pre-trained ImageNet weights for high-precision medical diagnostics.
* ** Cloud Native:** Optimized for **Google Colab** (TPU/GPU) and **Kaggle Kernels**.

---

##  Repository Structure

```text
Deep-Learning-Hub/
├──  Medical_Imaging/
│   ├── Brain_tumor_complex.ipynb      # MRI Segmentation & Classification
│   ├── chest_xray_pneumonia.ipynb     # Binary Classification (Pneumonia/Normal)
│   └── skin_cancer_ham10000.ipynb     # Multi-class Lesion Detection
├──  Computer_Vision/
│   ├── Expression_Recognition.ipynb   # FER-2013 Implementation
│   └── Digit_Prediction_MNIST.ipynb   # Optimized CNN
├──  Finance/
│   └── Financial_Rating.ipynb         # Credit Risk MLP
└── README.md

```

<a name="medical-sector"></a>

##  Medical Imaging Research

*High-precision diagnostics using Convolutional Neural Networks (CNNs) and Transfer Learning.*

| Project | Objective | Architecture | Status |
| --- | --- | --- | --- |
| **Brain Tumor Analysis** | MRI Scan classification & Segmentation | `Custom CNN` / `VGG-16` |  Done |
| **Pneumonia Detection** | Chest X-Ray analysis for opacity | `ResNet-50` |  Done |
| **Lung Cancer** | Pulmonary nodule detection | `3D CNN` |  In Progress |
| **Skin Lesion (HAM10000)** | Dermatoscopic cancer classification | `InceptionV3` |  Done |

> **Note:** Medical models leverage **Data Augmentation** (rotation, zoom, shear) to handle class imbalance.

---

<a name="vision-sector"></a>

## 👁️ Computer Vision Systems

*General-purpose visual recognition, feature extraction, and object detection.*

| Project | Description | Key Tech | Accuracy |
| --- | --- | --- | --- |
| **Expression Recognition** | Real-time facial emotion mapping (Happy, Sad, Angry, etc.) | `OpenCV` `Haar Cascades` | 78% |
| **Food & Vehicle Class.** | Large-scale multi-category object recognition | `EfficientNet` | 92% |
| **MNIST Digit** | Handwriting recognition engine | `LeNet-5 Variant` | **99.2%** |
| **CIFAR-10** | Baseline object detection benchmark | `Sequential CNN` | 85% |

---

<a name="finance-sector"></a>

##  Financial Analytics

*Deep Learning applied to non-visual tabular datasets.*

####  Financial Rating Predictor

An Artificial Neural Network (ANN) approach to corporate credit scoring and risk assessment.

* **Input:** Financial ratios (Liquidity, Profitability, Leverage).
* **Model:** Multi-Layer Perceptron (MLP).
* **Optimizer:** Adam with Dynamic Learning Rate Decay.
* **Loss Function:** Binary Cross-Entropy.

---

<a name="technical-setup"></a>

##  Setup & Execution

<details>
<summary><b> Local Installation (Click to Expand)</b></summary>

Prerequisites: Python 3.10+ and CUDA (if using GPU).

1. **Clone the Repository**
```bash
git clone [https://github.com/vishva2410/Deep-Learning-Hub.git](https://github.com/vishva2410/Deep-Learning-Hub.git)
cd Deep-Learning-Hub

```


2. **Install Dependencies**
```bash
pip install tensorflow-gpu opencv-python matplotlib pandas scikit-learn seaborn

```


3. **Launch Jupyter**
```bash
jupyter notebook

```



</details>

<details>
<summary><b> Google Colab Setup (Click to Expand)</b></summary>

1. Upload the `.ipynb` file to your Google Drive.
2. Open with Google Colab.
3. Change Runtime Type: **Runtime -> Change runtime type -> T4 GPU**.

</details>

---

<div align="center">
<h3>👤 Lead Developer</h3>
<p><b>Vishva</b></p>
<p>
<a href="https://www.google.com/search?q=https://github.com/vishva2410">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/GitHub-Profile-black%3Fstyle%3Dfor-the-badge%26logo%3Dgithub" />
</a>
<a href="https://www.google.com/search?q=https://linkedin.com/in/vishva-teja-guduguntla">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/LinkedIn-Connect-blue%3Fstyle%3Dfor-the-badge%26logo%3Dlinkedin" />
</a>
</p>
<p><i>Building the future of AI, one epoch at a time.</i></p>
</div>

```

```

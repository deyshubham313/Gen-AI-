# 🔬 Generative AI Lab Experiments

This repository contains a comprehensive set of **Generative AI laboratory experiments** covering fundamental to advanced concepts in probabilistic modeling, deep learning, and generative architectures.

---

## 📚 Course Information

* **Course Title:** Advanced Topics in Generative Modeling
* **Focus Areas:**

  * Distribution Sampling
  * Likelihood-based Learning
  * Neural Networks
  * GANs (Generative Adversarial Networks)
  * Variational Autoencoders (VAE)
  * Normalizing Flows
  * Autoregressive Models
  * Model Evaluation Metrics

---

## 📋 Table of Contents

| #  | Experiment      | Topic                        |
| -- | --------------- | ---------------------------- |
| 1  | Random Sampling | Probability Distributions    |
| 2  | MLE             | Parameter Estimation         |
| 3  | Neural Networks | Backpropagation & SGD        |
| 4  | GAN             | Image Generation             |
| 5  | Flow Models     | Density Estimation           |
| 6  | Metrics         | Model Evaluation             |
| 7  | Validation      | Model Testing                |
| 8  | VAE             | Encoder-Decoder Architecture |
| 9  | PixelCNN        | Autoregressive Models        |
| 10 | GAN Loss        | Theoretical Analysis         |
| 📁 | Project         | Parameter Estimation         |

---

## ⚙️ Setup & Installation

### 🔧 Requirements

Install the following dependencies before running the notebook:

```bash
pip install numpy matplotlib scikit-learn torch torchvision
```

---

## 🧪 Experiments Overview

### 🔹 Experiment 1: Sampling from Distributions

* Generated samples from:

  * Gaussian Distribution
  * Uniform Distribution
  * Exponential Distribution
* Visualized using histograms and compared with theoretical PDFs.

---

### 🔹 Experiment 2: Maximum Likelihood Estimation (MLE)

* Estimated parameters of Gaussian distribution.
* Compared:

  * Analytical solution
  * Numerical optimization
* Demonstrated **consistency of estimators**.

---

### 🔹 Experiment 3: Neural Network Training

* Built a **Multi-Layer Perceptron (MLP)** using PyTorch.
* Applied:

  * Backpropagation
  * Stochastic Gradient Descent (SGD)
* Achieved high accuracy on MNIST dataset.

---

### 🔹 Experiment 4: Generative Adversarial Network (GAN)

* Implemented:

  * Generator
  * Discriminator
* Trained adversarial model for image synthesis.
* Observed convergence toward Nash equilibrium.

---

### 🔹 Experiment 5: Normalizing Flow Model

* Implemented invertible transformations.
* Used **Affine Coupling Layers (RealNVP)**.
* Learned complex distributions from simple Gaussian.

---

### 🔹 Experiment 6: Evaluation Metrics

* Implemented:

  * Accuracy
  * Precision
  * Recall
  * F1 Score
  * ROC-AUC
* Used `scikit-learn` for evaluation.

---

### 🔹 Experiment 7: Model Validation

* Evaluated trained models on validation dataset.
* Checked generalization performance.

---

### 🔹 Experiment 8: Variational Autoencoder (VAE)

* Implemented encoder-decoder architecture.
* Learned latent representations.
* Generated new samples from latent space.

---

### 🔹 Experiment 9: Autoregressive Model (PixelCNN)

* Modeled pixel dependencies sequentially.
* Generated images pixel-by-pixel.

---

### 🔹 Experiment 10: GAN Loss Analysis

* Studied:

  * Generator loss
  * Discriminator loss
* Analyzed training stability and convergence.

---

## 📊 Project: Parameter Estimation

* Applied statistical techniques to estimate distribution parameters.
* Compared theoretical and empirical results.
* Evaluated model performance.

---

## 🚀 Key Learning Outcomes

* Strong understanding of **Generative Models**
* Hands-on experience with:

  * GANs, VAEs, Flows
* Practical implementation of:

  * Deep Learning pipelines
  * Optimization techniques
* Insight into:

  * Model evaluation and validation

---

## 🛠️ Technologies Used

* Python
* NumPy
* Matplotlib
* Scikit-learn
* PyTorch

---

## 📁 File Structure

```
├── Gen AI Lab Experiments.ipynb
├── README.md
```

---

## 👨‍💻 Author

**Shubham Dey**
B.Tech CSE (Data Science)

---

## ⭐ Usage

Run the notebook step-by-step:

```bash
jupyter notebook
```

---


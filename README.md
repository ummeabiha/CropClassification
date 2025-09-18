# 🌾 Crop Classification using Deep Learning (TensorFlow & PyTorch)

This project implements a deep learning approach to classify crops using image datasets. We provide two parallel implementations — **TensorFlow** and **PyTorch** — for performance comparison and reproducibility.

---

## 📌 Project Overview

The goal of this project is to build and evaluate deep learning models for **crop classification** using image data. Both TensorFlow and PyTorch implementations are provided to compare training pipelines, performance metrics, and overall usability.

---

## 🛠️ Tech Stack

* **Languages:** Python
* **Frameworks:** TensorFlow, PyTorch
* **Model:** CNN (Convolutional Neural etwork)
* **Tools:** NumPy, Pandas, Matplotlib, Scikit-learn, TorchVision, TensorFlow Datasets
---

## 🚀 Steps in the Workflow

### 1. Dataset Preparation

* Collected and preprocessed crop images.
* Performed **train-test split**.
* Applied normalization and resizing for compatibility with CNN models.
* Used **data augmentation** (rotation, flipping, zoom) to reduce overfitting.

### 2. Model Building

* **TensorFlow:** Implemented a **CNN** using `tf.keras.Sequential`.
* **PyTorch:** Implemented a CNN using `torch.nn.Module`.
* Layers included convolutional, pooling, dropout, and dense layers.

### 3. Model Training

* Defined **loss functions**: Cross-Entropy Loss.
* Optimizers: Adam / SGD.
* Used **early stopping** and checkpoints (TensorFlow).
* Trained on GPU (if available).

### 4. Model Evaluation

* Calculated accuracy, precision, recall, and F1-score.
* Compared **macro** and **weighted averages** for imbalanced classes.
* Generated **confusion matrices** and **classification reports**.

### 5. Results & Comparison

| Framework  | Accuracy | 
| ---------- | -------- | 
| TensorFlow | \~0.95   | 
| PyTorch    | \~0.76   | 

📊 **Conclusion:** TensorFlow outperformed PyTorch in this classification task, maintaining higher accuracy and balanced metrics.

---

## 📷 Sample Outputs

* Training accuracy/loss curves
* Confusion matrix of classification results

---

## 📌 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/ummeabiha/CropClassification.git
   cd CropClassification
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebooks and run:

   * `Training Tensor Flow Model.ipynb`
   * `Training PyTorch Model.ipynb`

---

## 📚 Future Work

* Extend dataset for more crop categories.
* Experiment with transfer learning (ResNet, EfficientNet, etc.).
* Deploy the best-performing model as a web/mobile application.

---



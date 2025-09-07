#  Caltech-101 Image Classification

This project applies **Convolutional Neural Networks (CNNs)** with **transfer learning (EfficientNet-B6)** to classify images from the [Caltech-101 dataset](https://data.caltech.edu/records/20086).
The dataset contains **101 object categories** (animals, vehicles, instruments, etc.), making it a challenging image classification task.

✅ **Training Accuracy:** 98.56%
✅ **Validation Accuracy:** 93.00%

---

## 📂 Contents

* `Caltech101_EfficientNet.ipynb` – Main notebook with model implementation and training
* `requirements.txt` – Dependencies used in the project
* `training_log.csv` – Training curves (accuracy/loss per epoch)

---

## ⚙️ Requirements

* Python 3.x
* TensorFlow / Keras
* NumPy
* Matplotlib
* scikit-learn

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run

1. Download the **Caltech-101 dataset** from [Caltech Dataset Page](https://data.caltech.edu/records/20086) or via **TensorFlow Datasets**.
2. Place the dataset in a folder named `data/` (or update the dataset path in the notebook).
3. Run the notebook:

```bash
jupyter notebook Caltech101_EfficientNet.ipynb
```

---


## 🏷️ Topics

`cnn` `image-classification` `deep-learning` `transfer-learning` `efficientnet` `caltech101`

---



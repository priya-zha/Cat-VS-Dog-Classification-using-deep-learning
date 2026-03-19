# 🐱🐶 Cat vs Dog Classification using Deep Learning (CNN)

A binary image classification project that distinguishes between cats and dogs using a Convolutional Neural Network (CNN) built with Keras/TensorFlow. A classic deep learning benchmark problem demonstrating the power of CNNs for image recognition.

---

## 📌 Description

This project trains a CNN model on the famous Dogs vs. Cats dataset to classify images as either a cat or a dog. It demonstrates fundamental deep learning concepts including image preprocessing, data augmentation, CNN architecture design, and binary classification with sigmoid activation. The model achieves strong accuracy and generalizes well to unseen images.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| TensorFlow / Keras | CNN model building and training |
| NumPy | Array manipulation |
| Matplotlib | Visualizing training metrics and sample predictions |
| Jupyter Notebook | Development and experimentation environment |

---

## 📁 Project Structure

```
├── dogsvscat.ipynb   # Full notebook: data loading, CNN training, evaluation, predictions
```

---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/priya-zha/Cat-VS-Dog-Classification-using-deep-learning.git
cd Cat-VS-Dog-Classification-using-deep-learning
```

### 2. Install Dependencies
```bash
pip install tensorflow keras numpy matplotlib jupyter
```

### 3. Download the Dataset
- Download the [Dogs vs. Cats dataset from Kaggle](https://www.kaggle.com/c/dogs-vs-cats/data)
- Extract and place it in the directory referenced in the notebook

### 4. Launch the Notebook
```bash
jupyter notebook dogsvscat.ipynb
```

---

## 🚀 Usage

1. Open the notebook in Jupyter or Google Colab
2. Run cells in order to:
   - Load and preprocess cat and dog images
   - Apply data augmentation (flips, zoom, shear)
   - Build and compile the CNN model
   - Train on the dataset and validate performance
   - Visualize accuracy/loss curves
   - Run predictions on test images

---

## 📋 Requirements

- Python 3.6+
- TensorFlow 2.x / Keras
- NumPy
- Matplotlib

---

## 👩‍💻 Author

**Priya** — [@priya-zha](https://github.com/priya-zha)

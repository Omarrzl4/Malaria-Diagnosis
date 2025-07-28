# 🦠 Malaria Image Detection

## 📌 Project Description

This project implements a **deep learning model** to detect malaria in **microscopic images of red blood cells**. It leverages **Convolutional Neural Networks (CNNs)** with techniques like **Batch Normalization**, **Dropout**, and **L2 regularization** to accurately classify infected and uninfected cells.

---

## 🧠 Why This Project?

Early and accurate detection of malaria is critical for effective treatment. Manual diagnosis is time-consuming and error-prone. This automated solution improves accuracy and efficiency using image-based analysis powered by deep learning.

---

## 🖼️ Dataset

- **Input**: Microscopic images of red blood cells
- **Classes**:
  - `Parasitized` (infected with malaria)
  - `Uninfected` (healthy red blood cells)

> Dataset is typically sourced from the **NIH Malaria Dataset**, which contains over 27,000 labeled cell images.

---

## 🏗️ Model Architecture

### 🔍 Feature Extraction

- `Conv2D`: Extracts visual patterns from images using multiple filters
- `BatchNormalization`: Speeds up training and stabilizes learning
- `MaxPooling2D`: Reduces spatial size and computation
- `Dropout`: Prevents overfitting by randomly deactivating neurons

### 🧮 Classification

- `Dense` layers: Fully connected layers to classify features
- `Activation Functions`: 
  - `ReLU` for hidden layers
  - `Sigmoid` for binary classification output

---

## 🧪 Features & Techniques

- ✅ **CNN Architecture** with multiple convolutional layers
- 📉 **L2 Regularization** to reduce overfitting
- 🔄 **BatchNormalization** for faster convergence
- 💧 **Dropout Layers** to improve generalization
- 📊 Final output: Probability that a cell is infected

---

## 📦 Libraries Used

- TensorFlow / Keras
- NumPy
- Matplotlib
- Pandas
- Scikit-learn (for evaluation and preprocessing)

---

## 📈 Evaluation

- Accuracy and loss tracked during training
- Confusion matrix and classification report used on test set
- Visualizations of training/validation accuracy and loss across epochs

---

## 👨‍💻 Author

**Omar Al Zoghbi**

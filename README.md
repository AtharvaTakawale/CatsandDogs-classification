# Cats vs Dogs Image Classification using CNN

## 📌 Problem Statement
Build a Convolutional Neural Network (CNN) to classify images as **cats** or **dogs**.

---

## 📂 Dataset
- Cats and Dogs image dataset  
- Images are preprocessed and normalized before training

---

## 🧠 Model Architecture
The CNN model consists of:
- Conv2D layers for feature extraction
- MaxPooling2D layers to reduce spatial dimensions
- Flatten layer to convert features into a vector
- Dense layers for final classification

---

## ⚙️ Training Details
- Framework: TensorFlow / Keras
- Image normalization (pixel values scaled from 0–255 to 0–1)
- Train–validation split used to monitor overfitting

---

## 📊 Results
- Training Accuracy: *(0.9766)*
- Validation Accuracy: *(0.8288)*

Training and validation performance is visualized using accuracy and loss graphs.

---

## ▶️ How to Run
1. Open the notebook in **Google Colab**
2. Upload or link the dataset
3. Run all cells from top to bottom

---

## 🎯 What I Learned
- Basics of CNN architecture
- Image preprocessing and normalization
- Handling overfitting using validation data
- Interpreting training vs validation curves

---

## 🚀 Future Improvements
- Data augmentation
- Hyperparameter tuning
- Trying deeper CNN architectures

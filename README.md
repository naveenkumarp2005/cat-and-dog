# 🐱🐶 Cat vs Dog Image Classification

A deep learning project that classifies images as either **cats** or **dogs** using TensorFlow and Keras.

## 📌 Project Overview

This project builds a Convolutional Neural Network (CNN) to distinguish between cat and dog images. The dataset is loaded using TensorFlow utilities, preprocessed, and used to train a binary image classification model.

## 🚀 Features

- Image dataset loading using TensorFlow
- Data preprocessing and visualization
- Convolutional Neural Network (CNN)
- Model training and validation
- Prediction on new images
- Performance evaluation

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- KaggleHub

## 📂 Dataset

The project uses the **Cat vs Dog** dataset from Kaggle.

Dataset:
https://www.kaggle.com/datasets/sanchitnamdeo/catvsdog

You can download it using:

```python
import kagglehub

path = kagglehub.dataset_download("sanchitnamdeo/catvsdog")
print(path)
```

## 📁 Project Structure

```
├── cat_and_dog3.ipynb    # Jupyter Notebook
├── README.md             # Project documentation
```

## ▶️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/naveenkumarp2005/cat-and-dog.git
cd cat-and-dog
```

### 2. Install dependencies

```bash
pip install tensorflow matplotlib numpy kagglehub
```

### 3. Run the notebook

Open the notebook using Jupyter Notebook or VS Code.

```bash
jupyter notebook cat_and_dog.ipynb
```

## 📈 Future Improvements

- Apply data augmentation
- Use transfer learning (MobileNetV2, ResNet50)
- Hyperparameter tuning
- Deploy using Flask or Streamlit
- Save and load trained models


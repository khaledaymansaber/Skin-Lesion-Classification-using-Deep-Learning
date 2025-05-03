# 🧠 Skin Lesion Classification with Deep Learning

This project focuses on classifying skin lesions as **benign** or **malignant** using deep learning and dermatoscopic images. It leverages **EfficientNetB0** with transfer learning and is implemented in **TensorFlow** using **Google Colab**.

---

## 📌 Project Overview

Skin cancer is one of the most common cancers globally, and early detection is critical. This project builds a Convolutional Neural Network (CNN) pipeline to assist in the automatic classification of skin lesions using medical image data. The project is structured to support experimentation, reproducibility, and future deployment in clinical decision-support tools.

---

## 🚀 Features

- Image preprocessing and resizing  
- Data augmentation to reduce overfitting  
- Transfer learning using EfficientNetB0  
- Model regularization with Dropout and EarlyStopping  
- Learning rate scheduling and checkpointing  
- Confusion matrix and performance evaluation  
- Built and tested in Google Colab

---

## 🧰 Technologies Used

- Python  
- TensorFlow / Keras  
- EfficientNetB0 (Pretrained)  
- Google Colab  
- NumPy, Matplotlib, Seaborn, Pandas

---

## 📁 Dataset

This project uses a dataset of dermatoscopic images labeled as **benign** or **malignant**. The images were pre-organized into respective folders and split into:

- Training Set: 70%  
- Validation Set: 15%  
- Test Set: 15%

*Note: You should replace this with a public dataset link or dataset description if available.*

---

## 🧪 Model Architecture

- **Base Model:** EfficientNetB0 (pretrained on ImageNet, `include_top=False`)  
- **Custom Layers:**  
  - GlobalAveragePooling2D  
  - Dropout  
  - Dense (fully connected output layer)

---

## 🧠 Training Details

- **Optimizer:** Adam  
- **Loss Function:** Binary Crossentropy  
- **Metrics:** Accuracy, Recall  
- **Callbacks:** EarlyStopping, ReduceLROnPlateau, ModelCheckpoint

---

## 📊 Results

The model was trained and evaluated using metrics and visualizations such as:

- Training/validation accuracy and loss plots  
- Confusion matrix  
- Classification report (precision, recall, F1-score)



---

## 📌 How to Run

You can run the project in **Google Colab**:

1. Upload the dataset (organized into `train`, `val`, `test` folders).
2. Open the notebook file (`Skin_Lesion_Classification.ipynb`).
3. Run all cells in order to train and evaluate the model.

---

## 📎 Folder Structure (Recommended)


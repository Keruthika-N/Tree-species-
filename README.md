# 🌳 Tree Species Classification using CNN

A deep learning project that classifies tree species based on leaf images using Convolutional Neural Networks (CNNs). The model is trained on a custom dataset of **30 different tree species** and deployed using a user-friendly **Streamlit** web app.

---

## 🧠 Problem Statement

Manual identification of tree species can be time-consuming and error-prone. This project aims to automate the process using AI, particularly CNN models, to predict the species from a tree leaf image.

---

## 🎯 Learning Objectives

- 🔍 Understand and apply CNN architectures for image classification.
- 🤖 Train a deep learning model on a real-world, multi-class dataset.
- 🛠️ Preprocess and augment image data for better model generalization.
- 💻 Deploy the trained model using Streamlit for real-time prediction.

---

## 🛠️ Tools & Technologies Used

| 🔧 Technology       | 💬 Purpose                            |
|--------------------|----------------------------------------|
| Python 🐍          | Programming language                   |
| TensorFlow / Keras 🔧 | Model building & training         |
| Streamlit 🌐        | Web app deployment                    |
| NumPy / Pandas 📊   | Data manipulation                     |
| Matplotlib 📈       | Visualization of training metrics     |
| PIL 🖼️              | Image processing                      |

---

## 📁 Dataset

- **Total Classes**: 30
- **Image Types**: Leaf images
- **Source**: Custom dataset (Drive / Kaggle)
- **Preprocessing**:
  - Image resizing to `224x224`
  - Rescaling pixel values
  - Data Augmentation (rotation, zoom, flip)

---

## 🏗️ Methodology

1. **Data Preprocessing**
   - Applied ImageDataGenerator for augmentation and validation split

2. **Model Building**
   - Started with a basic CNN
   - Improved using Batch Normalization, Dropout & Adam optimizer

3. **Training**
   - Trained for up to 25 epochs using categorical crossentropy loss

4. **Deployment**
   - Saved model as `.h5` and created a `Streamlit` app for prediction

---

## 📦 Project Structure

tree_species_classifier/
│
├── app.py # Streamlit web app
├── improved_cnn_model.h5 # Trained CNN model
├── requirements.txt # Python dependencies
├── README.md # You're reading it!
└── dataset/ # Tree species leaf images



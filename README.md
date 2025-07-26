# 🌳 Tree Species Classifier

This project is part of my internship task for Week 1.  
The goal is to classify tree species using an image dataset and Google Colab.

---

1. Uploaded the **Tree Species Dataset** to Google Drive.
2. Mounted Google Drive in Google Colab.
3. Unzipped the dataset in Colab for use.
4. Built a Jupyter notebook to work with the image dataset.

---

📌 Project Structure

├── Tree_Species_Classification/
│   ├── archive1.zip
│   ├── cleaned_dataset/
│   ├── train/
│   ├── val/
│   ├── model/
│   ├── improved_cnn_model.h5
│   └── notebook.ipynb


---


The dataset contains images of 30 tree species, each in its own folder. The dataset was cleaned by:

    Removing duplicate images

    Detecting and excluding corrupted files

    Filtering out extreme outliers (very small or large image dimensions)

---

## 🚀 How to Run the Notebook

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload and open `TreeSpeciesClassifier.ipynb`
3. Follow the steps:
   - Mount your Google Drive
   - Set the zip file path
   - Extract the dataset
   - Load and process the data

---

## 🧠 Technologies Used

- Python 🐍
- Google Colab 📒
- Google Drive 💾
- Jupyter Notebook
- Basic file handling and zip extraction

---

🧪 Data Preprocessing

    Used ImageDataGenerator for image rescaling and data augmentation

    Resized all images to 224x224

    80% for training, 20% for validation

Augmentations applied:

    Rotation

    Zoom

    Shear

    Horizontal fli

    ---
    🧠 Model Architecture
CNN Structure:

Conv2D → BatchNorm → MaxPool
Conv2D → BatchNorm → MaxPool
Conv2D → BatchNorm → MaxPool
Conv2D → BatchNorm → MaxPool
Flatten → Dense → Dropout → Output(Softmax)

## 📌 Notes

- This is a beginner-friendly project.
- Dataset is used only for learning and training purposes.

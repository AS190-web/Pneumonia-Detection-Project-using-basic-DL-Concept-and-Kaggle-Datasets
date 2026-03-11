🩺 Pneumonia Detection using Deep Learning (Chest X-Ray)

This project implements a Pneumonia Detection System using Deep Learning techniques on Chest X-ray images.
The objective is to automatically classify X-ray images as Pneumonia or Normal using Convolutional Neural Network (CNN) based models and ensemble learning.

The project demonstrates how AI can assist in medical image analysis using modern deep learning methods.

📌 Project Highlights

Binary classification: Pneumonia vs Normal

Implementation using basic Deep Learning concepts

Multiple CNN models trained and compared

Ensemble learning used for improved prediction performance

Explainability using Grad-CAM

Performance evaluated using standard classification metrics

🧠 Models Implemented

The following deep learning models were implemented and evaluated:

Simple CNN Model

VGG-based CNN Model

ResNet-based Model

Ensemble Model combining multiple architectures

📊 Evaluation Metrics

Model performance was evaluated using the following metrics:

Accuracy

Precision

Recall

F1-Score

ROC Curve & AUC

Confusion Matrix

Precision–Recall Curve

Representative evaluation plots and Grad-CAM visualizations are included in this repository.

Note:
All visualizations are generated from the same validation dataset.
Selected representative plots are included for clarity.

🗂 Dataset

Chest X-Ray Pneumonia Dataset

Source (Kaggle):
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

⚠️ The dataset is not included in this repository due to its large size.

🛠 Tools & Technologies

Python

TensorFlow / Keras

NumPy

Pandas

Matplotlib

Seaborn

Google Colab

🚀 How to Run the Project
1️⃣ Open the notebook

Open the project notebook in Google Colab.

2️⃣ Download dataset

Download the dataset from Kaggle and upload it to your environment.

3️⃣ Update dataset path

Modify the dataset path inside the notebook if required.

4️⃣ Run the notebook

Run all cells sequentially to train and evaluate the models.

📎 Google Colab Notebook:
https://colab.research.google.com/drive/189UVaYyZdLLDI2BNy6I3WHmnMRAj70t2

📊 Results

All evaluation plots, model performance visualizations, and Grad-CAM outputs generated during training and testing are stored in the Results/ directory.

⚠️ Disclaimer

This project is intended for educational and research purposes only.
It should not be used for real-world medical diagnosis or clinical decision-making.

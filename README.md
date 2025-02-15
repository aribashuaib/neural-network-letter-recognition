# Neural-Network-Letter-Recognition
# Letter Recognition with Neural Networks

This project implements a **deep learning model** to classify handwritten letters (A-Z) using the **UCI Letter Recognition Dataset**. The model is built with **TensorFlow/Keras** and achieves an impressive **92.6% accuracy** on the test set. 🚀  

## Project Overview

Handwriting recognition is a fundamental problem in AI, with applications in **OCR (Optical Character Recognition), document digitization,** and **assistive technology**. In this project, we:  

- **Preprocessed the dataset** (scaling and encoding labels)  
- **Built a neural network** with dropout for regularization  
- **Trained the model** on 16,000 samples and tested on 4,000 samples  
- **Evaluated performance** using accuracy and classification reports  

---

## 📊 Dataset Information  

**Dataset:** [UCI Letter Recognition Dataset](https://archive.ics.uci.edu/ml/datasets/Letter+Recognition)  
**Features:** 16 numerical attributes extracted from font images  
**Classes:** 26 (A-Z letters)  
**Samples:** 20,000 (16,000 train / 4,000 test)  

---

## ⚙️ Installation  

To run the project locally, follow these steps:  

### **Clone the Repository**  
```sh
git clone https://github.com/aribashuaib/LetterRecognition-ML.git
cd LetterRecognition-ML

📦 Dependencies:
To run this project, install the following Python packages:

- `numpy`
- `pandas`
- `tensorflow`
- `matplotlib`

🚀 Running the Model:
After installing the dependencies, run the script to train and evaluate the model:
python train.py

The model will:
-Fetch the UCI Letter Recognition Dataset
-Preprocess the data (scaling & encoding)
-Train a neural network
-Evaluate performance and print accuracy & classification reports

📈 Model Performance:
-Final Accuracy: 92.6%
-Loss Trend: Model loss steadily decreases over epochs
-Best Validation Accuracy: 92.6% after 20 epochs




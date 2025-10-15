# 🧠 Parkinson's Disease Detection using Pre-trained EfficientNet

## 📘 Overview
This project focuses on detecting **Parkinson’s Disease (PD)** using deep learning techniques and **transfer learning** with the **EfficientNet** architecture.  
By leveraging pre-trained models, the system achieves high accuracy in distinguishing between Parkinson’s and healthy subjects from biomedical or voice-based data.

---

## 🎯 Objective
- To develop a **robust and efficient model** for early detection of Parkinson’s Disease.  
- To utilize **transfer learning** for faster convergence and higher accuracy.  
- To evaluate the model's performance and demonstrate its clinical potential.

---

## 🧩 Model Architecture
- **Base Model:** EfficientNet (pre-trained on ImageNet)
- **Fine-tuning:** Top layers replaced with custom dense layers for binary classification.
- **Activation:** ReLU for hidden layers, Sigmoid for final output.
- **Optimizer:** Adam
- **Loss Function:** Binary Crossentropy
- **Accuracy Achieved:** ✅ **95%**

---

## ⚙️ Requirements
To run this project, install the dependencies:

```bash
pip install tensorflow keras numpy pandas matplotlib scikit-learn

# leukemia-detection-cnn
A deep learning research project using Convolutional Neural Networks (CNNs) to support early detection of Acute Lymphoblastic Leukemia (ALL) in children through automated analysis of blood smear images. Built as part of my research focus in AI/ML for pediatric oncology.
# Leukemia Detection Using Convolutional Neural Networks (CNN)

This project focuses on applying **Deep Learning** to assist in the **early detection of Acute Lymphoblastic Leukemia (ALL)** in children using microscopic blood smear images. Early diagnosis of leukemia can significantly improve treatment outcomes, and AI can support pathologists by automating the visual analysis of cell morphology.

---

## 🎯 Project Goal
To build a CNN-based image classification model that can distinguish between:
- Normal lymphocyte cells  
- Leukemic (ALL) lymphoblast cells

This serves as a foundational research project in my journey toward AI/ML in Pediatric Oncology, specifically supporting early cancer detection in children.

---

## 🧠 Why This Matters
- Leukemia is the most common cancer in children.
- Early detection dramatically increases survival rates.
- Manual diagnosis using microscopes is slow and error-prone.
- AI can enhance speed, accuracy, and decision support for clinicians.

---

## 🗂️ Dataset
Dataset: ALL-IDB2  
The dataset is categorized into four distinct morphological stages:
1. **Benign** (Normal Lymphocytes)
2. **Early** (Early-stage Lymphoblasts)
3. **Pre** (Pre-B/T Lymphoblasts)
4. **Pro** (Promyelocytic blasts)
A publicly available, ethically-approved dataset of blood smear images.

Contains:
| Class | Description |
|------|-------------|
| ALL | Images with leukemic lymphoblast cells |
| Normal | Images with healthy lymphocyte cells |

Dataset Source → (I will add links after the notebook setup)

---

## 🏗️ Model Architecture (Simple CNN)
The model is built using:
- Convolution layers
- Max-pooling layers
- Dropout regularization
- Fully connected classifier head

This architecture is chosen for:
- Interpretability
- Clarity in training behavior
- Strong baseline performance

(Advanced versions using ResNet & Vision Transformers will follow in next projects.)

---

## 🔧 Technologies Used
| Category | Tools |
|---|---|
| Programming | Python |
| Deep Learning | TensorFlow / Keras |
| Data Handling | NumPy, Pandas |
| Visualization | Matplotlib |
| Execution | Google Colab |

---

## 📊 What Will Be Evaluated
- Training accuracy and validation accuracy
- Loss curves
- Confusion matrix
- Sample predictions

Visual results of the model will be saved in a `results/` folder.

---

## 🚀 Next Steps (Planned Enhancements)
| Stage | Upgrade |
|---|---|
| Project 2 | Transfer Learning using ResNet50 |
| Project 3 | Vision Transformers for medical imaging |
| Project 4 | Deploy model as a web-based diagnostic assistant |

---

## 👩🏽‍💻 Research Direction
This project is part of my long-term research pathway into:

AI for Pediatric Oncology → Early Detection → Personalized Treatment Recommendations

---

## ✨ Author
Sheena Dzamefe 
GitHub: https://github.com/sheeCancode

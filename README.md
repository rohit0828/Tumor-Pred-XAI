# 🧠 Tumor Prediction using Explainable AI (XAI)

This project leverages a CNN-based deep learning model using **PyTorch** and **VGG16** to classify brain tumor MRI images into 4 types with **97% accuracy**. It incorporates **Grad-CAM** for model interpretability by generating class-specific heatmaps over tumor regions.

---

## 🔧 Tech Stack

- PyTorch
- VGG16 (Transfer Learning)
- Grad-CAM (pytorch-grad-cam)
- CNN, PIL, Torchvision, Matplotlib

---

## 📊 Features

- Tumor classification across **4 categories**: glioma, meningioma, pituitary, and no tumor  
- Grad-CAM heatmaps for class-specific interpretability  
- Performance evaluated using accuracy, precision, recall, and confusion matrix  
- Real-time prediction-ready architecture with support for unseen images

---

## 📥 Download Dataset

[📂 Click here for dataset link](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)


The dataset is structured using `ImageFolder` format with 4 classes and two sets:

```yaml
Tumor Dataset:
  Training:
    - glioma
    - meningioma
    - pituitary
    - notumor
  Testing:
    - glioma
    - meningioma
    - pituitary
    - notumor
```

Each subfolder contains MRI images representing its respective class.

---

## 🖼️ Sample Output (Grad-CAM)

![Grad-CAM Example](https://github.com/rohit8082/Tumor-Pred-XAI/blob/main/gradecam_git_project_otp.png?raw=true)

---

Feel free to explore the code, raise issues, or contribute!

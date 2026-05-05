# 🌴 Palm Leaf Disease Detection

## 📌 Project Overview
This project focuses on developing a **deep learning-based image classification system** to detect diseases in palm leaves.  
The model classifies images into categories such as:

- Brown Spots  
- Healthy  
- White Scale  

This enables **early and accurate disease detection** in agricultural applications.

---

## 🧠 Models Used
Multiple pretrained CNN architectures were explored using **transfer learning**:

- **MobileNetV2** → Lightweight and fast baseline model  
- **ResNet50** → Deeper architecture with residual learning (~80% accuracy)  
- **EfficientNetB0** → Advanced model with optimized performance (~93–96% accuracy)  

---

## ⚙️ Techniques Applied
To improve model performance, the following techniques were used:

- 🔄 **Data Augmentation**  
  - Rotation  
  - Zoom  
  - Brightness adjustment  
  - Horizontal flipping  

- ⚖️ **Class Weights**  
  - Handled imbalanced dataset  

- 🎯 **Label Smoothing**  
  - Improved generalization  

- 🔁 **Two-Stage Training**
  1. **Feature Extraction** (Freezing pretrained layers)  
  2. **Fine-Tuning** (Unfreezing deeper layers)  

---

## 🚀 Results
- Best performance achieved using **EfficientNetB0**  
- Achieved:
  - **Accuracy:** ~95%  
  - High precision and recall across all classes  

---

## 🌱 Conclusion
This project demonstrates how **modern deep learning architectures** combined with transfer learning can be effectively used for **agricultural disease detection**.

The system is:
- Accurate ✅  
- Efficient ⚡  
- Suitable for real-world applications 🌍  

---

## 🛠️ Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy, Matplotlib, Scikit-learn  

---

## 📊 Future Improvements
- Deploy as a web app (Streamlit/Flask)  
- Expand dataset for better generalization  
- Explore EfficientNet variants (B1–B7)  

---

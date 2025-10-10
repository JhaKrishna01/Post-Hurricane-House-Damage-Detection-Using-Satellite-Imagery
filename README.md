# 🛰️ Post-Hurricane Danger Detection Using Satellite Imagery

### VIT-AP | Jan 2025 – Apr 2025

This project develops a **deep learning pipeline** to automatically detect **post-hurricane hazardous zones** from satellite imagery.  
It leverages **Convolutional Neural Networks (CNNs)** for **binary classification** — identifying whether a region is damaged or safe — to assist disaster response teams with rapid, data-driven insights.

---

## 🚀 Overview

With the growing availability of **satellite imagery**, deep learning offers a scalable and automated way to assess disaster damage.  
This project compares multiple CNN architectures for accurate and explainable **post-disaster image classification**.

---

## 🧠 Model Architectures

### 1. Base CNN Model
- Standard convolutional layers with ReLU activation and max pooling.
- Acts as the baseline network.

### 2. CNN with L2 Regularization
- Adds L2 weight penalties to combat overfitting.
- Shows smoother validation performance and better generalization.

### 3. Hybrid CNN Model
- Merges feature maps from multiple convolutional branches.
- Improves contextual understanding and detection accuracy.

---

## ⚙️ Tech Stack

- **Frameworks:** TensorFlow, Keras  
- **Language:** Python (Jupyter Notebook)  
- **Data Handling:** NumPy, Pandas  
- **Visualization:** Matplotlib, Seaborn  
- **Big Data Preprocessing:** Scalable satellite image handling  
- **Environment:** GPU-based runtime (e.g., Google Colab or CUDA)

---

## 📂 Project Structure

DL_project.ipynb # Main Jupyter Notebook
data/
├── train/ # Training images
├── test/ # Testing images
└── labels.csv # Labels for classification
models/
├── base_cnn.h5
├── cnn_l2.h5
└── hybrid_cnn.h5
results/
├── accuracy_loss_curves.png
└── confusion_matrix.png
README.md

yaml
Copy code

---

## 🧩 Key Features

- Binary classification: damaged vs. undamaged areas  
- Explainable AI visualizations (feature maps, activations)  
- Regularization and hybridization for better accuracy  
- Big Data preprocessing for large-scale image inputs  
- Scalable training pipeline with clear modularity  

---

## 📊 Results Summary

| Model | Regularization | Accuracy | Notes |
|-------|----------------|-----------|-------|
| Base CNN | No | ~85% | Good baseline |
| CNN + L2 | Yes | ~89% | Reduced overfitting |
| Hybrid CNN | Combined | ~92% | Best generalization |

*(Results may vary based on dataset splits and hyperparameters.)*

📈 Future Enhancements

Integration with Google Earth Engine for real-time satellite data

Implementation of attention mechanisms (Grad-CAM, SE blocks)

Deployment as a web-based disaster management tool

👥 Author

Krishna Jha
B.Tech | VIT-AP University
CSE (Spec in Artificial Intelligence and Machine Learning)

🪪 License

This project is released under the MIT License
.

⭐ Acknowledgments

Special thanks to faculty mentors and the VIT-AP research community for guidance and computational support.

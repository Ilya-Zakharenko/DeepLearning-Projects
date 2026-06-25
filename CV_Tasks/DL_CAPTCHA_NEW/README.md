# <center> **PROJECT: English Letters CAPTCHA Recognition**

Convolutional Neural Network for recognizing distorted and noisy images of English alphabet letters (A–Z).

---

### **Project Goal**

Develop a robust image classification model capable of high-accuracy recognition of English letters under significant noise, distortion, and blur.

---

### **Dataset**

- **Training data**: 20,000 labeled images (48×48, RGB, 3 channels)
- **Test data**: 50,000 unlabeled images
- **Classes**: 26 (English letters A to Z)
- **Challenge**: Heavy noise, distortion, and blur

---

### **Project Stages**

1. Basic data analysis and familiarization
2. Data preparation and augmentation
3. Model development (CNN architecture)
4. Training with regularization techniques
5. Evaluation and conclusions

---

### **Model Architecture**

- Multiple `Conv2D` + `BatchNormalization` + `MaxPooling2D` blocks
- `Flatten` + `Dense(256)` with `Dropout`
- Output layer with 26 classes (`softmax`)
- **Total parameters**: ~988,122 (3.77 MB)

---

### **Technologies Used**

- `TensorFlow` / `Keras`
- `pandas`, `numpy`
- Data Augmentation (`ImageDataGenerator`)
- `BatchNormalization` and `Dropout` for regularization
- Visualization: `matplotlib`, `seaborn`, `plotly`

---

### **Results**

- **Validation Accuracy**: **0.9003** (90.03%)

---

### **Key Achievements**

- Successfully handled heavily distorted and noisy images
- Applied effective data augmentation and regularization techniques
- Built a deep CNN capable of high accuracy under challenging conditions

---

### **Project Structure**

- `notebooks/` — main Jupyter notebook
- `src/` — model utilities (if any)
- `data/` — `.npy` files (`images.npy`, `labels.npy`, `images_sub.npy`)
- `figures/` — training plots, sample predictions, confusion matrix
- `requirements.txt`

---

### **Conclusion**

This project demonstrates the ability to build a resilient Convolutional Neural Network for image classification in difficult conditions. Achieving 90.03% accuracy on distorted letter images highlights strong skills in computer vision, data augmentation, and model optimization.

---

